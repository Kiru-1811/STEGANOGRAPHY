# LSB Steganography System

A Python-based steganography project developed to securely hide secret text messages inside digital images using Least Significant Bit (LSB) image steganography techniques. The project focuses on secure data hiding and extraction while maintaining image quality.

## Features

- Hide secret text inside images
- Extract hidden messages from encoded images
- Secure image-based data transmission
- User-friendly implementation
- Maintains image quality after encoding
- Supports PNG/JPG image formats

## Technologies Used

- Python
- OpenCV
- NumPy
- Image Processing
- LSB Steganography Technique

## Project Structure

```bash
Kiruthiga_LSB_Stego.ipynb
```

## How It Works

### Encoding Process
- The secret message is converted into binary format.
- Binary bits are embedded into the least significant bits of image pixels.
- Modified image is saved as encoded image.

### Decoding Process
- Encoded image is analyzed pixel by pixel.
- Hidden binary data is extracted.
- Binary values are converted back into readable text.

## How to Run

### Install Required Libraries

```bash
pip install opencv-python numpy
```

### Run the Notebook

Open Jupyter Notebook and execute:

```bash
jupyter notebook
```

Then open:

```bash
Kiruthiga_LSB_Stego.ipynb
```

## Applications

- Secure Communication
- Cybersecurity
- Data Protection
- Digital Information Hiding
- Confidential Data Sharing

## Concepts Implemented

- Image Processing
- Binary Manipulation
- Data Encoding & Decoding
- File Handling
- Cybersecurity Fundamentals

## Project Description

This project was developed to understand practical applications of steganography and cybersecurity using Python. The system securely embeds confidential text messages into digital images without visibly altering the image appearance. It demonstrates secure data hiding techniques and image processing concepts using Python libraries.

## Author

Kiruthiga V
