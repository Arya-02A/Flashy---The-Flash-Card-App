# 🧠 Flashy - The Hindi-English Flashcard App

Flashy is a simple yet effective GUI flashcard application built with Python. It helps users learn Hindi-English vocabulary using flashcards. Each word appears in Hindi first and flips to reveal its English meaning after a few seconds.

---

## 🚀 Features

- ✅ Automatically shows a Hindi word, then flips to English
- ✅ Tracks which words you’ve learned
- ✅ Saves progress in a CSV file so you can resume later
- ✅ Simple and clean GUI using `tkinter`
- ✅ Built-in timer to flip card after 3 seconds

---

## 🛠️ Tech Stack

- **Python 3**
- **Tkinter** – for GUI
- **Pandas** – for reading and saving word data
- **CSV File Handling** – for persistent learning data

---

## 📁 File Structure

├── main.py # Main application file
├── data/
│ ├── hindi_words.csv # Original vocabulary file
│ └── words_to_learn.csv # Auto-generated: stores remaining words
├── images/
│ ├── card_front.png # Front side of the card (Hindi)
│ ├── card_back.png # Back side of the card (English)
│ ├── right.png # "I know this word" button image
│ └── wrong.png # "I don't know this word" button image

---

## ▶️ How to Run

1. **Install Python** (if not already):  
   [https://www.python.org/downloads](https://www.python.org/downloads)

2. **Clone the repo or download the ZIP**:

   ```bash
   git clone https://github.com/yourusername/flashy.git
   cd flashy
   
3. **Run the App**:
  - python main.py

## 💾 How Progress is Tracked

- When you click the ✅ button, the word is removed from the learning list.
- A new file words_to_learn.csv is automatically created to track your progress.
- If this file exists, it will be used next time instead of the full list.

## 📌 Future Ideas

- Add more languages
- Add a difficulty filter
- Add sound pronunciation
- Progress charts and performance tracking

## 🧠 Made By

- Arya Madiwale
