# STC ChatBot - Learning Assistant

## Overview
This is a web-based learning assistant chatbot designed to provide various functionalities for students. It allows users to interact with a chatbot for queries, view study materials, access e-learning resources, track progress, and explore a digital library. It also includes a voice assistant feature for hands-free interaction.

## Features
- **Login Page**: Secure login for accessing the main features.
- **Main Menu**: Navigate to various sections such as:
  - **ChatBot Queries**: Ask questions to integrated chatbots (ChatGPT, DeepSeek, etc.)
  - **Study Materials**: Download or refer to study materials.
  - **E-Learning**: Access online learning resources like YouTube, Coursera, edX, etc.
  - **Track Progress**: Monitor your progress in learning.
  - **Voice Assistant**: Use speech-to-text for interaction.
  - **Curriculum Completion**: Track syllabus coverage.
  - **Digital Library**: Access open access books and resources.
- **Voice Assistant**: Hands-free interaction using speech recognition.
- **Responsive Design**: Optimized for mobile and desktop view.

## Technologies Used
- **HTML5**: Structure of the web pages.
- **CSS3**: Styling for layout and design.
- **JavaScript**: Interaction logic, including login, voice recognition, and page navigation.

## Installation
To run this project locally:

1. Clone this repository.
2. Open the `index.html` file in any modern web browser.
3. Start interacting with the Learning Assistant chatbot.

## Usage

### Login
1. Enter your username and password to access the main features.
2. The default credentials are:
   - **Username**: `kaviya`
   - **Password**: `deva`

### Main Menu
Once logged in, the user can access the following options:
- **ChatBot Queries**: Opens a page with various chatbot services like ChatGPT, OpenAI, and DeepSeek.
- **Study Materials**: Provides options to download PDFs or refer to materials on Google Classroom.
- **E-Learning**: Links to popular e-learning platforms such as YouTube, Coursera, edX, etc.
- **Track Progress**: A section to monitor your learning progress (not fully implemented in the code).
- **Voice Assistant**: A voice-enabled assistant that can recognize and respond to speech commands.

### Voice Assistant
Click on the "🎤 Speak" button to start voice recognition. The recognized speech will appear on the screen, and the user can send it to the chatbot for a response.

### Digital Library
Provides links to external digital libraries such as Google Books, Hathi Trust, and the National Repository of Open Resources.

## Development Notes

### Components
1. **Login Page**: Users must enter the correct credentials (`username: kaviya`, `password: deva`) to access the app.
2. **Main Menu**: Once logged in, users can navigate between sections like queries, study materials, e-learning, and more.
3. **Voice Assistant**: Uses the Web Speech API for speech-to-text functionality. Compatible with modern browsers that support this API.
4. **Redirection**: External links (e.g., YouTube, Google Scholar, Udemy) open in new tabs when clicked.

### Known Issues
- The **Track Progress** feature is not yet implemented in the code.
- Voice recognition works only on browsers that support the Web Speech API (e.g., Google Chrome).

## License
This project is open-source. Feel free to modify and enhance it as per your requirements.

## Contact
For issues or suggestions, open an issue in this repository or contact the project maintainer.

