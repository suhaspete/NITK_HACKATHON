# NITK_HACKATHON

##1
**JARVIS - Your Personal Assistant 🤖**
Welcome to JARVIS, your very own personal assistant! Inspired by the iconic AI from the Marvel universe, JARVIS is designed to help you with general knowledge queries, math calculations, science questions, and more. Whether you interact with it through voice commands or a chat interface, JARVIS is here to make your life easier. 🚀

Features ✨
🎤 Voice Recognition: Converts your spoken words into text using Google Speech Recognition.

🔊 Text-to-Speech: Speaks responses back to you using Google Text-to-Speech (gTTS).

🧠 WolframAlpha Integration: Fetches accurate answers to your queries using the WolframAlpha API.

💬 Chat Interface: A sleek and modern chat interface for text-based interaction.

🎨 Responsive Design: Works seamlessly on all devices (desktop, tablet, mobile).

How It Works 🛠️
System Architecture
JARVIS consists of three main components:

Frontend (Optional): A web-based chat interface built with HTML, Bootstrap, and JavaScript.

Backend: A Python-based server that handles speech recognition, WolframAlpha queries, and text-to-speech synthesis.

WolframAlpha API: Provides computational knowledge and answers to user queries.

Workflow 🔄
🎤 Capture User Input:

The user speaks into the microphone or types a query in the chat interface.

If using voice, the audio is converted into text using speech_recognition.

📤 Send Query to WolframAlpha:

The text input is sent to the WolframAlpha API.

WolframAlpha processes the query and returns a response.

📥 Process Response:

The response is extracted and formatted.

If no response is found, JARVIS provides a fallback message (e.g., "I couldn't find an answer.").

🔊 Convert Response to Speech:

The response text is converted into speech using gTTS.

The speech is saved as an MP3 file and played back to the user.

💬 Display Response:

In the chat interface, the user’s input and JARVIS’s response are displayed in a conversational format.

In voice-only mode, the response is played as audio.

How to Run JARVIS 🚀
Prerequisites
Before running JARVIS, ensure you have the following:

Python 3.x: Install Python from python.org.

Libraries: Install the required Python libraries:

bash
Copy

pip install speechrecognition gtts wolframalpha playsound flask


WolframAlpha API Key: Sign up for a free API key at WolframAlpha.

Microphone: Ensure your system has a working microphone.

Running the Project


Clone this repository:

bash
Copy
```
git clone https://github.com/your-username/jarvis.git
cd jarvis
```
Replace "YOUR_WOLFRAM_ALPHA_API_KEY" in the Python script with your actual API key.

Run the  script:

bash
Copy
```
python jarvis.py
```


JARVIS will greet you and start listening for your commands. 🎉


https://github.com/user-attachments/assets/c2befade-ab6f-4e2a-af75-0f392a7acf20



##2

**AI-Powered Emotion-Aware Interview System**
AI-Powered Emotion-Aware Interview System is an innovative tool that uses artificial intelligence to simulate an interview environment. The system evaluates candidates based on their verbal responses and emotional expressions, offering detailed feedback to help them prepare for real-world interviews.

🎯 Features
Emotion Detection: Uses advanced facial emotion recognition to analyze the candidate's emotional state during responses.
Generative AI for Interview Questions: Leverages Google's Gemini API to generate tailored and professional interview questions based on the job title.
Speech-to-Text: Converts the candidate's verbal responses into text using Google Speech Recognition.
Answer Evaluation: Uses Generative AI to assess the quality of the candidate's responses and provide constructive feedback.
Real-Time Emotion Tracking: Displays a live video feed with emotion statistics, highlighting dominant emotions during each question.
Interactive User Interface: Streamlit-powered frontend for seamless interaction.



🛠️ Technologies Used
Python: Core programming language for backend development.
Streamlit: For building the interactive web interface.
OpenCV: For real-time video processing and display.
FER: For detecting facial emotions.
SpeechRecognition: For converting speech to text.
Google Gemini API: For generating intelligent interview questions and evaluating answers.


🚀 Getting Started
Follow these steps to set up and run the project on your local machine.

Prerequisites
Python 3.x: Ensure Python is installed on your system.
Google Gemini API Key: Obtain an API key from Google Gemini.
Webcam: Required for real-time emotion detection.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/ai-interviewer.git
cd ai-interviewer
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up the API key:

Open the script and replace the placeholder with your Gemini API key:
python
Copy code
GEMINI_API_KEY = "Replace with your Gemini API key"
📖 How to Use
Launch the application:

bash
Copy code
streamlit run app.py
Enter the job title you are interviewing for.

Click "Start Interview" to begin:

The system will ask questions tailored to the specified job role.
Your emotions will be tracked, and responses will be recorded and evaluated.
Review the feedback provided at the end of the interview:

Emotion Analysis: A breakdown of your emotional state during the interview.
Answer Evaluation: AI-generated feedback on your verbal responses.
🔧 Troubleshooting
Issue: "Could not open webcam."

Solution: Ensure your webcam is connected and accessible.
Speech recognition issues:

Check your microphone settings.
Ensure you have a stable internet connection.
Error with API key:

Verify your Gemini API key and replace it if necessary.



https://github.com/user-attachments/assets/e57037b2-b60f-4088-a301-53e0ef102f4e




https://github.com/user-attachments/assets/2d7d8b73-2a43-475b-ab7e-21b7ca67cbe7



##3
Team_Alpha_GPT: Your Autonomous Data Engine ⚙️💡
Team_Alpha_GPT operates as a standalone intelligence core, designed for seamless execution on local systems. With its compact framework, Team_Alpha_GPT eliminates reliance on external servers, granting full operational independence across devices running iOS or Android.

Core Matrix

Core Features

Offline Neural Parsing: Execute localized data synthesis without external networks.
Model Fluidity: Transition seamlessly between miniature models such as Danube 2/3, Phi, and others.
Automated Resource Allocation: Intelligent unloading of non-essential matrices during low-power states.
Dynamic Parameter Control: Modify inference settings like temperature, token configuration, and response architecture.
Performance Analytics: Real-time tracking of computational throughput during response generation.
Installation Protocol

iOS: Deploy via the designated node within Apple’s App Store environment.
Android: Activate systems from Google’s Play Hub.
Operational Parameters

Model Deployment: Activate computational modules via streamlined menu commands.
Advanced Overrides: Fine-tune internal settings through the model dashboard.
Interaction: Input direct queries and retrieve neural responses with zero lag.
Data Extraction: Utilize integrated tools for precise copying of output.
Matrix Expansion

Integration of Hugging Face Protocols: Access and download additional data engines directly via integrated hubs.
Development Constructs

System Frameworks Required: Node.js, Yarn, and environment-specific tools like Xcode or Android Studio.
Initialization Sequence:
sh
Copy code
git clone [REPOSITORY_LINK]  
yarn install  
yarn start  
Functional Checks: Verify local execution using device-specific simulators/emulators.
Evolution Pathways

Broaden ecosystem compatibility.
Enhance UI/UX for optimal user navigation.
Expand neural databases with advanced AI matrices.
License & Attribution
This system operates under open-access licensing models. Special acknowledgments to foundational technologies like llama.cpp and llama.rn.

End transmission.



https://github.com/user-attachments/assets/652946e5-a4ca-4c3b-87c2-10d18dd577d0



