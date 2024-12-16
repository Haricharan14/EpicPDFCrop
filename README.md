# EpicPDFCropper

EpicPDFCropper is a user-friendly application designed to help you crop PDF files easily and efficiently. Built using PyQt5 and PyMuPDF, this tool allows you to open, view, and crop PDF documents with a simple and intuitive interface.

## Features

- **Open PDF Files**: Load your PDF documents with ease.
- **Crop PDF Pages**: Select and crop specific areas of your PDF pages.
- **Zoom In/Out**: Adjust the view to focus on specific sections of your PDF.
- **User-Friendly Interface**: Designed with a clean and intuitive layout for a seamless user experience.
- **Progress Indicators**: Visual feedback during loading and cropping processes.
- **Display all pages at once with decreased opacity, allowing you to see how each page aligns with the others**

## Installation

Just Download the Exe file from Releases
(OR)
You can also run with python
To run EpicPDFCropper, you need to have Python installed on your machine. Follow these steps to set up the application:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/EpicPDFCropper.git
   cd EpicPDFCropper
   ```

2. Install the required packages:
   ```bash
   pip install PyQt5 PyMuPDF Pillow numpy
   ```

3. Run the application:
   ```bash
   python pdf_crop_pyqt.py
   ```


## Usage

1. Open the application.
2. Click on the "Open PDF" button to load your PDF file.
3. Use the mouse to draw a rectangle around the area you want to crop.
4. Click the "Crop PDF" button to save the cropped area as a new PDF file.
5. Use the zoom buttons to adjust the view as needed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro) for the GUI framework.
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/) for handling PDF files.
- [Pillow](https://python-pillow.org/) for image processing.
