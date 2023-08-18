# OneTongue.ai

OneTongue.ai is a web application built using Streamlit that allows users to transcribe, translate, and synthesize audio files. The core functionalities of the application are:
- Transcribe audio files to text using OpenAI.
- Translate the transcribed text to various languages using Google Cloud Translate.
- Synthesize the translated text back to audio using Google Cloud Text-to-Speech.

## Prerequisites

To use OneTongue.ai, you need the following:

- Python 3.x
- Streamlit
- OpenAI Python SDK
- Google Cloud Translate and Text-to-Speech Python SDKs
- python-dotenv

## Installation

1. Clone the repository:

```
git clone <repository_url>
cd <repository_directory>
```

2. Install the required packages:

```
pip install streamlit openai google-cloud-translate google-cloud-texttospeech python-dotenv
```

3. Create a `.env` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=your_openai_api_key
```

Make sure to also set up the Google Cloud SDK and authentication as described in their official documentation.

## Usage

Run the app using Streamlit:

```
streamlit run <filename>.py
```

Once the app is running:

1. Upload an audio file (supported formats: m4a, mp3, wav).
2. Select the target language for translation.
3. Select the gender for synthesized voice.
4. Choose the specific voice for the selected language and gender.
5. Click "Execute" to transcribe, translate, and synthesize the audio.
6. Once processed, you can play the translated audio.

## Features

- **Transcribe Audio**: Transcribe audio files to text.
- **Translate Text**: Translate the transcribed text to English, Spanish, or Korean.
- **Synthesize Audio**: Convert the translated text back to audio using various voices.

## License

This project is open-source. Feel free to use, modify, and distribute as per your requirements.
