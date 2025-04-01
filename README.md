# 🖼️ Steganography Project 📚💻

A project focused on **bit manipulation in C** (low-level programming), where we manipulate images to implement **steganography**, a technique used to hide messages or data within images.

## 🚀 Features

- ✅ **Encoding & Decoding** – Hide a message or an image within another image.  
- ✅ **Lossless Extraction** – Retrieve the hidden data without altering the original content.  
- ✅ **Bit-Level Manipulation** – Efficient and optimized implementation in C.  
 
## 📌 How It Works

1️⃣ **Encoding:** The program takes an input image and embeds a hidden message or image within it, modifying the least significant bits (LSBs) of the pixels.  
2️⃣ **Decoding:** The hidden data is extracted by reading the modified bits and reconstructing the original message or image.  

## 📂 How to run

1️⃣ **Clone this repository:**
```bash
git clone https://github.com/MFelisberto/Steganography_Project.git
cd Steganography_Project
```

2️⃣ **Compile the project:**
```bash
gcc -o steganography steganography.c -lm
```

3️⃣ **Run the program:**
```bash
./steganography encode input.bmp secret.txt output.bmp
./steganography decode output.bmp
```

## 🤝 Authors

[Marcelo Augusto Felisberto Martins](https://github.com/MFelisberto)

[Mateus Fritas Charloto](https://github.com/mateusfch)
