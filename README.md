steganography-tool

hide messages in images

Steganography Tool - Hidden Data in Images

📌 Introduction

Steganography is the practice of concealing messages within digital media. This project provides a GUI-based tool that allows users to hide encrypted messages inside images using the Least Significant Bit (LSB) technique. This tool now includes a Streamlit-based web interface for improved usability.

🎯 Features

🖼 Load an image (PNG, JPG)

🔑 Encrypt and embed a secret message

🛠 Decode and retrieve the hidden message

🔐 Secure encryption using Fernet

💾 Save the modified image

🎨 Simple GUI with tkinter and Web UI with Streamlit

🛠 Technologies Used


Python (Core Programming Language)
tkinter (Desktop GUI Development)
Streamlit (Web-based GUI)
Pillow (PIL) (Image Processing)
NumPy (Image Data Manipulation)
Cryptography (Encryption & Decryption)


📦 Required Libraries
Ensure you have the following Python libraries installed:

pip install pillow numpy cryptography streamlit fernet
🚀 Installation
Ensure Python is installed on your system.

pip install pillow numpy cryptography streamlit fernet

🎮 Usage
Using the Desktop GUI:
Run the script:
python steganography_tool.py
Click "Load Image" and select an image file.
Enter the secret message you want to hide.
Click "Generate Key" to create an encryption key.
Click "Encode Message" to embed the encrypted message into the image.
Click "Save Image" to store the modified image.
Using the Web Interface (Streamlit):
Run the Streamlit app:
streamlit run streamlit_steganography.py
Upload an image.
Enter the secret message and generate an encryption key.
Click "Encode" to hide the message within the image.
Click "Decode" to retrieve a hidden message from a modified image.


🔥 Future Enhancements


Support for additional image formats (BMP, TIFF)
Drag-and-drop image loading
User-defined encryption keys
Image preview before saving
Advanced steganography techniques for better security

