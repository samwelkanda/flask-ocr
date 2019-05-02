# Flask-ocr
## A simple-python-optical-character-recognition server. 

Optical Character Recognition involves the detection of text content on images and translation of the images to encoded text that the computer can easily understand. An image containing text is scanned and analyzed in order to identify the characters in it. Upon identification, the character is converted to machine-encoded text.

This project uses:
* Python-Tesseract, or simply PyTesseract, library which is a wrapper for Google's Tesseract-OCR Engine.
*  Flask web framework to create our simple OCR server where we can take pictures via the webcam or upload photos for character recognition purposes.
*  Pillow library which is a fork of the Python Imaging Library (PIL) to handle the opening and manipulation of images in many formats in Python.
