# Fluency Assessment Tool

A lightweight, browser-based multilingual pronunciation assessment tool built using HTML, CSS, and JavaScript. It helps users practice reading predefined paragraphs in multiple Indian languages and get feedback on pronunciation accuracy using speech-to-text comparison.

## Features
-> Real-time Speech Recognition using the Web Speech API

-> Multilingual Support: English, Hindi, Telugu, and Malayalam

-> Pronunciation Scoring using similarity metrics

-> No Backend Required – runs entirely in the browser

## Tech Stack

-> Frontend: HTML and CSS

-> JavaScript APIs: Web Speech API 

-> Icons: Font Awesome

## How It Works

-> A predefined paragraph is shown to the user based on the selected language.

-> The user reads the paragraph aloud by clicking the red microphone button.

-> The Web Speech API captures the voice input and transcribes it to text.

-> The tool calculates the similarity between the spoken and original paragraphs using edit distance.

-> Based on the similarity score, it provides a feedback message.


