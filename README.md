Text Summarizer AI App
A tiny AI-powered app that summarizes news articles or blog posts into 3 concise sentences.
This project is part of the Intern Assignment: Build a Tiny AI-Powered App. The goal is to show effort, creativity, and learning using AI, even without prior coding experience.

Features
Summarizes any text input into 3 sentences.
Command-line interface for easy testing.
Demonstrates use of AI APIs (Hugging Face or OpenAI) for NLP tasks.

Setup Instructions (Part 1)
-Install Python (≥3.8 recommended).
-Clone this repository:
git clone https://github.com/your-username/text-summarizer-ai.git
-Navigate to the project folder:
cd text-summarizer-ai
-Install dependencies:
pip install -r requirements.txt
-Set up API key (Hugging Face or OpenAI):
export HUGGINGFACE_API_KEY="your_api_key_here"
(Windows users: use set instead of export.)

Usage (Part 2)
-Run the Python script:
python summarizer.py

Paste or type your text (news article, blog post, or any long text).
Receive a summarized version in 3 sentences.

Example Usage Snippet
from summarizer import summarize_text
text = """
Artificial Intelligence is rapidly transforming the way humans interact with technology...
"""
summary = summarize_text(text)
print(summary)

Learning Notes
Explored Hugging Face transformers for text summarization.
Documented all attempts, errors, and solutions throughout the project.
Experimented with input formatting, model selection, and output style.
Practiced integrating APIs and building a simple CLI app.

Contributing
This project is for learning and experimentation.
You can fork and extend it by adding a UI, deploying online, or improving the summarization model.
