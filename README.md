# Sign2Sense
Overview
Sign2Sense is a machine learning-based assistive system that translates American Sign Language (ASL) gestures into both English text and Braille. The goal is to bridge communication gaps for the Deaf-Blind community through real-time gesture recognition, text conversion, and Braille mapping.

By combining real-time image analysis, convolutional neural networks (CNNs), and customizable Braille encoding, Sign2Sense offers a flexible, adaptive, and inclusive communication solution.

Features
  -Real-time ASL gesture recognition using CNN
  
  -Instant conversion to English text
  
  -Automatic translation of text to Braille
  
  -Output saved in Word documents (editable & printable)
  
  -Simple, user-friendly graphical interface
  
  -Easily adaptable to new ASL dialects or Braille standards via CSV-based mapping

Technologies Used
-Python 3

-OpenCV – for image capture and processing

-TensorFlow/Keras – for training CNN model

-pandas / NumPy – for data handling

-docx / python-docx – for generating Word outputs


How It Works
  1. Data Preparation
  ASL gesture images are labeled and stored in a .csv file.
  
  Images are preprocessed (resized, normalized) for model training.
  
  2. Model Training
  A CNN is trained to classify ASL images into corresponding English letters.
  
  3. Real-Time Gesture Recognition
  Camera captures ASL gestures.
  
  The trained model identifies the gesture and converts it to text.
  
  4. Text-to-Braille Conversion
  Text is mapped to Braille characters using a custom conversion table.
  
  Output is saved in Word format, both in English and Braille.
