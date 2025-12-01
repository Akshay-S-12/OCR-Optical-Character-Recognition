
# 📝 OCR - Optical Character Recognition


## 🔍 Overview
**OCR - Optical Character Recognition** is a Python-based project that extracts text, words, and dates from uploaded images. It converts printed text in images into editable digital text, making it useful for digitizing documents, receipts, and other scanned materials. This project demonstrates practical applications of computer vision and OCR technologies.  

---

## ✅ Features
- 🖼️ **Image Text Extraction:** Recognize text from uploaded images.  
- 📅 **Word & Date Detection:** Extract words, numbers, and date information.  
- 📂 **Multi-format Support:** Works with JPEG, PNG, and other common image formats.  
- ✨ **Simple Interface:** Upload an image and get textual output.  

---

## 🛠 Technology Stack
- **Language:** Python  
- **Libraries:** OpenCV, pytesseract (Tesseract OCR)  
- **Tools:** VS Code / Jupyter Notebook  

---

## 📁 Project Structure
```
OCR-Optical-Character-Recognition/
├── images/                           # Sample/test images
├── output/                           # Optional: store extracted text
├── main_script.py                    # Main Python script
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
```

---

## 📥 Installation & Setup
1. Clone the repository:  
```bash
git clone https://github.com/Akshay-S-12/OCR-Optical-Character-Recognition.git
cd OCR-Optical-Character-Recognition
```
2. (Optional) Create a virtual environment:  
```bash
python -m venv venv
# Activate it
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate
```
3. Install dependencies:  
```bash
pip install -r requirements.txt
```
4. Ensure Tesseract OCR is installed on your system and configured properly.  

5. Run the project:  
```bash
# For a single image
python main_script.py --image path/to/image.jpg
```

---

## 🧪 Usage
- Upload an image containing printed text.  
- The system will detect and extract text, including dates and numeric data.  
- Output is displayed in console or saved to a file (depending on your script setup).  

---

## 📸 Example Output
```
Input Image: receipt.jpg
Detected Text:
Invoice Date: 01-12-2025
Customer Name: John Doe
Total Amount: ₹1,234
```

---

## 🚀 Future Enhancements
- 📄 Support PDF input and batch processing.  
- 🖌️ Add bounding boxes around detected text regions.  
- 🌐 GUI or web interface for easy uploads.  
- 🗂️ Export structured data to CSV or JSON.  
- 🌍 Multi-language OCR support.  

---
 



## 📜 License
This project is licensed under the **MIT License**.
