💰 Simple Expense Tracker
A straightforward, user-friendly web application for tracking personal expenses, powered by a Python Flask backend and Google's Firebase Firestore database for real-time data storage.

✨ Features
User Authentication: Secure sign-in and sign-up with email and password using Firebase Authentication.

Real-Time Tracking: Add expenses with details like amount, description, and category. Expenses are saved and synced in real-time.

Monthly Reports: View a detailed breakdown of your spending for any given month, with a calculated total.

Budget Management: Set a monthly budget and receive a notification if your total spending exceeds it.

Responsive Design: The application is built with a clean, modern interface using Tailwind CSS, ensuring it looks great on both desktop and mobile devices.

🚀 Getting Started
Follow these steps to set up and run the project locally.

Prerequisites
Python 3.x: Make sure you have Python installed.

Firebase Project: You need to create a new project on the Firebase Console.

Firebase Service Account Key: This is a JSON file needed for the backend to connect to your Firebase project. You can generate it from Project settings > Service accounts in the Firebase Console.

Installation
Clone the repository:

git clone [https://github.com/your-username/expense-tracker.git](https://github.com/your-username/expense-tracker.git)
cd expense-tracker

Install dependencies:

pip install -r requirements.txt

Configuration
This project requires you to configure two files with your Firebase credentials: index.html (for the frontend) and app.py (for the backend).

Configure Frontend (index.html):

Open index.html.

Go to your Firebase Console, navigate to Project settings > General, and find your web app configuration.

Copy the firebaseConfig object and paste it directly into the <script> tag at the bottom of the index.html file, replacing the placeholder code.

Configure Backend (app.py):

Open app.py.

Find the firebase_config dictionary at the top of the file.

Copy the entire contents of your downloaded Firebase Service Account key JSON file and paste it as the value for the firebase_config variable.

Running the Application
Start the Flask backend server:

python app.py

Open your web browser and navigate to http://127.0.0.1:5000 to view the application.

🤝 Contribution
Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

📄 License
This project is licensed under the MIT License.
