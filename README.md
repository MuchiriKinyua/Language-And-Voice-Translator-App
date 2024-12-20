# Language And Voice Translator App  </br>

![Language translator](https://github.com/user-attachments/assets/f81b172c-25b5-4ade-a5ac-379af5bd28a4)

This project is a web-based Language Translator and Voice Recognition application. It allows users to translate text between various languages and includes voice recognition and playback functionalities.

# Features

Translate text between multiple languages.

Text-to-speech (voice output) for input and translated text.

Copy text to clipboard for both input and output areas.

Select source and target languages from dropdowns.

Swap source and target languages with a single click.

# Technologies Used

HTML5: For the structure of the application.

CSS3: For styling the application.

JavaScript: For dynamic functionality and interaction.

Font Awesome: For icons.

API: MyMemory Translated.net for fetching translations.

# Project Structure

project-folder </br>
├── index.html          # Main HTML file </br>
├── style.css           # Stylesheet </br>
├── script.js           # Main JavaScript file </br>
├── countries.js        # List of supported languages </br>
└── README.md           # Project documentation </br>

# Setup and Usage </br>

# Prerequisites </br>
 
A modern web browser. </br>

An active internet connection to fetch translations from the API. </br>

# Steps to Run </br>

Download or Clone the repository: git clone https://github.com/MuchiriKinyua/Language-And-Voice-Translator-App.git </br>

Open the index.html file in any web browser. </br>

Interact with the app by entering text, selecting languages, and clicking on the translate button. </br>

# How It Works </br>

Language Selection: Users select source and target languages from dropdowns populated using the countries.js file. </br>

Translation: Text entered in the source area is translated using the MyMemory API, and the result is displayed in the output area. </br>

Voice Recognition: The app uses the Web Speech API for text-to-speech functionality, supporting both source and translated text. </br>

Clipboard Functionality: Users can copy text from the input or output areas using the copy icon. </br>

Language Swap: The source and target languages can be swapped seamlessly using the swap icon. </br>

# Files </br>

## index.html </br>

The main structure of the application, defining the layout and placeholders for user interaction. </br>

## style.css </br>

Styles the application, ensuring a user-friendly interface with responsive design. </br>

## script.js </br>

Handles the functionality, including: </br>

Language selection population. </br>

Translation API calls. </br>

Voice recognition and playback. </br>

Clipboard copy and language swap. </br>

## countries.js </br>

Provides a comprehensive list of supported languages with their corresponding codes. </br>

# APIs Used </br>

MyMemory Translated.net </br>

Endpoint: https://api.mymemory.translated.net/get </br>

# Parameters: </br>

q: Text to translate. </br>

langpair: Source and target language pair (e.g., en-GB|ru-RU). </br>

Usage: Fetches translations for the input text. </br>

# Future Enhancements </br>

Add offline translation support. </br>

Improve UI for mobile devices. </br>

Integrate more robust APIs for enhanced translations. </br>

Add support for multiple simultaneous translations.
