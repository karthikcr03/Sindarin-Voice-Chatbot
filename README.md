# 🎙️ Sindarin Voice Chatbot Web App

A modern, lightweight, **voice-enabled chatbot** application powered by the [Sindarin SDK](https://sindarin.tech/). This project lets users interact with a custom AI persona through speech, using Web Speech API and real-time transcription in a stylish UI.

Deployed as a fully functional **standalone web app**, this project replicates the core experience of the Sindarin app — now in your browser!

---

## ✨ Features

✅ Start and initialize chatbot session  
⏸️ Pause voice interaction  
▶️ Resume after pause  
🛑 End session and clear state  
📝 Transcribe complete chat session  
🎤 Real-time voice-to-text + text-to-speech  
🧠 Persona memory and live responses  
🎨 Clean, responsive design using Tailwind CSS

---

## 🖼️ Preview

![Chatbot Screenshot]((https://github.com/user-attachments/assets/3bf45734-e8ff-4ed2-8498-eb646ccdfa39)

---


## Add Your Sindarin API Key
In complete-voice-chatbot.html, replace:

html
Copy
Edit
<script src="https://api.prod.centralus.az.sindarin.tech/PersonaClientPublicV2?apikey=YOUR_API_KEY_HERE"></script>
And in JS:

js
Copy
Edit
const API_KEY = "YOUR_API_KEY_HERE";
3. Launch the App
Option A – Open in Browser
Just double-click complete-voice-chatbot.html to open it directly in your browser.

Option B – Serve Locally
## Using Python:

bash
Copy
Edit
python3 -m http.server
Then visit: http://localhost:8000

## Using Node.js (Live Server):

bash
Copy
Edit
npm install -g live-server
live-server

## 🧰 Built With
HTML & JavaScript – Core structure and logic

Tailwind CSS – For beautiful and responsive UI design

Sindarin SDK – For real-time voice persona interaction

Web Speech API – For speech-to-text and text-to-speech support

## 🔧 Customization

Part	How to Customize
Persona	Update personaName and userId in initChat()
Appearance	Modify Tailwind CSS classes in HTML
Transcripts	Enhance or export conversationHistory logic
📜 License
This project is licensed under the MIT License.

## 🙌 Credits
Sindarin

Tailwind CSS

Web Speech API
