📄 README — OCR Text Scanner (PyQt5 + OpenCV + Tesseract)

This project is a desktop application that allows users to load images, capture camera frames, draw a Region of Interest (ROI), and extract printed text using Tesseract OCR. The interface is built with PyQt5, and image processing is handled by OpenCV.

✅ Features

Load images from your computer

Use your webcam to capture live frames

Draw a custom ROI on the image

Perform OCR inside the selected region

View and edit extracted text

Save the processed image with OCR overlays

🛠 Technologies Used

Python

PyQt5 (UI Framework)

OpenCV (Image handling + camera)

Tesseract OCR + pytesseract

Pillow (Image conversions)

NumPy

▶️ How to Run

Install all required packages:

pip install PyQt5 opencv-python numpy pillow pytesseract


Install Tesseract OCR from:
https://github.com/UB-Mannheim/tesseract/wiki

Run the application:

python test.py

📌 Usage

Load or capture an image

Draw a rectangle to select the text area

Click Run OCR to extract text

View the results in the text area

Save the overlay if needed
