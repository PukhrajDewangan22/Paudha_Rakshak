
# 🌿 Paudha Rakshak

**Paudha Rakshak** is a responsive web-based application built using **Flask** and **Machine Learning** to detect plant diseases from images. Users can **upload plant leaf images** or **capture photos using the device’s rear camera**. Based on the image, the app detects the disease and provides:

- 🌱 Disease name  
- 💊 Precautionary measures  
- 🌾 Recommended fertilizers and supplements  

Additionally, the platform allows users to **borrow essential gardening items**, such as **fertilizers, supplements, and other plant-care equipment**, making it a complete tool for plant health and management.

---

## 📸 Features

- Detect plant diseases using a trained ML model
- Upload images or capture using the rear camera
- Get precautions and treatment recommendations
- Borrow plant essentials like fertilizers and supplements
- Clean, responsive design for all screen sizes
- Backend powered by Flask; image processing with Pillow; data lookup with Pandas

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **ML**: scikit-learn / TensorFlow *(update if needed)*
- **Libraries Used**:
  - `Flask` – Web application framework
  - `Pandas` – For data lookup and mapping
  - `Pillow` – For image preprocessing
  - `scikit-learn` – For model prediction

---

## 📁 Project Structure

```

Paudha-Rakshak/
│
├── static/                 # CSS, JavaScript files
├── templates/              # HTML files (Jinja templates)
├── model/                  # Trained ML model
├── uploads/                # Uploaded plant images
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

````

---

## 🧪 How to Access and Run the Project

### 🔧 Installation & Setup Instructions

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

3. **Add `requirements.txt` Manually**

Create a file named `requirements.txt` inside your project folder (`Paudha-Rakshak/`)
Copy and paste the following lines into the file:

```txt
Flask
pandas
Pillow
scikit-learn
```

> ✅ *You can add more packages if your app uses them.*

4. **Install Dependencies**

```bash
pip install -r requirements.txt
```

5. **Run the Flask App**

```bash
python app.py
```

6. **Open the Application in Browser**

Navigate to:
👉 `http://127.0.0.1:5000`

---

## 🧾 Tasks Performed

* Built user interface using HTML, CSS, and JavaScript
* Integrated device rear-camera functionality
* Used Pillow to handle uploaded and captured images
* Applied a machine learning model to classify plant diseases
* Used Pandas to fetch and display treatment and fertilizer info
* Added feature to borrow essential plant care equipment

---

## ✅ Sample Output



---

### 💻 Output Web Interface

![Result Output](https://via.placeholder.com/500x300?text=Disease+Result+Displayed)

---

## 👨‍💻 Authors

* **Pukhraj Dewangan**
* **Shasank Baxi**

---

## 📃 License

This project is licensed under the **MIT License**.


---

Let me know if you'd like this as a `.md` file download or if you want to generate actual screenshots from your app!
