# 🌍 Language Translator Chatbot

A simple and beginner-friendly Language Translator Chatbot built using Python and the Deep Translator library. This project allows users to translate text from one language to another automatically using Google Translate services.

The chatbot automatically detects the source language and translates the text into the target language selected by the user.

---

# 📌 Project Overview

Language barriers can make communication difficult. This Language Translator Chatbot helps users instantly translate text into multiple languages.

This project demonstrates:

* Python Programming
* API Integration
* Language Translation
* User Interaction
* Chatbot Development

It is an excellent beginner project for learning Python and working with real-world APIs.

---

# 🚀 Features

✅ Translate text into multiple languages

✅ Automatic source language detection

✅ Interactive chatbot interface

✅ Beginner-friendly implementation

✅ Real-time translation

✅ Lightweight and fast

✅ Supports 100+ languages

---

# 🛠️ Technologies Used

| Technology             | Purpose              |
| ---------------------- | -------------------- |
| Python                 | Programming Language |
| Deep Translator        | Translation Library  |
| Google Translator      | Translation Engine   |
| Input/Output Functions | User Interaction     |

---

# 📂 Project Structure

```text
language-translator-chatbot/
│
├── app.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/language-translator-chatbot.git

cd language-translator-chatbot
```

## Step 2: Install Dependencies

```bash
pip install deep-translator
```

---

# ▶️ Run The Project

```bash
python app.py
```

---

# 💻 Source Code

```python
from deep_translator import GoogleTranslator

print("🌍 Language Translator")

while True:
    text = input("\nEnter text: ")

    if text.lower() == "exit":
        break

    target_lang = input("Translate to (hi, en, fr, de, es): ")

    translated = GoogleTranslator(
        source='auto',
        target=target_lang
    ).translate(text)

    print("\nTranslated Text:")
    print(translated)
```

---

# 🔍 Complete Code Explanation

## 1. Import GoogleTranslator

```python
from deep_translator import GoogleTranslator
```

### Purpose

Imports the GoogleTranslator class from the Deep Translator library.

This class is responsible for sending translation requests and returning translated text.

---

## 2. Display Welcome Message

```python
print("🌍 Language Translator")
```

### Purpose

Displays the chatbot title when the program starts.

Output:

```text
🌍 Language Translator
```

---

## 3. Infinite Loop

```python
while True:
```

### Purpose

Keeps the chatbot running continuously until the user exits.

---

## 4. Take User Input

```python
text = input("\nEnter text: ")
```

### Purpose

Accepts text from the user for translation.

Example:

```text
Hello, how are you?
```

---

## 5. Exit Condition

```python
if text.lower() == "exit":
    break
```

### Purpose

Stops the program when the user enters:

```text
exit
```

---

## 6. Target Language Input

```python
target_lang = input("Translate to (hi, en, fr, de, es): ")
```

### Purpose

Allows users to choose the target language.

Example:

```text
hi
```

for Hindi translation.

---

## 7. Translation Process

```python
translated = GoogleTranslator(
    source='auto',
    target=target_lang
).translate(text)
```

### Breakdown

### source='auto'

Automatically detects the source language.

Example:

```text
Hello
```

Detected as:

```text
English
```

---

### target=target_lang

Specifies the target language selected by the user.

Example:

```text
hi
```

means Hindi.

---

### translate(text)

Translates the provided text.

Example:

Input:

```text
Hello
```

Output:

```text
नमस्ते
```

---

## 8. Display Translation

```python
print("\nTranslated Text:")
print(translated)
```

### Purpose

Displays the translated text to the user.

---

# 🔄 Project Workflow

```text
User Input
     │
     ▼
Language Detection
     │
     ▼
Target Language Selection
     │
     ▼
Google Translation Service
     │
     ▼
Translated Output
     │
     ▼
Display Result
```

---

# 🌐 Supported Language Codes

| Language   | Code  |
| ---------- | ----- |
| English    | en    |
| Hindi      | hi    |
| French     | fr    |
| German     | de    |
| Spanish    | es    |
| Japanese   | ja    |
| Korean     | ko    |
| Chinese    | zh-CN |
| Arabic     | ar    |
| Russian    | ru    |
| Italian    | it    |
| Portuguese | pt    |

---

# 📊 Example

## Input

```text
Enter text: Hello, how are you?
Translate to: hi
```

## Output

```text
नमस्ते, आप कैसे हैं?
```

---

## Input

```text
Enter text: I am learning Python.
Translate to: fr
```

## Output

```text
J'apprends Python.
```

---

# 🎯 Applications

* Language Learning
* Travel Assistance
* International Communication
* Educational Projects
* Translation Services
* Multilingual Chatbots

---

# Advantages

* Easy to Use
* Supports Multiple Languages
* Real-Time Translation
* Beginner Friendly
* Lightweight Project
* Automatic Language Detection

---

# Limitations

* Requires Internet Connection
* Depends on Google Translation Services
* Translation Quality May Vary
* Limited Customization

---

# Future Enhancements

* Voice Translation
* PDF Translation
* Text File Translation
* Speech-to-Text Translation
* Streamlit Web Interface
* Translation History
* Dark Mode UI
* Multi-user Support

---

# Time Complexity

### Input Processing

```text
O(1)
```

### Translation Request

```text
O(n)
```

Where:

```text
n = Length of Input Text
```

---

# Learning Outcomes

After completing this project, you will understand:

* Python Programming
* API-Based Applications
* Language Translation Systems
* User Input Handling
* Chatbot Development
* Third-Party Library Integration

---

# Resume Description

Developed a multilingual Language Translator Chatbot using Python and Deep Translator. The application automatically detects the source language and translates user-provided text into multiple target languages using Google Translation services.

---

# 👨‍💻 Author

## Ajay Sagar

* Python Developer
* AI & Machine Learning Enthusiast
* B.Tech CSE Student

### Connect With Me

🔗 LinkedIn: https://www.linkedin.com/in/engineerajay

🚀 Building AI Projects and Learning New Technologies Every Day.

**Code the Future with Us..!**
