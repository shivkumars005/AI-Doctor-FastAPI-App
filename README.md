# 📊 AI-Doctor: Medical Assistant

A medical chatbot that takes an **image** and **text query**, processes them using **GROQ LLMs**, and responds with a diagnosis-like text and **text** reply.

---

## 🚀 Features

* Upload an **image** of a medical scan or photo.
* Ask a question via **text**.
* **LLaMA-based models** (from GROQ) analyze both query and image.
* Displays the AI's response **text**.
* Python **FastAPI for backend**.
* `index.html` UI with TailwindCSS for UI purpose.

---

## 💠 Setup

```bash
git clone https://github.com/shivkumars005/AI-Doctor-FastAPI
cd AI-Doctor-FastAPI
pip install -r requirements.txt
```

Set environment variables in a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key_here
```

---

## 📆 Running the App

```bash
python app.py
```

Then visit: `http://localhost:7860`

---

## 🌐 Deployment

---

## 📁 Project Structure

```
.
├── app.py
├── main.py
├── templates/
│   └── index.html
├── requirements.txt
└── README.md
```

---

## 🙏 Credits

* 🧠 [GROQ](https://groq.com/) – blazing fast inference of open LLMs
---

## 📃 License

MIT License
