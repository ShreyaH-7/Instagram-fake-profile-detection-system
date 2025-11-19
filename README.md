📘 Instagram Fake Profile Detection System

This project is an Instagram Fake Profile Detection System that analyzes user profiles and predicts whether an Instagram account is real or fake.
It uses a combination of Machine Learning, Face Recognition, and Instaloader-based scraping to extract public Instagram details.

The system also includes an Admin Dashboard, User Login, Data Visualization, and Face Detection module for profile validation.

🚀 Features

🔍 Fake Profile Prediction using XGBoost ML Model

👤 Face Detection + Face Matching

📸 Image Upload + Webcam Capture Support

📊 Charts and Graphs (Pie, Bar, Line Charts)

📥 Username-based Details Extraction using Instaloader

📁 Storage of known faces for comparison

💬 User Login / Registration System

🛠 Admin Dashboard to monitor flagged profiles

📂 Multiple UI pages (HTML Templates) with clean visuals

🛠 Tech Stack Used
Frontend

--HTML
--CSS
--JavaScript
--Bootstrap

Backend

--Python
--Flask Framework
--Machine Learning
--XGBoost Classifier
--Face Recognition Library
--OPENCV (cv2)

Tools / Libraries

Instaloader

Git LFS (for handling large images)

SQLite Database

📁 Project Structure
📦 Instagram Fake Profile Detection System
 ┣ 📂 Face Detection/
 ┣ 📂 Screenshots/
 ┣ 📂 images/
 ┣ 📂 instance/
 ┣ 📂 known_faces/
 ┣ 📂 models/
 ┣ 📂 pages new/
 ┣ 📂 static/
 ┣ 📂 templates/
 ┣ app.py
 ┣ uname_scraper.py
 ┣ requirements.txt
 ┣ .gitattributes
 ┗ README.md

▶️ How the System Works
1️⃣ Username Input / Manual Input

User enters:

Username
or

Manual details (followers, following, bio length etc.)

2️⃣ Instaloader Fetch

If username is entered:

Public data → scraped

Followers, following, profile pic, description length collected

3️⃣ ML Model Prediction

Data is sent to the XGBoost model, which predicts:

Fake Profile  OR  Real Profile

4️⃣ Face Detection (Optional)

Face from uploaded image is compared with known_faces folder

Helps identify impersonation

5️⃣ Results Displayed

User sees:

Fake/Real

Probability

Graphs

Summary

▶️ How to Run the Project Locally
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run the App
python app.py

3️⃣ Open in Browser:
http://127.0.0.1:5000/

📊 Screenshots (Optional Section)

Add your uploaded screenshots here:

./Screenshots/

🔮 Future Improvements

Add deep learning model for better accuracy

Improve UI with Tailwind/React

Add API endpoint for mobile app integration

Add automatic scraping bypass for private accounts

Add impersonation detection using multiple face comparison

👩‍💻 Author

Shreya H
Instagram Fake Profile Detection System —
