# Chess Game - 2 Player & AI
A fully functional chess game with two-player mode and AI opponent capabilities using LLM APIs (OpenAI GPT-4, Google Gemini, or Anthropic Claude).

![image](https://github.com/user-attachments/assets/9e0eb18c-3f6f-4e43-8e67-47c60e1c4c8a)


# Project Overview
This chess application was developed as part of the BharatX Tech Intern 1st Task. Unlike conventional chess applications that use deterministic engines like Stockfish, this project explores how generative language models can interpret board positions and suggest moves based on contextual understanding.

# Features 
- Two-player mode allowing humans to play against each other
- AI opponent mode supported by LLMs
- Functional chessboard UI with legal move validation
- Move history tracking
- Choose to play as white or black against AI
- Game state indication: Shows check, checkmate, draws


# Instructions to play with AI :
To play against AI
1. Click the "Play vs AI" button
2. Select your preferred AI model
3. Enter your API key for one of the supported LLMs:
   - Google Gemini
   - OpenAI GPT-4
   - Anthropic Claude
4. Choose whether to play as white or black
5. Start playing!

# Live Demo
Open the `index.html` file directly in your browser.

https://github.com/user-attachments/assets/eb98f67c-55a5-495a-bc2a-8b666ce5b769



# API Keys
You will need to enter your own API keys for the AI services:

**Google Gemini**    : Get API key from [Google AI Studio](https://makersuite.google.com/)

**OpenAI GPT-4**     : Get API key from [OpenAI](https://platform.openai.com/)

**Anthropic Claude** : Get API key from [Anthropic](https://console.anthropic.com/)

# Technical Details
 - Frontend      : HTML, CSS, JavaScript
 - AI Integration: RESTful API calls to various LLM providers
 - Imported chess.js library for move validation and game state



