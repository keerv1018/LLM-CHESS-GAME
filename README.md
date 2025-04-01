# LLM-CHESS-GAME

# Chess Game - 2 Player & AI
A fully functional chess game with two-player mode and AI opponent capabilities using LLM APIs (OpenAI GPT-4, Google Gemini, or Anthropic Claude).

# Project Overview
This chess application was developed as part of the BharatX Tech Intern 1st Task. Unlike conventional chess applications that use deterministic engines like Stockfish, this project explores how generative language models can interpret board positions and suggest moves based on contextual understanding.

# Features 
- Two-player mode allowing humans to play against each other
- AI opponent mode powered by LLM APIs
- Functional chessboard UI with legal move validation
- Move history tracking
- Choose to play as white or black against AI
- Game state indication: Shows check, checkmate, draws


# Playing Against AI :
To play against AI
1. Click the "Play vs AI" button
2. Select your preferred AI model
3. Enter your API key for one of the supported LLMs:
   - Google Gemini
   - OpenAI GPT-4
   - Anthropic Claude
4. Choose whether to play as white or black
5. Start playing!

## Live Demo
The simplest way to use this is to open the `index.html` file directly in your browser.

## API Keys
You will need to enter your own API keys for the AI services:

**Google Gemini**    : Get API key from [Google AI Studio](https://makersuite.google.com/)

**OpenAI GPT-4**     : Get API key from [OpenAI](https://platform.openai.com/)

**Anthropic Claude** : Get API key from [Anthropic](https://console.anthropic.com/)

# Technical Details
 - Frontend      : HTML, CSS, JavaScript
 - Chess Engine  : chess.js library for move validation and game state
 - AI Integration: RESTful API calls to various LLM providers

## Development
This is a pure client-side application with no build requirements. Just open the `index.html` file to run locally.


