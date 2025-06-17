# Voice Bot with ChatGPT

A voice-enabled chatbot that uses ChatGPT's API to provide personalized responses to questions. The bot can both listen to your questions and speak its responses.

## Features

- Voice input using Web Speech API
- Text-to-speech responses
- Real-time communication using Socket.IO
- Modern UI with Material-UI
- Powered by ChatGPT API

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- OpenAI API key

## Setup

1. Clone the repository
2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd client
   npm install
   ```

4. Create a `.env` file in the root directory and add your environment variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/voicebot
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Running the Application

1. Start the backend server:
   ```bash
   npm run dev
   ```

2. In a new terminal, start the frontend:
   ```bash
   cd client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Usage

1. Click the "Start Listening" button to activate voice input
2. Ask your question verbally or type it in the text field
3. Click "Send" to get the bot's response
4. The bot will respond both in text and voice

## Example Questions

- What should we know about your life story in a few sentences?
- What's your #1 superpower?
- What are the top 3 areas you'd like to grow in?
- What misconception do your coworkers have about you?
- How do you push your boundaries and limits?

## Technologies Used

- Frontend: React, Material-UI, Socket.IO Client
- Backend: Node.js, Express, Socket.IO
- Database: MongoDB
- AI: OpenAI GPT-4 API
- Voice: Web Speech API 