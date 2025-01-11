# NITK_HACKATHON



J.A.R.V.I.S - Voice Assistant with WolframAlpha Integration
J.A.R.V.I.S (Just A Rather Very Intelligent System) is a voice-activated assistant built using Python. The assistant responds to voice commands, provides answers to queries using WolframAlpha, and can convert text to speech for seamless interaction.

🎯 Features
Voice Input: Captures user input through the microphone.
Speech Recognition: Uses Google's Speech Recognition API to process spoken commands.
Text-to-Speech: Converts responses to audio using gTTS (Google Text-to-Speech).
WolframAlpha Integration: Retrieves detailed answers to user queries from WolframAlpha's knowledge base.
Error Handling: Handles errors gracefully, ensuring a smooth user experience.
Exit Command: Easily terminate the program by saying "exit."
🛠️ Technologies Used
Python: Core programming language.
gTTS: For generating speech from text.
Playsound: For playing audio responses.
SpeechRecognition: For processing user voice input.
WolframAlpha API: For fetching answers to user queries.
🚀 Getting Started
Follow these steps to set up and run the project on your local machine.

Prerequisites
Python 3.x installed on your system.
WolframAlpha API Key:
Sign up at WolframAlpha Developer Portal.
Create an app and obtain your unique API key.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/voice-assistant.git
cd voice-assistant
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Add your WolframAlpha API key:
Open the script (app.py).
Replace the placeholder key with your API key:
python
Copy code
client = wolframalpha.Client("YOUR_API_KEY")
📖 How to Use
Run the script:
bash
Copy code
python app.py
The assistant will greet you with:
rust
Copy code
Hi Noah, what can I do for you?
Speak your query into the microphone. Examples:
"What is the capital of France?"
"Who is Albert Einstein?"
Listen to the response as the assistant speaks it aloud.
Exit the Program
Say "exit" to terminate the program.

🔧 Troubleshooting
Issue: "Couldn't find ffmpeg or ffprobe."

Solution: Install ffmpeg and add it to your system's PATH. Download here.
Error: "Speech recognition error."

Solution: Check your internet connection and ensure your microphone is working.
WolframAlpha query errors:

Verify your API key is correct and active.
Ensure your query is valid and understandable.
📂 Directory Structure
bash
Copy code
voice-assistant/
├── app.py               # Main script
├── requirements.txt     # Python dependencies
└── README.md            # Project description
🤝 Contributing
Contributions are welcome! Feel free to:

Report issues.
Suggest features.
Submit pull requests.
Steps to Contribute
Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Commit your changes:
bash
Copy code
git commit -m "Add feature-name"
Push to your branch:
bash
Copy code
git push origin feature-name
Open a pull request.
