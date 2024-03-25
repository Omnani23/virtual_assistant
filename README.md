# Jarvis - Personal Assistant
Jarvis is a Python-based personal assistant designed to assist users with various tasks through voice commands. It utilizes several APIs and libraries to perform tasks like fetching news, sending emails, playing YouTube videos, and more.
## Installation
### To use Jarvis, ensure you have Python installed on your system. Additionally, install the required packages using pip:
      pip install -r requirements.txt
## Usage
### Run the script jarvis.py:
      python jarvis.py
Jarvis will greet you and await your commands.
## Features
## Voice Interaction
Jarvis interacts with the user through voice commands. It uses the speech_recognition library to recognize and process user commands.
### Core Functionalities
- **Greet User:** Jarvis greets the user based on the time of day (Morning, Afternoon, Evening).
- **Open Applications:** You can ask Jarvis to open applications like Notepad, Command Prompt, Camera, and Calculator.
- **Retrieve IP Address:** Jarvis can fetch and announce the user's IP address.
- **Wikipedia Search:** Allows users to search for information on Wikipedia.
- **YouTube Integration:** Plays YouTube videos based on user requests.
- **Google Search:** Performs searches on Google.
- **Send WhatsApp Message:** Enables users to send WhatsApp messages to specified contacts.
- **Send Email:** Sends emails to specified recipients.
- **Fetch Jokes and Advice:** Provides users with random jokes and advice.
- **Fetch Latest News:** Retrieves and reads out the latest news headlines.
- **Exit :** To exit the application, simply say "I'm done" or similar phrases, and Jarvis will stop executing.

## Configuration
Jarvis can be configured using environment variables:
- **USER:** Your name (e.g., "Om Prakash").
- **BOTNAME:** The name of the assistant (e.g., "Jarvis").
- **NEWS_API_KEY:** Your News API key for fetching news headlines.
- **EMAIL:** Your email address for sending emails.
- **PASSWORD:** Your email password (ensure to use app-specific passwords for security).
