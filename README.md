# AudioTranscriptAnalyzer

**AudioTranscriptAnalyzer** is a powerful tool designed for speaker diarization, transcription, and the extraction of specific patterns from audio transcriptions. Leveraging advanced machine learning models, this project processes audio files, identifies different speakers, and analyzes the content for specific phrases.
> THIS IS THE FIRST MOST SIMPLE MODEL WHICH DIRECTLY EXTRACTS THE PHRASE FROM AUDIO AND SEND IT IN MACHINE LEARNING MODEL TO BE ANALYSED ON PARTICULAR PARAMETERS
> FEW PARAMETERS TO BE ADDED AND NEED TO USE ADVANCE MACHINE LEARNING MODELS PRESENTLY IT USES SIMPLE REGEX AND NLP TO ANALYSE
> THIS IS USEFULL TO COMPANIES WHICH PROVIDE SERVICES TO OTHER BIG COMPANIES
> ALDO MAKE SURE TO HAVE SMALL AUDIO FILES OR LAPTOP WITH GOOD RAM

## Features

- **Speaker Diarization**: Identify and segment different speakers in an audio file.
- **Transcription**: Convert audio segments into text using pre-trained Wav2Vec2 models.
- **Pattern Detection**: Analyze transcriptions for specific phrases related to learning.
- **Excel Output**: Save the results, including transcripts, speaker labels, and pattern detections, to an Excel file.

## Installation

To get started, clone the repository and install the required dependencies.

### Clone the Repository

```bash
git clone https://github.com/Srish0218/AudioTranscriptAnalyzer.git
cd AudioTranscriptAnalyzer
```

### Install Dependencies

```bash
pip install pyannote.audio openpyxl transformers librosa spacy torch
python -m spacy download en_core_web_sm
```

## Usage

1. **Prepare your audio file**: Place your audio file in the project directory and update the `file_name1` variable in the script with the path to your audio file.

2. **Run the script**:

   ```bash
   python audio_transcript_analyzer.py
   ```

3. **View results**: The results will be saved in an Excel file named `diarization_transcripts_with_parameters_new.xlsx`.

## Contributing

We welcome contributions! Please feel free to submit issues or pull requests to improve the project or add new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Hugging Face](https://huggingface.co/) for the Wav2Vec2 models.
- [Pyannote](https://github.com/pyannote/pyannote-audio) for the speaker diarization pipeline.
- [SpaCy](https://spacy.io/) for the natural language processing toolkit.
