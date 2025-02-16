# Speech-to-Text
A simple Python application using speech_recognition and tkinter to convert speech into text and display it in a graphical user interface (GUI). This program listens to the user's voice through a microphone and outputs the recognized speech as text in a separate window.

Speech-to-Text with GUI
This project utilizes the python speech_recognition library to capture speech from the microphone and convert it into text. The recognized text is displayed in a user-friendly graphical interface created using tkinter.
Features:
Speech Recognition: Uses Google’s Speech API to convert speech to text.
Graphical User Interface: Displays the recognized speech in a window with large font for easy readability.
Microphone Selection: Choose the correct microphone from a list of available devices.
Requirements:
Python 3.x
speech_recognition library
tkinter
How to Run:
Install the required libraries: pip install SpeechRecognition
Run the script, and the program will start listening to your speech.
Troubleshooting:
Ensure that your microphone is connected and properly configured.
If you encounter issues with the microphone, try updating the DEVICE_INDEX based on the list of available devices printed when the program starts.
