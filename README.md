# Secure QR Encryption (RSA + Streamlit)

A simple Streamlit app to **encrypt text**, generate **QR codes**, and **decrypt** them securely using **RSA encryption**.

## Features
- RSA key generation  
- Data encryption & decryption  
- QR code creation and scanning  
- Streamlit GUI interface  

## How to Run
```bash
pip install streamlit cryptography qrcode[pil] opencv-python-headless
streamlit run secure_QR.py
