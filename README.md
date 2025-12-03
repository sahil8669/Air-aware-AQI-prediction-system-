# 🤖 Simple Chatbot in Python using NLTK

This project demonstrates how to build a **simple rule-based chatbot** using Python and the **NLTK (Natural Language Toolkit)** library. The chatbot can respond to user input with basic conversational replies.

---

## 📌 Features

- Preprocessing of user input using NLTK tools (tokenization, lemmatization).
- Rule-based response selection using cosine similarity.
- Use of `TF-IDF` vectorization for matching queries.
- Interaction via a command-line interface (CLI).
- Graceful exit with the keyword: `bye`.

---

## 🛠️ Technologies Used

- Python
- NLTK
- NumPy
- scikit-learn

---

## 🧠 Concepts Covered

- Tokenization
- Lemmatization
- TF-IDF Vectorization
- Cosine Similarity
- Rule-based NLP approach

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/simple-chatbot-nltk.git
cd simple-chatbot-nltk
```

### 2. Install dependencies

```bash
pip install nltk scikit-learn numpy
```

### 3. Run the notebook

Launch Jupyter Notebook and open `Simple_chatbot_in_python_using_nltk.ipynb`.

```bash
jupyter notebook
```

---

## 🧪 Sample Usage

```plaintext
BOT: Hello! I am your chatbot. If you want to exit, type 'bye'.
You: Hi
BOT: Hello!

You: What is AI?
BOT: Artificial Intelligence (AI) is the simulation of human intelligence processes by machines...

You: bye
BOT: Bye! Take care.
```

---

## 📂 Project Structure

```
├── Simple_chatbot_in_python_using_nltk.ipynb
└── README.md
```

---

## 📌 Notes

- Make sure you have an active internet connection when running the NLTK download commands for the first time (`nltk.download()`).
- This is a rule-based bot and not trained on deep learning models.

---

## 👨‍💻 Author

- **Your Name** (replace with your GitHub or LinkedIn if needed)

---

## 📄 License

This project is open-source and free to use under the MIT License.
