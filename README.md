🛣️ AI-Based Road Damage Detection

An AI-powered web application that detects road damage using a custom-trained YOLOv5 model. The application provides visual detection results, damage summaries, optional GPS location, voice assistance, and downloadable CSV reports.

🌐 Live Demo

🚀 Try the application:

"AI-Based Road Damage Detection – Live Demo" (https://roaddamagedetection-cjj7yxcyuekyucuasqbsb5.streamlit.app/)

📌 Project Overview

Road damage, including potholes and surface defects, can create serious problems for road safety and transportation.

This project uses Artificial Intelligence and Computer Vision to automatically identify road damage from images.

Users can upload a road image or capture a photo using a camera. The trained YOLOv5 model analyses the image and displays detected damage with bounding boxes and confidence scores.

✨ Key Features

- 📸 Upload road images or capture photos using a camera.
- 🤖 Road damage detection using a custom-trained YOLOv5 model.
- 🎯 Visual detection with bounding boxes.
- 📊 D20 and D40 damage count summary.
- 📍 Current device location capture (with browser permission).
- 🗺️ Google Maps location link.
- 🔊 Voice-based detection summary.
- 📥 Download detection reports in CSV format.
- 📋 Display confidence scores and bounding-box coordinates.

🛠️ Technologies Used

Technology| Purpose
Python| Main programming language
YOLOv5| Road damage detection
PyTorch| Deep learning framework
Streamlit| Web application interface
Pandas| Data handling and CSV reports
Pillow (PIL)| Image processing
Streamlit Geolocation| Location capture
HTML and JavaScript| Voice assistant

📂 Project Structure

RoadDamageDetection/
│
├── app.py
├── best (2).pt
├── best (4).pt
├── requirements.txt
├── packages.txt
├── README.md
│
├── screenshots/
│   ├── app homepage.png
│   ├── Road image upload.png
│   ├── YOLOv5 detection output.png
│   ├── damage summary.png
│   ├── Gps location.png
│   └── csv report.png
│
└── training_results/
    ├── F1_curve.png
    ├── PR_curve.png
    ├── confusion_matrix.png
    ├── results.png
    ├── results.csv
    └── README.md

⚙️ Installation and Setup

1. Clone the repository

git clone https://github.com/notkrishatall/RoadDamageDetection.git

2. Open the project folder

cd RoadDamageDetection

3. Install dependencies

pip install -r requirements.txt

4. Run the application

streamlit run app.py

🔍 How It Works

1. User uploads a road image or captures a photo.
2. The trained YOLOv5 model processes the image.
3. The model identifies road damage.
4. Bounding boxes and confidence scores are displayed.
5. The application generates a damage summary.
6. Users can access available location information, hear a voice summary, and download a CSV report.

📊 Model Training Results

The "training_results/" folder contains the YOLOv5 training and evaluation files:

- Training results graph
- Confusion matrix
- Precision-Recall curve
- F1 curve
- Results CSV file

🚀 Future Scope

- Improve model performance through further training.
- Integrate a database to store road damage reports.
- Add more road damage categories.
- Improve GPS-based road damage reporting.
- Develop a mobile-friendly road monitoring solution.

👨‍💻 Project Information

Project Title: AI-Based Road Damage Detection

GitHub Repository:
https://github.com/notkrishatall/RoadDamageDetection

Live Demo:
https://roaddamagedetection-cjj7yxcyuekyucuasqbsb5.streamlit.app/

Technologies: Python, YOLOv5, PyTorch and Streamlit
