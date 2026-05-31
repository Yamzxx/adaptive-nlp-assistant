# Adaptive NLP Assistant

A simple NLP chatbot built using Python, NLTK, scikit-learn, and Streamlit. The chatbot understands user queries using NLP techniques such as TF-IDF vectorization and cosine similarity for intent matching.

## Features

* NLP-based intent recognition
* TF-IDF and cosine similarity matching
* Predefined chatbot responses
* Context-aware conversations (basic memory)
* Interactive Streamlit interface
* Multiple domains support (Python, Git, DSA, Docker, etc.)

## Project Structure

```txt
chatbot/
│── app.py
│── chatbot_engine/
│   ├── preprocess.py
│   ├── intent_classifier.py
│   ├── response_engine.py
│   ├── context_manager.py
│── data/
│   ├── intents.json
│   ├── faq_knowledge.json
│── requirements.txt
│── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone <your-repository-link>
cd nexus-nlp
```

### 2. Create a Virtual Environment

Windows (PowerShell)

```bash
python -m venv venv
.\venv\Scripts\Activate.ps1
```

Windows (CMD)

```bash
venv\Scripts\activate.bat
```

macOS/Linux

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Project

Start the Streamlit app:

```bash
streamlit run app.py
```

The chatbot will open in your browser.

## Technologies Used

* Python
* NLTK
* scikit-learn
* Streamlit
* NLP (TF-IDF, cosine similarity)

## Future Improvements

* Voice input and output
* Better context understanding
* More chatbot intents and domains
* Improved UI/UX

## Author

Built as an NLP chatbot project using Python and Streamlit.
