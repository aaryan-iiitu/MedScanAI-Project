# MedScanAI

**MedScanAI** is an AI-powered diagnostic assistant that integrates voice input, image analysis, and natural language processing to provide medical insights. Leveraging the capabilities of the **Groq API** and **ElevenLabs API**, it offers an interactive interface for users to receive audio-based medical feedback.

---

## Features

- **Voice Input**: Captures patient voice input and converts it to text.
- **Image Analysis**: Processes uploaded medical images (e.g., skin conditions).
- **AI Diagnosis**: Uses the Groq API to generate intelligent, context-aware medical responses.
- **Voice Output**: Converts AI-generated text to speech using ElevenLabs API.
- **User Interface**: Intuitive Gradio web app for real-time interaction.

---

## Installation

1. **Clone the Repository**

git clone https://github.com/aaryan-iiitu/MedScanAI-Project.git
cd MedScanAI-Project/MedScanAI

2. **Set Up a Virtual Environment**

pip install pipenv
pipenv shell
pipenv install


3. **Set API Keys**

   
Create a `.env` file in the `MedScanAI` directory with the following content:
GROQ_API_KEY=your_groq_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key


## Usage
Run the Gradio app:

python gradio_app.py



Then:
1. Record or upload the patient's voice.
2. Upload a medical image.
3. Receive AI-generated medical suggestions — both as text and spoken output.
