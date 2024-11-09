# Minute Mate

**Minute Mate** is an AI-powered meeting assistant that transcribes meetings, generates concise summaries, and extracts actionable items. The project supports multi-language functionality using a translation API, ensuring that meeting summaries and action items can be provided in the user's preferred language.

## Features

- **Meeting Transcription**: Process meeting transcripts and generate structured summaries.
- **Actionable Items Extraction**: Automatically extract key action items from the meeting discussion.
- **Multi-Language Support**: Translate summaries and action items into different languages using an external translation API.
- **Real-Time Collaboration**: Participants can join virtual rooms for real-time meeting discussions and summaries.
- **Document Export**: Save meeting summaries and action items in `.docx` format.

## Technologies Used

- **Flask**: Backend framework for creating API routes.
- **OnDemand API**: Used for language transalation and speech recognition Using LLAMA for generating real time transcription during the meet .
- **Socket.IO**: Real-time communication between the users in the virtual rooms.
- **LangChain**: For handling Large Language Models (LLMs) to summarize and extract key points from transcripts.
- **DeepInfra**: Language model for generating summaries and action items.
- **docx**: Python library for saving the generated summaries in a Word document.
- **Translation API**: External API for translating meeting summaries and action items into multiple languages.
- **UUID**: For creating unique room IDs and document names.

## Getting Started
 - Create a virtual environment and activate it
     `python -m venv venv`
     `source venv/bin/activate`   # On Windows: venv\Scripts\activate
- Install the required dependencies:
     `pip install -r requirements.txt`
- Run the Flask app :
     `python app.py`

  Open a web browser and navigate to http://localhost:5001. You should see the homepage where you can create or join a room.
  
### Prerequisites

1. Python 3.x
2. Flask(for backend)
3. An external translation API (Use LLama from onDemand or from Deepinfra)

### Installation

1. Clone the repository:
   ```bash
   `git clone https://github.com/riteshXcodes/minute-mate.git`
   cd minute-mate
