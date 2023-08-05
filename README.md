# 4100_applied_project
Business Application for AI - Developing Course Exercises

Voice-Enabled Chatbot with PyQt5 and OpenAI

-This project integrates the OpenAI GPT model with a PyQt5 GUI application to build a chatbot capable of understanding both text and voice input.

Features:


-GUI Application: Utilizes the powerful PyQt5 library to create a user-friendly interface.  


-Text Chat: Users can type their questions and get responses instantly.


-Voice Recognition: With the integration of the speech_recognition library, users can also speak their queries.


-Integration with OpenAI GPT: Harnesses the capabilities of OpenAI's GPT model to generate human-like responses to user queries.


Setup:


Prerequisites: Ensure you have PyQt5, speech_recognition, and openai libraries installed.

How it Works:


-GUI Creation: The application starts by initializing a QMainWindow which contains various widgets like buttons, labels, and text input fields.


-Event Handling: Button click events are connected to specific functions that process user input or start voice recognition.


-Voice Recognition: The recognize_speech function captures audio from the microphone and converts it into text using Google's speech recognition service.


-Generating Responses: The generate_chat_response function sends the user's query to the OpenAI API and fetches a response, which is then displayed on the GUI.


Future Enhancements:


-Multi-language support.


-Improved error handling for voice recognition.


-GUI beautification using Qt Designer or other styling methods.


-Integration of advanced NLP techniques for better understanding and processing of user queries.


<img width="1279" alt="0160686b6b1e31f59a49f767746c3e9" src="https://github.com/ZhengFeie/4100_applied_project/assets/106442747/19bb9712-b9ae-4402-8062-122497bf15c1">
