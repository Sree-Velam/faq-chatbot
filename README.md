# FAQ Chatbot 🤖

A simple and intelligent FAQ Chatbot built with Python using Natural Language Processing (NLP). It matches user questions with predefined FAQs using cosine similarity and provides relevant answers. The chatbot includes a graphical user interface (GUI) built with Tkinter.

---

## 🧠 Features

- ✅ Tokenizes and preprocesses user input using NLTK
- ✅ Matches questions using TF-IDF and cosine similarity
- ✅ Returns the most relevant answer from a custom FAQ list
- ✅ GUI-based interaction using Tkinter
- ✅ Easily extensible: add more questions/answers

---

## 🛠️ Technologies Used

- Python 3.x
- [NLTK](https://www.nltk.org/) – Natural Language Toolkit for preprocessing
- [scikit-learn](https://scikit-learn.org/) – TF-IDF & cosine similarity
- Tkinter – Built-in GUI toolkit for the chatbot interface

---

## 📁 Project Structure

faq-chatbot/
├── faq_chatbot.py # Main Python GUI Chatbot
├── requirements.txt # List of Python dependencies
└── README.md # Project documentation


---

## ⚙️ Installation

1. **Clone the repository** or [download ZIP](https://github.com/Sree-Velam/faq-chatbot/archive/refs/heads/main.zip):

```bash
git clone https://github.com/Sree-Velam/faq-chatbot.git
cd faq-chatbot
2. Install dependencies:
pip install -r requirements.txt
3.Run the chatbot:
python faq_chatbot.py
