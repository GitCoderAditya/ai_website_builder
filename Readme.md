
# AI-Powered Web Development Assistant

This is an intelligent web development assistant that helps you create and modify web applications using natural language prompts. It combines the power of AI with a modern development environment to streamline the web development process.

## Features

- 🤖 AI-powered code generation and modification
- 🎨 Real-time preview of generated code
- 📝 Monaco code editor integration
- �� WebContainer-based live preview
- 🔄 Real-time file system updates
- 🎯 Support for both React and Node.js projects
- 🎨 Tailwind CSS for styling
- 🔍 File explorer with real-time updates

## Tech Stack

### Frontend
- React 18
- Vite
- Tailwind CSS
- Monaco Editor
- WebContainer API
- React Router DOM
- Axios

### Backend
- Node.js
- Express
- Google Gemini AI
- CORS

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Google Gemini API key
- Anthropic API key (optional)
- OpenAI API key (optional)

## Environment Variables

Create a `.env` file in the backend directory with the following variables:

```env
GEMINI_API_KEY=your_gemini_api_key
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai_website_builder.git
cd bolt
```

2. Install dependencies:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables:
```bash
# In the backend directory
cp .env.example .env
# Edit .env with your API keys
```

4. Start the development servers:
```bash
# Start backend server (from backend directory)
npm run dev

# Start frontend server (from frontend directory)
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`


## Usage

1. Navigate to the home page
2. Enter your project requirements in natural language
3. Select the project type (React or Node.js)
4. View the generated code in the editor
5. Make modifications as needed
6. Preview the changes in real-time

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [WebContainer API](https://webcontainers.io/) for browser-based development environment
- [Monaco Editor](https://microsoft.github.io/monaco-editor/) for code editing
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Google Gemini](https://ai.google.dev/) for AI capabilities
<｜tool▁call▁end｜><｜tool▁calls▁end｜>
