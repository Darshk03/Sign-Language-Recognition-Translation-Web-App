# ✋🖥️ Sign Language Recognition & Translation Web App

## 📖 Overview

A Django-based web application for real-time sign language recognition and translation.  
Utilizes computer vision (MediaPipe, OpenCV) and deep learning (TensorFlow/Keras) to enable users to add new signs, train models, and translate between sign language and text.

---

## 🛠️ Setup & Prerequisites

### 1. **Python Version**
- Python 3.8 or higher is recommended.

### 2. **Clone the Repository**
```bash
git clone https://github.com/yourusername/sign_language.git
cd sign_language
```

### 3. **Create & Activate Virtual Environment** (Recommended)
```bash
python -m venv venv
venv\Scripts\activate
```
*On Linux/macOS, use:*  
```bash
source venv/bin/activate
```

### 4. **Install Dependencies**
All required libraries are listed in `requirements.txt`.  
Install them using:

```bash
pip install -r requirements.txt
```

### 5. **Tech Stack**
See `techstack.txt` for a full list of technologies used.

### 6. **Model Training (First Time Setup)**
No pre-trained model is included.  
To create and train your own sign language recognition model:

```bash
python app/training.py
```
- This script will process your dataset and generate `Dataset/sign_language_model.h5`.

### 7. **Run the Project**
Start the Django development server:

```bash
python manage.py runserver
```
- Access the web app at [http://localhost:8000](http://localhost:8000)

---

## 📦 Project Structure

- `app/` : Django app with views, models, forms, and ML scripts
- `Dataset/` : Stores sign images, label mappings, and trained model
- `media/` : Uploaded images and generated videos
- `static/` : Static files (CSS, JS, images)
- `templates/` : HTML templates
- `requirements.txt` : Python dependencies
- `techstack.txt` : Technology stack details

---

## ⚡ Key Features

- User authentication (register/login)
- Add new signs with webcam capture
- Train and retrain sign recognition model
- Real-time sign-to-text prediction
- Text-to-sign translation (images/videos)
- Extensible dataset for new signs

---

## 📜 License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

```
© 2025 Your Name.  
This software is open-source and free to use under the terms of the GNU GPL v3.
```

---

## 👨‍💻 Developer Notes

- Using a virtual environment is recommended for isolation.
- For video features, ensure you have `opencv-python` and related libraries installed.
- For hand detection, `mediapipe` is required.
- For deep learning, `tensorflow` and `keras` are used.

---

## 🚀 Quick Start

```bash
# Clone, create virtual environment, install dependencies, train model, and run server
git clone https://github.com/yourusername/sign_language.git
cd sign_language
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app/training.py
python manage.py runserver
```

---

## 📝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📧 Contact

For questions or support, contact: darshankeadre1815@gmail.com

