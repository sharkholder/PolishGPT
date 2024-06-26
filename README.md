# Multi-Type File Handling System

## Project Overview

This Flask-based web application enables efficient handling of multiple file types, including DOCX, PDF, XLSX, PPTX, PNG, JPG, and JPEG. It facilitates uploading files, displaying their content, and interacting with the content through a Q&A functionality, making it suitable for data and text management across various sectors such as education, legal document management, and business operations.

## Features

- **File Uploads**: Supports uploading multiple types of files.
- **Content Display**: Dynamically displays content from uploaded files.
- **Q&A Functionality**: Allows users to interact with the uploaded content through a Q&A interface.
- **Responsive Web Design**: Ensures a user-friendly interface across various devices.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What you need to install the software:

```
bash
Python 3.8 or later
Flask
PyPDF2
python-docx
openpyxl
```

### Installing
A step-by-step guide on setting up your development environment:

#### Clone the repository
```
bash
git clone https://github.com/yourusername/multi-type-file-handler.git
cd multi-type-file-handler
```

#### Set up a virtual environment (Optional but recommended)
```
bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

#### Install the required packages
```
bash
pip install -r requirements.txt
```

#### Run the application
bash
```
export FLASK_APP=app.py  # On Windows use `set FLASK_APP=app.py`
flask run
```
Navigate to http://127.0.0.1:5000/ in your web browser to view the application.

### Usage
How to use the application:

Uploading a File: Navigate to the Upload page, select a file, and hit the upload button.
Viewing Content: After uploading, the content of the file will be displayed on the screen.
Asking Questions: Use the Q&A section to type in your questions regarding the file content.
### Built With
Flask - The web framework used.
HTML/CSS/JavaScript - For creating a responsive frontend.
PyPDF2, python-docx, openpyxl - Used for handling different file types.
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.
