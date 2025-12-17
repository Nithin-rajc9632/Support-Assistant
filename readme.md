# Overview
NITHIN is a virtual HR support assistant built entirely with HTML, CSS, and JavaScript. It runs offline in the browser and provides instant support for HR-related queries such as leave policy, working hours, benefits, and more. The assistant also supports file uploads for basic resume analysis, sentiment detection, task management, and multilingual responses (English and Hindi). The interface is responsive and includes features like emoji picker, voice input, and theme toggle for enhanced user experience.

# Features & Limitations

## Features
- FAQs & Fuzzy Search: Instant answers to common HR questions with fuzzy matching for better query resolution.
- Multilingual Support: Switch between English and Hindi with dynamic language change.
- File Upload & Analysis: Upload .txt or .json files for offline keyword analysis (e.g., resume scanning).
- Task Management: Add, remove, and view tasks within the chat.
- Sentiment Analysis: Detects user sentiment based on text and emoji input.
- Voice Input: Uses browser speech recognition for hands-free input.
- Text-to-Speech: Replies are spoken aloud using browser synthesis.
- Analytics & Metrics: Tracks questions, escalations, and sentiment for user feedback.
- Export & Print: Chat history can be exported as TXT or printed as PDF.
- Emoji Picker: Quick emoji insertion for expressive chat.

## Limitations
- Offline Only: No integration with live APIs or external databases; all logic and data are client-side.
- Basic NLP: Responses rely on keyword matching and simple logic, not advanced AI models.
- Limited File Support: Only analyzes plain text and JSON files.
- Browser Compatibility: Speech recognition and synthesis require modern browsers.

# Tech Stack & APIs Used
- Frontend: HTML, CSS, JavaScript
- Styling: CSS (custom and responsive design)
- Offline Storage: localStorage for persisting chat, tasks, and analytics
- Browser APIs:
  - SpeechRecognition API (for voice input)
  - SpeechSynthesis API (for text-to-speech)
  - FileReader API (for file uploads)
- No External Libraries: All functionality is implemented with vanilla JavaScript.

# Setup & Run Instructions
- Save the provided HTML code as nithin-assistant.html.
- Open the file in any modern web browser (Chrome, Firefox, Edge, etc.).
- The assistant will load with a welcome message and is ready to use.
- To use voice input, ensure your browser supports SpeechRecognition and grant microphone permission when prompted.
- For multilingual support, type "switch to hindi" or "switch to english" in the chat.
- To upload a file, use the paperclip icon and select a .txt or .json file.
- All data is stored locally and will persist between sessions.

# Potential Improvements
- Integration with Live APIs: Connect to backend services for real-time data and advanced NLP.
- Enhanced NLP: Use libraries like TensorFlow.js or integrate with external AI APIs for smarter responses.
- User Authentication: Add login and session management for personalized support.
- Richer File Analysis: Support for PDF and DOCX files using client-side libraries.
- Dark Mode Toggle: Allow user preference for light/dark theme persistence.
- Accessibility: Improve screen reader and keyboard navigation support.
- Multi-User Chat: Enable support for group chats or team-based HR queries.
