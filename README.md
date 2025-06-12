
# 🌿 Paudha Rakshak

**Paudha Rakshak** is a responsive web-based application built using **Flask** and **Machine Learning** to detect plant diseases from images. Users can **upload plant leaf images** or **capture photos using the device’s rear camera**. Based on the image, the app detects the disease and provides:

- 🌱 Disease name
- 💊 Precautionary measures
- 🌾 Recommended fertilizers and supplements

Additionally, the platform allows users to **borrow essential gardening equipment**, including **fertilizers, supplements, and other plant-care tools**, making it a comprehensive tool for plant care and disease prevention.

---

## 📸 Features

- Detect plant diseases using machine learning
- Upload or capture plant images through the browser
- View detailed precautions and treatments
- Responsive and mobile-friendly design
- Borrow essential items like fertilizers and supplements
- Powered by Flask, Pandas, and Pillow for fast and accurate results

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: scikit-learn / TensorFlow *(update if needed)*
- **Libraries Used**:
  - `Pandas` – for handling disease and treatment data
  - `Pillow` – for image processing
  - `Flask` – web server and routing

---

## 📁 Project Structure

```

Paudha-Rakshak/
│
├── static/                 # CSS, JavaScript files
├── templates/              # HTML files (Jinja templates)
├── model/                  # Trained machine learning model
├── uploads/                # Uploaded images
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

````

---

## 🧪 How to Access and Run the Project

### 🔧 Installation Steps

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/Paudha-Rakshak.git
cd Paudha-Rakshak
````

2. **Create and Activate Virtual Environment**

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. **Create `requirements.txt` File**

Run this command to generate it:

```bash
pip freeze > requirements.txt
```

Ensure it contains essential packages like:

```txt
Flask
pandas
Pillow
scikit-learn
```

If not, install them:

```bash
pip install Flask pandas Pillow scikit-learn
```

4. **Install Required Packages**

```bash
pip install -r requirements.txt
```

5. **Run the Flask App**

```bash
python app.py
```

6. **Open in Browser**

Visit: `http://127.0.0.1:5000`

---

## 🧾 Tasks Performed

* Created a frontend with HTML, CSS, JavaScript
* Integrated camera functionality for real-time image capture
* Preprocessed plant images using Pillow
* Used ML model to predict plant diseases
* Displayed precautions and fertilizers using Pandas
* Implemented option to borrow gardening essentials

---

## ✅ Sample Output

### 🔼 Upload or Capture Image

![Upload Screen](https://via.placeholder.com/500x300?text=Upload+or+Capture+Image)

---

### 🧠 Model Prediction Result

```json
{
  "Disease": "Leaf Blight",
  "Precaution": "Avoid overhead watering. Remove infected leaves.",
  "Fertilizer": "Apply organic potassium-based fertilizer."
}
```

---

### 💻 Output Web Interface

![Result Output](https://via.placeholder.com/500x300?text=Disease+Result+Displayed)

---

## 👨‍💻 Author

**Pukhraj Dewangan**

---

## 📃 License

This project is licensed under the **MIT License**.



---

Let me know if you'd like a downloadable file version or GitHub formatting preview.
