Advanced ATM System with OTP and Facial Recognition


Introduction
Welcome to the Advanced ATM System with OTP and Facial Recognition! This system provides an enhanced level of security for ATM transactions by incorporating two-factor authentication using OTP (One-Time Password) and facial recognition.

Installation Guide

Prerequisites
Python 3 installed on your system.
pip package manager installed.
Steps for Installation
Clone the Repository



To install all dependencies at once run the following command-
pip install -r requirements.txt

(For Virtual Environment run = python -m venv venv)


bash
**************************************
git clone <repository_url>
cd advanced-atm-system
Create a Virtual Environment
It is recommended to create a virtual environment to manage dependencies for this project.

bash
**************************************
python -m venv venv
Activate the Virtual Environment

On Windows:
bash
**************************************
venv\Scripts\activate
On macOS and Linux:
bash
**************************************
source venv/bin/activate
Install Dependencies
Use pip to install the required Python packages from the provided requirements.txt file.

bash
**************************************
pip install -r requirements.txt
Set Up Data Folder

Navigate to the data folder in the project directory.
Replace the sample user_credentials.json file with your own file containing user credentials.
Ensure that the file contains details like card holder name, card number, expiry date, CVV, and account balance.
Run the Flask Application
Execute the following command to start the Flask application.

bash
**************************************
python app.py
Access the Application
Open a web browser and navigate to http://localhost:5000 to access the Advanced ATM System.

Usage
Login: Enter your credentials including card holder name, card number, expiry date, and CVV.
User Dashboard: Upon successful login, you will be redirected to your dashboard where you can perform various transactions.
Transactions: You can withdraw cash, check your account balance, and perform other banking operations.
Logging Out: Click on the logout button to securely logout from your account.


Security Considerations
Always ensure that you are accessing the application over a secure network.
Never share your OTP or banking credentials with anyone.
In case of any suspicious activity or unauthorized access, immediately contact your bank.


License
This project is licensed under the MIT License.





**************************************
Exceptional Errors

For installing cv2 - 
pip install opencv-contrib-python 


For ERROR: Could not build wheels for dlib, which is required to install pyproject.toml-based projects-
pip install dlib <dlib file location in your local repository


**************************************
Customer Data base is in - Data Folder
Face Data base is in - Face Folder

NOTE: Save the face of person with the same name as that of mentioned on ATM Card i.e name on card should match with person's image for successful authentication.
