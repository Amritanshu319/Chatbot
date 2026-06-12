# 🧠 Chat With Gemi

An AI-powered web application built using Python, Streamlit, and Google Gemini API. The application provides two intelligent features:
- 🤖 AI ChatBot for real-time conversations.
- 🖼️ Image Captioning using Google's multimodal Gemini model.
## Features
## 🤖 AI ChatBot
Real-time conversational interface.
Context-aware responses using Google Gemini AI.
Session-based chat history.
Clean and interactive Streamlit UI.
🖼️ Image Captioning
Upload images in JPG, PNG, or JPEG format.
Generate image descriptions and captions.
Ask custom questions about uploaded images.
Powered by Gemini's multimodal capabilities.
Technologies Used
Python
Streamlit
Google Gemini API
Pillow (PIL)
python-dotenv
streamlit-option-menu
Project Structure
Project/
│
├── app.py
├── .env
├── requirements.txt
└── README.md
Installation
Clone the Repository
git clone <repository-url>
cd <project-folder>
Create Virtual Environment
python -m venv venv

Activate the environment:

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate
Install Dependencies
pip install -r requirements.txt

Or install manually:

pip install streamlit google-generativeai python-dotenv pillow streamlit-option-menu
Configure API Key

Create a .env file in the project root directory:

api_key=YOUR_GOOGLE_GEMINI_API_KEY
Run the Application
streamlit run app.py

The application will open in your browser at:

http://localhost:8501
How It Works
ChatBot
User enters a message.
Gemini model processes the query.
AI-generated response is displayed in the chat interface.
Image Captioning
User uploads an image.
User enters a prompt such as:
"Describe this image"
"What objects are present?"
"Explain this scene"
Gemini analyzes the image and returns a response.
Future Enhancements
Camera capture support.
Voice input and speech recognition.
Chat history export.
Multi-language support.
User authentication and profiles.
# Author

Amritanshu Sharma
