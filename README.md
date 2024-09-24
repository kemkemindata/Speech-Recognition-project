## OVERVIEW
This project is a Speech Recognition App built using Streamlit for a web-based interface. 
It uses Python's SpeechRecognition library to transcribe speech to text, allowing users to interact with the app via their microphone. 
The app is designed to recognize speech, transcribe it, and display the transcribed text.

##FEATURES
-Transcribes speech to text using Google Web Speech API
-Simple web interface using Streamlit
-Progress spinner to show transcription progress
-Displays transcription results and history in the sidebar

## 🛠️ INSTALLATION
To run this project locally, follow these steps:

**Clone the repository:**
**code**
git clone https://github.com/your-username/streamlit-speech-recognition.git
cd streamlit-speech-recognition

**Set up a virtual environment:**
**code**
python -m venv venv
source venv/bin/activate    # For Linux/MacOS
venv\Scripts\activate       # For Windows

**Install the required dependencies:**
**The file containing all the dependencies is availabe as 'reqirements.txt'**
pip install -r requirements.txt

**Ensure you have all required libraries installed:**


## RUN

**To run the app, use the following command:**
**code**
streamlit run app.py


## Main Features:

-Start Recording: Click the button to begin voice recording.

-Transcription: Once you stop speaking, the app will transcribe your words into text.

-History: Your transcriptions are saved and displayed in the sidebar.


## 🧰 Technologies Used
**-Python:** The programming language used to build the app.

**-Streamlit:** The web interface framework used to create an interactive web app.

**-SpeechRecognition:** Python library for converting speech into text.

**-Pyttsx3:**  Optional library for text-to-speech conversion.

**-Pandas:**  Data handling for storing transcription history.




