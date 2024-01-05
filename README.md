# BizCardX-Extracting-Business-Card-Data-with-OCR
BizCardX

Project Overview: BizCardX

BizCardX is a user-friendly tool designed for effortless extraction of information from business cards, leveraging the power of Optical Character Recognition (OCR) through the EasyOCR Python library. This project simplifies the OCR process with its straightforward installation, minimal dependencies, and easy integration into your development environment.

Key Features:

    Easy Installation: Install the EasyOCR package with a single pip command, streamlining the setup process for OCR development.
    Minimal Dependencies: Enjoy a hassle-free OCR development environment with minimal dependencies required by EasyOCR.
    Simplified Integration: With just one import statement, EasyOCR seamlessly becomes part of your project, simplifying OCR implementation.
    Effortless OCR: Perform OCR with only two lines of code – one to initialize the Reader class and another to OCR the image using the readtext function.

BizCardX Application:
BizCardX is a versatile tool that harnesses OCR technology to recognize text on business cards, extracting valuable data into a PostgreSQL database. The process involves classification using regular expressions to enhance accuracy. The user interacts with a user-friendly GUI built using Streamlit, guiding them through the steps of uploading a business card image and extracting information.

Key Components:

    Streamlit GUI: A clean and intuitive graphical user interface enables users to easily navigate the extraction process.
    OCR Technology: EasyOCR efficiently recognizes text on business cards, ensuring accurate extraction of valuable information.
    PostgreSQL Integration: The extracted data is stored in a PostgreSQL database, allowing for efficient retrieval and management.

Workflow:

    Image Upload: Users upload a business card image through the Streamlit interface.
    Text Extraction: EasyOCR performs OCR on the uploaded image, extracting relevant text.
    Data Classification: Regular expressions are applied for classification, enhancing data accuracy.
    Database Interaction: The classified data is stored in a PostgreSQL database for easy retrieval and management.
    User Interaction: Users can effortlessly view, update, and delete the stored data through the Streamlit interface.
