# Chatbot

## Description
The Chatbot project is a simple interactive chatbot that takes user input, displays it in the chat interface, and responds dynamically. This project reinforces JavaScript event handling and DOM manipulation concepts.

## Features
- Users can enter messages and send them to the chatbot.
- Messages appear dynamically in the chat container.
- The chatbot replies to each message.
- User input is cleared after sending a message.

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)

## Setup Instructions
### Prerequisites
Ensure you have a modern web browser installed.

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/Mubeena2003/chatbot.git
   ```
2. Navigate to the project directory:
   ```sh
   cd chatbot
   ```
3. Open `index.html` in a browser to run the chatbot.

## File Structure
```
chatbot/
│── index.html
│── styles.css
│── script.js
```

## Implementation Details
### HTML Elements
- The chat container element should have:
  ```html
  <div class="chat-container" id="chatContainer"></div>
  ```
- The user input field should have:
  ```html
  <input type="text" class="user-input" id="userInput">
  ```
- The send button should have:
  ```html
  <button id="sendMsgBtn">Send</button>
  ```

### Functionality
1. When the **Send** button is clicked:
   - The user message appears in the chat container.
   - The input field is cleared.
   - The chatbot responds with a predefined reply.

2. Messages use predefined class names for styling:
   - `.msg-to-chatbot-container`
   - `.msg-to-chatbot`
   - `.msg-from-chatbot-container`
   - `.msg-from-chatbot`

## Screenshots
*Include relevant screenshots of the chatbot interface.*
![Image](https://github.com/user-attachments/assets/41175176-ca93-49df-8c71-7e4f3cff7a95)







