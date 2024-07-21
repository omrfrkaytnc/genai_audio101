# genai_audio101

genai_audio101 is a versatile Streamlit application that leverages OpenAI and AssemblyAI to perform various audio operations,
including text-to-speech synthesis, transcription, and translation. 
This project integrates these functionalities into an intuitive web interface, 
making it easy to process audio files and generate speech from text.

## Features

- **Text-to-Speech Synthesis (TTS)**
  - Converts input text into speech using OpenAI's TTS-1 model.
  - Supports multiple voice types including alloy, echo, fable, onyx, nova, and shimmer.

- **Transcription with Whisper**
  - Transcribes audio files into text using OpenAI's Whisper model.
  - Supports Turkish language transcription.

- **Translation with Whisper**
  - Translates audio files into text in another language using OpenAI's Whisper model.

- **Transcription with Conformer**
  - Transcribes audio files using AssemblyAI's Conformer model.

## Installation

To get started with genai_audio101, you'll need to install the required dependencies. You can do this by running:

```bash
pip install -r requirements.txt
```

Ensure you have the following environment variables set up in a .env file:
```env
openai_apikey=your_openai_api_key
assemblyai_apikey=your_assemblyai_api_key
```

## Usage
Run the Streamlit application with the following command:
```bash
streamlit run audio_ops.py
```

### Tabs and Functionalities
- **Text-to-Speech Synthesis**
   -Enter the text you want to convert to speech.
   -Select a voice type from the provided options.
   -Click the "Ses Sentezle" button to generate and play the speech.
  
- **Transcription with Whisper**
   -Upload an audio file in MP3 format.
   -Click the "Metne Dönüştür" button to transcribe the audio to text.
   
- **Translation with Whisper**
   -Upload an audio file in MP3 format.
   -Click the "Tercüme Et" button to translate the audio to text in another language.

- **Transcription with Conformer**
   -Upload an audio file in MP3 format.
   -Click the "Metne Dönüştür" button to transcribe the audio using the Conformer model.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
OpenAI for their powerful AI models.
AssemblyAI for their advanced transcription services.
Streamlit for providing an easy-to-use web application framework.
  

