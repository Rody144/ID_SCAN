
# ID Scanner App

The **ID Scanner App** is a Python-based web application that allows users to upload an image of an ID card and extract text from it using Optical Character Recognition (OCR). The app is built using the `streamlit` library for the user interface and `pytesseract` for OCR functionality.

## Features

- Upload images in formats like `.jpg`, `.png`, `.jpeg`, and `.webp`.
- Extract text from uploaded images using Tesseract OCR.
- Display the extracted text in an organized format.
- Simple and interactive web interface.

## Requirements

- Python 3.11 or higher
- Tesseract OCR installed on your system ([Download Tesseract](https://github.com/tesseract-ocr/tesseract))

## Installation

1. Clone this repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install streamlit opencv-python pytesseract pillow numpy
   ```
3. Ensure Tesseract OCR is installed and its path is correctly set in the script:
   ```python
   pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run ID_Scanner.py
   ```
2. Open the provided URL in your browser.
3. Upload an image of an ID card.
4. View the extracted text displayed on the web interface.

## File Structure

- `Untitled-1.ipynb`: A Jupyter Notebook used for development and writing the main script.
- `ID_Scanner.py`: The main Python script for the Streamlit app.

## Example Output

- **Uploaded Image**: Displays the uploaded ID card image.
- **Extracted Text**: Shows the extracted text, including:
  - Organization Name
  - Employee Name
  - Additional details from the ID card.

## Notes

- Ensure the Tesseract OCR executable is installed and accessible.
- The accuracy of text extraction depends on the quality of the uploaded image.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
```

Save this content as `README.md` in your project directory. Let me know if you need further assistance!
