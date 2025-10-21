🗣️ AI Voice Assistant using Python, Google Gemini API & LiveKit

A real-time AI Voice Assistant built using Python, Google Gemini API, and LiveKit for seamless two-way audio communication.
This project demonstrates speech recognition, natural language understanding, and text-to-speech generation integrated into a fully functional prototype.

🚀 Features

🎙️ Real-time voice interaction — Talk naturally with the assistant.

🧠 AI-powered responses — Uses Google Gemini API for intelligent conversation handling.

🔊 Text-to-Speech (TTS) and Speech-to-Text (STT) support.

🌐 LiveKit Integration — Enables live audio streaming and real-time communication.

🧩 Modular Architecture — Easy to extend or customize.

🧰 Tech Stack
Component	Technology Used
Programming Language	Python
AI Model	Google Gemini API
Real-Time Communication	LiveKit
Speech Recognition	SpeechRecognition / Google Speech API
Text-to-Speech	pyttsx3 / gTTS
Environment	VS Code / Jupyter Notebook
📦 Installation
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/ai-voice-assistant.git
cd ai-voice-assistant

2️⃣ Create and Activate a Virtual Environment
python -m venv venv
# For Windows
venv\Scripts\activate
# For macOS/Linux
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

🔑 API Setup

Google Gemini API

Get your API key from Google AI Studio
.

Add it to your environment variables or a .env file:

GEMINI_API_KEY=your_api_key_here


LiveKit

Create an account on LiveKit
 and obtain your API credentials.

Add them to .env:

LIVEKIT_API_KEY=your_api_key_here
LIVEKIT_API_SECRET=your_secret_here

▶️ Usage

Run the application:

python main.py


Then speak to your AI assistant — it listens, processes, and responds in real time!

🧠 How It Works

Speech-to-Text (STT): Captures audio input and converts it into text.

Natural Language Understanding (NLU): Sends the text to the Google Gemini API for intelligent response generation.

Text-to-Speech (TTS): Converts AI’s text response back into voice output.

LiveKit Integration: Handles real-time audio streaming and bidirectional communication.

'''📂 Project Structure(JARVIS)
JARVIS/
├── .idea/               # IDE configuration files
├── __pycache__/         # Compiled Python cache
├── jarviz/              # Main assistant logic and modules
├── KMS/                 # Knowledge Management / support scripts
├── venv/                # Virtual environment
│
├── .env                 # Environment variables (API keys)
├── agent.py             # Core voice assistant logic
├── prompt.py            # System prompts / AI instructions
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation '''


🧩 Example Output
You: Hey, what’s the weather like today?
Assistant: It’s 28°C and sunny in your area. Perfect day for a walk!

🤝 Contributing

Contributions are welcome!
If you’d like to enhance the assistant, add features, or fix bugs:

Fork the repo

Create a new branch (feature-new-idea)

Commit your changes

Push and create a Pull Request

📜 License

This project is licensed under the MIT License — feel free to use and modify it.

💡 Future Improvements

🌍 Multi-language support

🧏 Visual avatar integration

📱 Web-based voice interface

🧩 Plugin system for custom commands
