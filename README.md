# Table Extraction Project

This project is designed to extract and process table data from images using OCR (Optical Character Recognition). The extracted data is then transformed into a structured format like CSV for further analysis and usage.

## Requirements

To run this project, you will need the following:

- Python 3.7+
- paddleOCR
- OpenCV
- pandas
- numpy

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shashank-vaidya/OCR_table_extraction.git
   ```

2. **Set up a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare your image data:**

   Ensure that the images you want to process are in a suitable format for OCR. This project includes preprocessing steps to enhance image quality for better OCR results.

2. **Run the main script:**

   The main script processes the images and extracts table data. To run the script, use the following command:

   ```bash
   python main.py
   ```

3. **Output:**

   The extracted table data will be saved in a CSV file. Check the `output.csv` file for the results.

## Project Files

- `OcrToTableTool.py`: Contains functions for OCR processing and table data extraction.
- `TableExtractor.py`: Includes methods to locate and extract table structures from images.
- `TableLinesRemover.py`: Preprocesses images to remove lines and improve OCR accuracy.
- `main.py`: Main script to run the complete table extraction process.
- `output.csv`: Example output file with extracted table data.
- `LICENSE`: License information for the project.
- `README.md`: Project documentation and instructions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
