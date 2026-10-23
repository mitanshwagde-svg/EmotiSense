# 🧠 EmotiSense

## NLP Sentiment & Emotion Analyzer

EmotiSense is an NLP-based sentiment and emotion analysis application that combines traditional Natural Language Processing techniques with Google's Gemini Large Language Model.

The application accepts natural language text and analyzes its overall sentiment, emotional characteristics, and important keywords.

---

## 🚀 Features

- Sentiment classification
- Sentiment confidence score
- Multi-emotion detection
- Dominant emotion identification
- AI-generated emotional explanation
- Text preprocessing
- Tokenization
- Stopword removal
- TF-IDF keyword extraction
- Google Gemini API integration
- Structured JSON responses
- Streamlit-based interactive interface
- Fallback handling for temporary Gemini API failures

🤖 LLM Integration
EmotiSense uses the Google Gemini API for contextual sentiment and emotion analysis.

The LLM is instructed through an external prompt file to return structured JSON containing:
- Overall sentiment
- Sentiment confidence
- Emotion intensity scores
- Explanation of the analysis
The application uses multiple Gemini models as fallbacks when a model is temporarily unavailable.
🎭 Supported Emotions
The system analyzes the following emotions:
- Joy
- Sadness
- Anger
- Fear
- Disgust
- Surprise
- Neutral
The system can identify multiple emotions in the same text.
🛠️ Technology Stack
- Python
- Streamlit
- NLTK
- Scikit-learn
- Google Gemini API
- Google GenAI SDK
- python-dotenv

---

## 🧠 NLP Pipeline

The application follows this pipeline:

```text
User Input
    ↓
Text Cleaning
    ↓
Tokenization
    ↓
Stopword Removal
    ↓
TF-IDF Keyword Extraction
    ↓
Gemini LLM Analysis
    ↓
Sentiment + Emotion Classification
    ↓
Interactive Results
