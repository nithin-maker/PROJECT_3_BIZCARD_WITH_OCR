# BizCardX - Business Card Data Extraction

BizCardX is a Streamlit application designed to extract information from business cards using Optical Character Recognition (OCR) technology. It allows users to upload an image of a business card, extract relevant information such as name, designation, company, contact details, and store the extracted information along with the uploaded image in a database.

## Features

- Extracts information from business card images using OCR.
- Displays extracted information in a tabular format.
- Allows users to upload business card images.
- Stores extracted information and uploaded images in a database.
- Provides a user-friendly interface for interacting with the application.

## Technologies Used

- Python
- Streamlit
- easyOCR
- PostgreSQL
- Pandas

## Setup Instructions

1. Clone the repository:

git clone https://github.com/your-username/BizCardX.git


2. Install dependencies:

pip install -r requirements.txt


3. Run the Streamlit application:

streamlit run app.py


4. Access the application in your web browser at http://localhost:8501.

## Usage

1. Upload a business card image using the file uploader.
2. Once the image is uploaded, the application will extract information from the image using OCR.
3. Extracted information will be displayed in a table format on the user interface.
4. Click the "Upload to database" button to store the extracted information and uploaded image in the database.

## Database Configuration

- The application uses PostgreSQL as the database. Make sure to configure the database connection in `db.py` file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.







