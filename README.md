## 🧠 About the Project

**Vision to Voice** is an intelligent multimedia project that automatically **generates captions for images** using deep learning and **converts those captions into spoken audio**. It supports **real-time image capture** or upload and produces audio output in **English**, **Tamil**, or **Hindi**.

This is especially helpful for:
- Visually impaired users 👁️‍🗨️
- Language learners 🌍
- AI/ML demonstrators 🎓

---

## 🚀 Features

- 📸 **Real-time webcam image capture** in Google Colab
- 📁 **Image upload** from device
- 🤖 **Automatic image captioning** using BLIP model
- 🌐 **Language translation**: English 🇬🇧, Tamil 🇮🇳, Hindi 🇮🇳
- 🔊 **Text-to-speech** output with `gTTS`
- ✅ Fully interactive in Google Colab

---

## 📷 Demo Flow

[Image] ➜ [BLIP Model] ➜ [Generated Caption] ➜ [Translation] ➜ [Speech Output]

yaml
Copy
Edit

🧪 **Example**:

- Input: 🐱 *An image of a cat on a couch*
- Caption: `"A cat sitting on a couch in a living room"`
- Output in Tamil: `"ஒரு பூனை ソபாவில் அமர்ந்துள்ளது..."`

---

## 🛠️ Tech Stack

| Component         | Library/Tool                            |
|------------------|------------------------------------------|
| 💡 Image Captioning | `BLIP (Salesforce - Hugging Face)`       |
| 🌍 Translation     | `googletrans==4.0.0-rc1`                 |
| 🗣️ Text-to-Speech  | `gTTS (Google Text-to-Speech)`           |
| 🖼️ Image Processing | `Pillow`, `OpenCV`, `IPython.display`     |
| ⚙️ Backend Runtime | Google Colab, Python 3.x                 |
| 🧠 ML Framework    | `PyTorch`, `Transformers`                |

---

## 🔧 Installation (Colab Recommended)

1. Clone this repo or open the notebook in **Google Colab**
2. Run the notebook step-by-step
3. Upload or capture an image
4. Choose a language
5. Listen to the result!

### 📦 Install Required Packages (if using locally):
```bash
pip install gtts transformers torch pillow opencv-python googletrans==4.0.0-rc1
