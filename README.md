# ImageEditor

ImageEditor is a Flask-based web application that allows users to upload and edit images with various features such as filters, cropping, blur, rotation, face detection, text extraction, and an undo-redo system. Users can also download their edited images.

## Features

1. **Filters**: Apply various filters to images for different effects.
2. **Crop**: Crop images to focus on specific areas.
3. **Blur**: Apply blur effects to parts of an image.
4. **Rotation**: Rotate images to desired angles.
5. **Face Detection**: Detect faces in images.
6. **Text Extraction**: Extract text from images.

## Technologies Used

- Flask: Web framework for Python
- Pillow: Image processing library
- cv2: OpenCV library for computer vision
- pytesseract: OCR (Optical Character Recognition) library
- tempfile: Temporary file management
- base64: Encoding and decoding images
