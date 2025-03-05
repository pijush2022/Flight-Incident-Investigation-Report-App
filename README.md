# Flight Incident Investigation Report App

## Overview
The **Flight Incident Investigation Report App** is a Streamlit-based application designed to analyze and generate detailed reports from audio transcriptions of flight incidents. This app utilizes OpenAI's Whisper model for transcription and LangChain's AI models to generate structured incident reports.

## Features
- **MP3 File Upload**: Users can upload MP3 files for transcription.
- **AI-Powered Transcription**: Utilizes OpenAI's Whisper model for high-quality speech-to-text conversion.
- **Automated Incident Report Generation**: Employs AI agents to analyze and structure the transcribed conversation.
- **Downloadable Reports**: Generates a structured incident report that can be downloaded as a Word document.

## Technologies Used
- **Python**
- **Streamlit** (for UI)
- **OpenAI Whisper API** (for transcription)
- **LangChain + CrewAI** (for processing and structuring the data)
- **Pydub** (for audio processing)
- **Python-dotenv** (for environment variable management)

## Installation
### Prerequisites
Ensure you have **Python 3.10 or higher** installed.

### Clone the Repository
```sh
git clone https://github.com/your-username/flight-incident-report-app.git
cd flight-incident-report-app
```

### Create a Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate    # On Windows
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Setup
1. Create a `.env` file in the root directory and add the required API keys:
```ini
GROQ_API_KEY="your-groq-api-key"
OPENAI_API_KEY="your-openai-api-key"
```

## Running the Application
```sh
streamlit run main.py
```

## Usage
1. Upload an MP3 file containing flight communication or incident audio.
2. Click the **Analyze** button to transcribe the audio.
3. AI agents process the transcription to generate a structured incident report.
4. Download the generated report as a Word document.

## Folder Structure
```
flight-incident-report-app/
│-- main.py
│-- transcript.py
│-- .env
│-- requirements.txt
```

## License
This project is licensed under the MIT License.

## Contributors
- **Your Name** - [GitHub Profile](https://github.com/pijush2022)

## Contact
For any inquiries, open an issue or reach out at [your-email@example.com](mailto:your-pijushpl2023@gmail.com).
