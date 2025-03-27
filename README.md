# AI Voice Agent with OpenAI SDK

## Overview
This project is an **AI-powered Voice Agent** built using the **OpenAI SDK**. It enables users to interact with an AI assistant through voice commands, providing intelligent responses based on OpenAI's language models.

## Features
- 🎤 **Voice Input:** Converts user speech into text.
- 🧠 **AI-Powered Responses:** Uses OpenAI models to process queries.
- 🔊 **Text-to-Speech (TTS):** Converts AI-generated responses back into speech.
- 🔄 **Seamless Interaction:** Users can have real-time conversations with the AI.
- 📂 **Customizable Settings:** Adjust voice, model, and response styles as needed.

## Technologies Used
- **Python** 🐍
- **OpenAI SDK** 🤖
- **SpeechRecognition** (for voice input) 🎙️
- **pyttsx3** (for text-to-speech) 🔊
- **Flask/FastAPI** (optional, for web API integration) 🌐

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/voice-agent-openai.git
   cd voice-agent
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Set Up Environment Variables**
   - Create a `.env` file in the root directory and add your OpenAI API key:
     ```env
     OPENAI_API_KEY=your_openai_api_key_here
     ```

## Usage
### Running the AI Voice Agent
Run the following command to start the voice assistant:
```sh
python voice_agent.py
```

### Interacting with the Agent
- Speak into your microphone.
- The AI will process your speech and generate a response.
- The response will be read back to you using text-to-speech.

## Configuration
You can modify the AI model and voice settings inside the `config.py` file:
```python
OPENAI_MODEL = "gpt-4o"
VOICE = "male"
LANGUAGE = "en"
```

## Future Improvements
- ✅ Integrate with **Twilio** for phone call-based AI conversations.
- ✅ Deploy as a **web app** for wider accessibility.
- ✅ Add support for **multiple languages**.

## Contribution
Pull requests are welcome! If you have suggestions, feel free to open an issue. 🚀

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

## Contact
For any inquiries, contact me at: `baseek8@gmail.com` 📩

