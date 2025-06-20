🧠 Panaversity AI Assistant
A conversational AI assistant built with Chainlit, Google Gemini API (via OpenAI-compatible interface), and a custom agent framework. This assistant provides smart, contextual replies by maintaining the history of your conversation.

🚀 Features
💬 Real-time chat using Gemini 2.0 Flash model
🧠 Tracks and remembers chat history for contextual responses
🔐 Secure API key handling using .env
⚙️ Fully customizable agent and model configuration
📁 Project Structure
. ├── agents/ # Contains Agent, Runner, and model logic ├── .env # Environment variables (excluded from Git) ├── main.py # Main Chainlit app script └── README.md # This file

yaml Copy Edit

🛠️ Installation Guide
1. Clone the repository
git clone https://github.com/your-username/panaversity-ai-assistant.git
cd panaversity-ai-assistant
2. Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
🔐 Setup .env
Create a .env file in the root directory and add your Google Gemini API Key:

env
Copy
Edit
GEMINI_API_KEY=your_google_gemini_api_key
▶️ Run the App
bash
Copy
Edit
chainlit run main.py
Once started, open the provided URL in your browser (usually http://localhost:8000) to begin chatting with the assistant.

📦 Requirements
Example requirements.txt:

txt
Copy
Edit
chainlit
python-dotenv
Add any other dependencies required by your custom agents/ code.# Advanced_Chatbot
