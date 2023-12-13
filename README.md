# BizcardX
BizCardX - Business Card Information Extraction and Management
BizCardX is a Python application designed to simplify the process of extracting and managing information from business cards. This project utilizes various technologies, including Streamlit, EasyOCR, OpenCV, and MySQL database, to achieve its functionality.

Project Overview:
The primary goal of BizCardX is to allow users to upload an image of a business card, extract relevant details using Optical Character Recognition (OCR), and manage the extracted data efficiently. The project offers a user-friendly interface, enabling users to view, update, and delete information from the MySQL database.

Features:
1. Image to Text Conversion:
Users can upload an image of a business card.
The application uses EasyOCR and OpenCV to extract text from the uploaded image.
Specific information such as name, designation, contact, email, website, address, city, state, and pincode is extracted.

2. Database Integration:
Extracted information is stored in a MySQL database named "cards."
The application checks if the required table ("card_data") exists and creates it if not.
Users can view the extracted data in an interactive table, including the business card images.

3. Update and Delete Records:
Users have the option to update or delete information from the database.
The "Update data" functionality allows users to modify specific fields for a selected person.
The "Delete data" functionality removes a person's record from the database.

Getting Started:
Install the required dependencies using pip install -r requirements.txt.
Configure your MySQL database details in the code (mydb connection).
Run the application using streamlit run your_script_name.py.
Access the application through the provided URL in the terminal.

Dependencies:
Streamlit

MySQL Connector

EasyOCR

Requests

Pillow

OpenCV

Pandas

SQLAlchemy

NumPy
