📌 Project Overview

The Real-Time Face Attendance System is an AI-powered application that automates attendance tracking using facial recognition technology. It captures live video feeds, detects faces, and marks attendance in real time.

🚀 Features

Live Face Detection & Recognition

Automated Attendance Marking

Secure & Efficient

User-Friendly Interface

Database Storage for Attendance Records

Works with Multiple Users

🛠️ Technologies Used

Programming Language: Python

Libraries & Frameworks: OpenCV, NumPy, Pandas, Face Recognition Library

Database: SQLite / MySQL

Tools: Jupyter Notebook / VS Code

📂 Project Structure

Real-Time-Face-Attendance-System/
│── dataset/                 # Stored face images
│── trained_model/           # Pre-trained face recognition model
│── haarcascades/            # Pre-trained face detection models
│── attendance.csv           # Attendance log file
│── AMS_Run.py               # Main script to run attendance system
│── training.py              # Script to train the model
│── retrain.py               # Script to update the dataset
│── testing.py               # Script to test recognition accuracy
│── requirements.txt         # Dependencies
│── README.md                # Project Documentation

🎯 Installation & Setup

Step 1: Clone the Repository

git clone https://github.com/aryan3877/Real-Time-Face-Attendance-System.git
cd Real-Time-Face-Attendance-System

Step 2: Install Dependencies

pip install -r requirements.txt

Step 3: Run the System

python AMS_Run.py

📸 How It Works

The system captures images from the webcam.

It detects faces using Haarcascade classifiers.

The model compares detected faces with the stored dataset.

Attendance is automatically marked and saved in attendance.csv.

👨‍💻 Contributing

Feel free to fork the repository, create a new branch, and submit a pull request with your enhancements.

🔐 Privacy & Security

All captured images are stored locally.

No data is sent to external servers.

📞 Contact

Author: Aryan GitHub: https://github.com/aryan3877

⭐ If you found this project helpful, don't forget to star the repository! ⭐
