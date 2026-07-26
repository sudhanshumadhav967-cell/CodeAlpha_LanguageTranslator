# 🤖 FAQ Chatbot using Python

## 📌 Project Overview

This project is a simple **FAQ Chatbot** built using Python.
It answers user queries by matching the input question with a predefined set of FAQs using basic Natural Language Processing (NLP) techniques.

The chatbot calculates similarity between user input and stored questions, then returns the most relevant answer.

---

## 🚀 Features

* Predefined FAQ-based responses
* Text preprocessing (lowercase, punctuation removal)
* Similarity matching using word comparison
* Interactive command-line chatbot
* Handles unknown queries gracefully

---

## 🛠️ Technologies Used

* Python 🐍
* Basic NLP (text preprocessing)
* Set-based similarity (Jaccard similarity)

---

## 📂 Project Structure

```
faq-chatbot/
│── chatbot.py        # Main chatbot code
│── README.md         # Project documentation
```

---

## ⚙️ How It Works

### 1️⃣ FAQ Storage

FAQs are stored in a Python dictionary:

* **Key** → Question
* **Value** → Answer

---

### 2️⃣ Text Preprocessing

User input and FAQ questions are cleaned by:

* Converting to lowercase
* Removing punctuation

---

### 3️⃣ Similarity Matching

* Words are split into sets
* Common words are compared
* Similarity is calculated using:

```
Similarity = Common Words / Total Unique Words
```

---

### 4️⃣ Response Generation

* The chatbot selects the most similar question
* Returns the corresponding answer
* If similarity is low, it shows a fallback message

---

## ▶️ How to Run the Project

### Step 1: Install Python

Make sure Python is installed (version 3.x)

### Step 2: Clone Repository

```
git clone https://github.com/your-username/faq-chatbot.git
cd faq-chatbot
```

### Step 3: Run the Program

```
python chatbot.py
```

---

## 💬 Example Interaction

```
Welcome to the FAQ Chatbot! Type 'exit' to end the conversation.

You: what is python
Chatbot: Python is a high-level, interpreted programming language known for its readability and versatility.

You: what is chatbot
Chatbot: A chatbot is a software application designed to simulate human conversation.

You: who is virat kohli
Chatbot: Sorry, I couldn't understand your question.
```

---

## 🔧 Future Improvements

* Add more FAQs for better accuracy
* Use advanced NLP techniques (TF-IDF, Cosine Similarity)
* Create GUI using Tkinter
* Convert to web app using Flask or Django
* Add voice support

---

## 🎯 Learning Outcomes

* Understanding of basic NLP preprocessing
* Implementing similarity matching
* Building a simple chatbot system
* Hands-on Python project experience

---

## 📜 License

This project is open-source and free to use.

---


