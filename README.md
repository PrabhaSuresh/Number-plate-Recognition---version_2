# 🚗🔐 NPR Enabled Security System

![Project Banner](https://your-image-link.com/banner.png)

## 📌 Overview

The **NPR Enabled Security System** is an **AI-powered vehicle identification system** that detects vehicles, extracts their number plates, and logs the data for **security and entry management**.

- 🚘 Uses **YOLOv11** for **real-time vehicle & number plate detection**
- 🔍 Employs **PaddleOCR** for **highly accurate text extraction** from number plates
- 📂 Automatically **stores extracted details** (vehicle number, timestamp, and images) in an **Excel file** for security logging

## 🎯 Key Features

- ✅ **Real-time vehicle detection** using **YOLOv11** 🚘
- ✅ **Number plate recognition** with a **fine-tuned YOLOv11 model** 🎯
- ✅ **OCR-based text extraction** using **PaddleOCR** 📝
- ✅ **Automatic data logging** in an **Excel file** 📊
- ✅ **Vehicle image storage** for security reference 🖼️
- ✅ **Vehicle count index** for tracking entries 🔢
- ✅ **User-friendly interface** with real-time visualization 🖥️

## 🛠️ Tech Stack

- 🚀 **Deep Learning Model:** YOLOv11
- 📷 **OCR Engine:** PaddleOCR
- 🐍 **Programming Language:** Python
- 📦 **Libraries:** OpenCV, NumPy, Pandas, TensorFlow/PyTorch
- 📑 **Database:** CSV/Excel for data storage

## 🔄 Project Workflow

1️⃣ **Vehicle Detection** 🚘
   - YOLOv11 detects vehicles in real-time

2️⃣ **Number Plate Detection** 🎯
   - A **fine-tuned YOLOv11 model** localizes number plates

3️⃣ **OCR Processing** 📝
   - PaddleOCR extracts **text from the detected number plate**

4️⃣ **Data Logging** 📊
   - Extracted details (**number, timestamp, vehicle image**) are stored in an Excel file

5️⃣ **Display & Storage** 🖥️
   - Real-time display of the extracted number, with **vehicle images saved for security records**

## 📥 Installation Guide

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/PrabhaSuresh/Number-plate-Recognition---version_2.git
cd Number-plate-Recognition---version_2
```

### 🔹 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 3. Download YOLOv11 Model Weights
- 🎯 Download the YOLOv11 pre-trained weights and place them in the `models/` directory.
- 🔗 [Download Weights](#)

### 🔹 4. Run the System 🚀
```bash
python main.py
```

### 🔹 5. View Extracted Data
- The extracted vehicle numbers, timestamps, and images will be saved in an Excel file (`vehicle_logs.xlsx`).
- Images of detected vehicles and their number plates will be stored in the `images/` directory.

## 📑 Data Storage Format

The extracted data is stored in an Excel file with the following structure:

| 🔢 Index | 🚘 Number Plate | ⏰ Timestamp | 🖼️ Vehicle Image Path |
|----------|----------------|-------------|----------------------|
| 1️⃣ | ABC1234 | 2025-03-24 10:15 AM | images/abc1234.jpg |

## 🚀 Future Enhancements

- ✨ Cloud database integration for remote monitoring ☁️
- ✨ Automatic gate control for seamless vehicle access 🚦
- ✨ Enhanced OCR accuracy with deep-learning text recognition 🤖
- ✨ Web dashboard for monitoring vehicle entries 📊

## 🤝 Contributing

🎯 We welcome contributions! Feel free to fork this repository, create a new branch, and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

## 📧 Contact

For any queries or contributions, feel free to connect at:
- 📩 prabhasuresh2006@gmail.com
