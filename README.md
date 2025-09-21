Image to PDF Converter

A simple desktop application built with Python and Tkinter that allows users to select multiple images and convert them into a single PDF file.

Features

Select multiple images (PNG, JPG, JPEG).

Preview selected images in a listbox.

Enter a custom name for the output PDF.

Automatically scales images to fit PDF pages while maintaining aspect ratio.

Generates a PDF with one image per page.

Requirements

Python 3.x

Tkinter
 (usually included with Python)

Pillow
 (pip install Pillow)

ReportLab
 (pip install reportlab)

Installation

Clone this repository:

git clone https://github.com/Keaton-Nordby/ImageToPDFConverter.git
cd ImageToPDFConverter


Install dependencies:

pip install Pillow reportlab

Usage

Run the application:

python main.py


Click Select Images to choose the images you want to include in your PDF.

Enter a name for your PDF in the input field.

Click Convert to PDF.

The PDF will be saved in the same directory as the script (default name is output.pdf if no name is provided).
