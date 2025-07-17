# ✍️ Handwriting to Text Converter (Frontend)

This is the **frontend interface** of a modern AI-powered web app that converts handwritten images into editable text using [TrOCR](https://huggingface.co/microsoft/trocr-base-handwritten), a Transformer-based OCR model by Microsoft.

🔗 Live demo:(https://github.com/ethancoens/handwriting-ocr-frontend.git)]([https://github.com/ethancoens/handwriting-ocr-frontend.git](
## 🚀 Features

- 🖼️ Upload handwritten image
- 🧠 Sends image to Flask + TrOCR API for recognition
- 📃 Displays clean extracted text
- 📱 Responsive design with **TailwindCSS**
- 🆓 Hosted on GitHub Pages (free hosting)

---

## 💡 Technologies Used

- HTML5 + TailwindCSS (via CDN)
- Vanilla JavaScript (Fetch API)
- Backend API (see: [handwriting-ocr-backend]([https://github.com/yourusername/handwriting-ocr-backend](https://github.com/ethancoens/handwriting-ocr-frontend.git)))
- Deployed with GitHub Pages

---

## 🛠 How It Works

1. User uploads a handwritten image
2. JavaScript sends the image to a Python Flask API endpoint:
