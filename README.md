# Steganography - Hide a Secret Text Message in an Image

This project is a **GUI-based Steganography tool** built using Python and Tkinter. It allows users to **hide secret text messages inside images** using the **LSB (Least Significant Bit) technique** and retrieve the hidden message later.

## Features
- 📷 **Open and Preview Images**
- 🔏 **Hide a Secret Message** inside an image
- 🔍 **Reveal Hidden Messages** from an image
- 💾 **Save the Modified Image**
- 🖼 **Supports PNG & JPG Files**

## Installation
### **Prerequisites**
Ensure you have **Python 3.x** installed on your system. Then, install the required dependencies using pip:

```sh
pip install pillow stegano
```

## How to Run the Project
1. **Clone the Repository** (if applicable) or save the script as `steganography.py`.
2. Open a terminal and navigate to the folder containing `steganography.py`.
3. Run the script using:

   ```sh
   python steganography.py
   ```

## Usage Guide
### **1️⃣ Open an Image**
Click on the **"Open Image"** button and select a PNG or JPG image from your system.

### **2️⃣ Hide a Message**
- Type a secret message into the text box.
- Click on the **"Hide Data"** button to embed the message inside the selected image.

### **3️⃣ Save the Image**
- Click the **"Save Image"** button to save the modified image as `hidden.png`.

### **4️⃣ Retrieve the Message**
- Open an image that contains a hidden message.
- Click the **"Show Data"** button to reveal the secret text.

## Project Structure
```
📂 Project Folder
 ├── steganography.py  # Main Python script
 ├── README.md         # Project documentation (this file)
```

## Dependencies
- **Tkinter** - GUI library for Python
- **Pillow (PIL)** - Image processing library
- **Stegano** - Library for LSB-based steganography

## Potential Improvements
- ✅ Add support for more image formats.
- ✅ Implement password-protected message encryption.
- ✅ Improve the UI for better user experience.

---


