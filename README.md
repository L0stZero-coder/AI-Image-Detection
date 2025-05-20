# **AI Image Detection System**

The **AI Image Detection System** is a web-based application that detects whether uploaded images are AI-generated or naturally captured. This program utilizes advanced machine learning models and image processing techniques, offering accurate results through a user-friendly interface.

---

## **Features**
- Upload and analyze multiple images simultaneously.
- Classifies images as **AI-generated** or **Natural**.
- Professional and responsive web interface with global accessibility.
- Leverages PyTorch for AI detection with Fourier transforms.

---

## **Requirements**
1. **Python 3.12.8**  
   Download the latest Python version [here](https://www.python.org/downloads/).  
   During installation, ensure you check the box **"Add Python to PATH"** to avoid manual configuration.

2. **Virtual Environment**  
   Set up a Python virtual environment to isolate dependencies.

3. **Dependencies**  
   The following libraries are required:
   - `Flask`
   - `torch` (PyTorch)
   - `numpy`
   - `opencv-python`
   - `scipy`
   - `gunicorn`

---

## **Installation Steps**

### 1. **Clone the Repository**
Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/AI-Image-Detection.git
cd AI-Image-Detection
```

---

### 2. **Set Up a Virtual Environment**
Create and activate a virtual environment:
```bash
# Create the virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

---

### 3. **Install Required Libraries**
Install the required dependencies using `pip`:
```bash
pip install -r requirements.txt
```

#### **Installing PyTorch**
Depending on your system configuration, install PyTorch with the following commands:

1. For systems **without GPU (CPU only)**:
   ```bash
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
   ```

2. For systems **with NVIDIA GPU**:
   ```bash
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
   ```

---

### 4. **Run the Program**
Start the Flask application:
```bash
python app.py
```

The app will run locally.

---

## **How to Use**
1. Open the web app in your browser by navigating to your local host.
2. Upload one or multiple images using the provided form.
3. View the detection results displayed in a list format on the webpage.

---

## **Contributing**
Feel free to contribute to this project by opening an issue or submitting a pull request. Any suggestions or improvements are welcome!

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### **Contact**
For inquiries, contact:  
Abdul Musawer  
musawerstanikzai7@gmail.com
https://github.com/L0stZero-coder
