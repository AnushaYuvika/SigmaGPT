SigmaGPT 🤖

SigmaGPT is a full-stack AI chat application built with React.js, Node.js, Express.js, MongoDB, and the Groq API. It allows users to interact with an AI assistant, create conversations, and access their previous chat history.

🚀 Live Demo

Frontend: https://sigma-gpt-murex-five.vercel.app/

Backend: https://sigmagpt-backend-nd0p.onrender.com

✨ Features
AI-powered conversations using the Groq API
Create new chat conversations
Persistent chat history using MongoDB
Retrieve and display previous conversations
Thread-based conversation management
React Context API for managing chat state
Markdown rendering for AI responses
GitHub Flavored Markdown (GFM) support
Markdown tables and lists
Syntax highlighting for code blocks
Responsive chat interface
🛠️ Tech Stack
Frontend
React.js
Vite
React Context API
React Markdown
Remark GFM
Rehype Highlight
Highlight.js
CSS
Backend
Node.js
Express.js
MongoDB
Mongoose
Groq API
REST APIs
Deployment
Vercel — Frontend
Render — Backend
🔄 How It Works
User enters a prompt
        ↓
React Frontend
        ↓
Express.js REST API
        ↓
Groq API
        ↓
AI-generated response
        ↓
MongoDB
        ↓
Conversation history
💬 Chat Functionality

The user enters a prompt through the React interface. The frontend sends the request to the Node.js/Express backend.

The backend processes the request through the Groq API and returns the AI-generated response to the frontend.

Conversation messages are stored in MongoDB using conversation/thread IDs, allowing previous chats to be retrieved and displayed.

📝 Markdown & Code Rendering

AI responses are rendered using react-markdown.

The application uses remark-gfm to support GitHub Flavored Markdown features such as:

Tables
Ordered and unordered lists
Task lists
Strikethrough text
Other common GFM formatting

Code blocks are processed using rehype-highlight and Highlight.js to provide syntax highlighting.

🧵 Conversation Management

SigmaGPT uses thread-based conversation management.

Users can:

Start a new conversation
Continue an existing conversation
Store messages in MongoDB
Retrieve previous conversations
View previous chat history
👩‍💻 Author

Anusha Yuvika
