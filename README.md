# SAIVO - AI Chatbot Application
https://saivo.netlify.app/

SAIVO is a modern, full-stack AI chatbot application built with FastAPI (Python) backend and vanilla JavaScript frontend. It features real-time streaming responses, chat management, user authentication, and a clean dark-themed UI.

## 🚀 Features

### Core Features
- **AI-Powered Chat**: Real-time streaming responses using Groq AI (LLaMA 3.3 70B model)
- **Chat Management**: Create, rename, and delete chat conversations
- **Auto-Generated Titles**: Smart title generation for new chats based on conversation context
- **Message History**: Persistent storage of all conversations in MongoDB

### User Authentication
- **Secure Login/Signup**: Password hashing with bcrypt
- **Session Management**: Persistent login sessions with localStorage
- **Password Reset**: Email-based password reset functionality

### Account Management
- **Account Deletion**: 30-day grace period soft-delete system
- **Deletion Rate Limiting**: Users can only request deletion once per week
- **Cancellation Option**: Cancel scheduled deletion by logging in

### Help & Support
- **Help Request System**: Submit issues/problems directly from the app
- **Submission History**: View history of submitted help requests
- **Status Tracking**: Track if issues are being worked on or fixed

### UI/UX
- **Dark Theme**: Modern dark-themed interface
- **Responsive Design**: Works on desktop and mobile devices
- **Smooth Animations**: CSS transitions and animations throughout
- **Tab-Based Navigation**: Clean tabbed interface for modals

## 🛠️ Tech Stack

### Backend
- **FastAPI**: Modern Python web framework
- **Motor**: Async MongoDB driver
- **Pydantic**: Data validation using Python type hints
- **Passlib**: Password hashing (bcrypt)
- **HTTPX**: Async HTTP client for AI API calls
- **Uvicorn**: ASGI server

### Frontend
- **HTML5/CSS3**: Semantic markup with modern CSS
- **Vanilla JavaScript**: No framework dependencies
- **Fetch API**: For API communication
- **CSS Variables**: Theming and consistent styling

### Database
- **MongoDB**: NoSQL document database
- **Collections**: users, chats, messages, help_requests

### AI Integration
- **Groq API**: Fast AI inference
- **LLaMA 3.3 70B**: Large language model for chat responses
- **LLaMA 3.1 8B**: Smaller model for title generation

## 🤖 AI Assistance Disclosure

This project was developed with the assistance of AI tools for coding implementation. However:

- **All logic and architecture decisions are original** - The overall system design, feature decisions, and problem-solving approaches are mine
- **AI was used for coding acceleration** - Writing boilerplate, implementing features based on my specifications
- **Debugging was done together** - Learning from errors, understanding what's happening in the code
- **Code review and understanding** - All AI-generated code was reviewed, understood, and modified as needed

The AI served as a coding assistant, similar to having a knowledgeable pair programmer, while the creative direction and logical decisions remained mine.

## 📄 License

This project is for personal/educational use.

## 👤 Author

Built with ❤️ and AI assistance
