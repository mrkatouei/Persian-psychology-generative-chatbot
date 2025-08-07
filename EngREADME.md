


---

# 🧠 Persian Psychology Generative Chatbot

Welcome to the **Persian Psychology Generative Chatbot** project – an open-source AI chatbot designed for understanding and responding in **Persian (Farsi)**, using real-world conversations from Persian forums. This project is ideal for researchers, developers, and enthusiasts of **natural language processing**, **psychology**, and **AI-driven dialogue systems**.

---

## 📌 About the Project

This repository explores various approaches to building a **Persian-language generative chatbot**, with a focus on psychological and lifestyle topics. The current dataset is scraped from the well-known Persian forum **Ninisite**, containing rich and real conversations.

> 💬 *"The goal is not only to generate replies, but to create empathetic, culturally-aware AI assistants in Persian."*

---

## 📊 Dataset

The chatbot is trained on conversation pairs crawled from Ninisite.com, one of the largest Persian lifestyle forums. The script for crawling is available in the [`/data/ninisite`](data/ninisite) directory.

### 🧾 Sample Conversation
```json
{
  "topic": "بیمارستان هدایت تهران برای زایمان چطوره؟",
  "question": [
    "سلام خانما",
    "من تو بیمارستان میلاد برای بارداری و زایمان پرونده دارم...",
    "شنیدم بیمارستان هدایت فقط زنان و زایمانه؟ کسی تجربه داره؟"
  ],
  "answer": [
    "آره من ۲۶ سال پیش اونجا بدنیا اومدم، مامانم خیلی راضی بود."
  ]
}

📈 Dataset Stats (Live Update)

Total Topics	Crawled Topics	Conversation Pairs	Size

636,921	48,708 (7%)	1,221,025	778MB



---

🚀 Getting Started

📦 Installation

Clone the repository and install the dependencies:

git clone https://github.com/mrkatouei/Persian-psychology-generative-chatbot.git
cd Persian-psychology-generative-chatbot

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

▶️ Run the Chatbot

Once setup is complete:

python main.py


---

🧠 Technologies Used

Python 3.7+

Scrapy (for data crawling)

PyTorch / minGPT (for language modeling)

JSON, UTF-8 Persian text handling

Persian NLP and data preprocessing utilities



---

✨ Features

Generative chatbot trained on real Persian dialogues

Modular and extensible codebase

Lightweight and offline-capable

Easy dataset expansion with new sources



---

👤 Author

Created with ❤️ by:

Dr. Mohammadreza Katoueizade
AI Researcher & Psychologist
📧 Email: mr.katouei@gmail.com
🔗 GitHub: @mrkatoueizade


---

🧠 Future Work

Fine-tuning with psychological response modeling

Interactive web-based chatbot interface

Expanding to include psychological assessments

Emotion-aware and sentiment-guided responses



---

📄 License

This project is released under the MIT License.


---

> “AI should not only be intelligent — it should be empathetic.”



---
