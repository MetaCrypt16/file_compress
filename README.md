# File Compressor (Huffman Coding) 🚀

![Live Demo](https://img.shields.io/badge/Live_Demo-Click_Here-blue?style=for-the-badge) 

A high-performance, web-based tool for real-time lossless compression of text files using the **Huffman Coding** algorithm. Built entirely with Vanilla JavaScript, it operates 100% locally in the browser, ensuring user data privacy and fast execution.

> **Live Demo:** [https://metacrypt16.github.io/file_compress/](https://metacrypt16.github.io/file_compress/)

---

## 🎯 Key Features
*   **Lossless Compression:** Achieves significant file size reduction (typically 50-60% for text files) without losing a single character of data.
*   **Premium User Interface:** Features a modern, responsive Glassmorphism design with a sleek dark mode and interactive micro-animations.
*   **Browser-Side Processing:** The compression and decompression algorithms run entirely on the client-side via JavaScript. No data is ever sent to a server.
*   **Zero Dependencies:** Built entirely from scratch using fundamental Data Structures without relying on external libraries.

## 🛠️ Technical Implementation
This project practically applies several core computer science concepts and data structures:
*   **Min-Heap (Priority Queue):** Custom implementation used to efficiently build the optimal Huffman Tree.
*   **Hash Maps:** Used for calculating the frequency of each character in $O(N)$ time.
*   **Binary Tree (Huffman Tree):** Generated to assign variable-length binary codes to characters based on their frequency (frequent characters get shorter codes).
*   **Bitwise Operations:** Used to pack the generated binary string into raw bytes for the final compressed output.

## 💻 Tech Stack
*   **Frontend:** HTML5, CSS3 (Flexbox, Glassmorphism), Vanilla JavaScript.
*   **Deployment:** GitHub Pages.

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/MetaCrypt16/file_compress.git
   ```
2. Navigate into the folder:
   ```bash
   cd file_compress
   ```
3. Open `index.html` in any modern web browser. No local server required!

## 📸 Screenshots

*(You can add a screenshot of your beautiful new UI here by placing the image in the repository and linking it!)*