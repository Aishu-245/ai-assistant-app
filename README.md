AI Assistant Platform
A full-stack application integrating multiple AI models to provide intelligent assistance through chat, code generation, and image creation.

Unsupported image

Features
AI Chat Interface: Engage in natural conversations with advanced AI models
Code Generation: Get programming assistance and code snippets for various languages
Image Generation: Create images from text descriptions using DALL-E
Dashboard: View analytics, conversation history, and settings at a glance
Model Settings: Customize AI parameters including temperature and max tokens
Conversation History: Review and continue previous AI interactions
Technologies Used
Frontend
React.js with TypeScript
TailwindCSS for styling
shadcn/ui component library
React Query for data fetching
Wouter for routing
Backend
Node.js with Express
RESTful API architecture
OpenAI API integration
In-memory data storage
Getting Started
Prerequisites
Node.js (v16 or higher, v20 recommended)
npm or yarn package manager
OpenAI API key
Installation
Clone the repository

git clone https://github.com/yourusername/ai-assistant-platform.git
cd ai-assistant-platform
Install dependencies

npm install
Create a .env file in the root directory with your OpenAI API key

OPENAI_API_KEY=your_openai_api_key_here
Start the development server

npm run dev
Open your browser and navigate to http://localhost:5000

Project Structure
├── client/                # Frontend code
│   ├── src/
│   │   ├── components/    # UI components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── lib/           # Utility functions and API clients
│   │   ├── pages/         # Page components
│   │   └── App.tsx        # Main application component
│
├── server/                # Backend code
│   ├── index.ts           # Server entry point
│   ├── routes.ts          # API route definitions
│   ├── storage.ts         # Data storage implementation
│   └── openai.ts          # OpenAI API integration
│
└── shared/                # Shared code between frontend and backend
    └── schema.ts          # Data models and validation schemas
Supported AI Models
OpenAI GPT-4
OpenAI DALL-E
Deepseek Coder (integration ready)
Llama 2 (integration ready)
Future Enhancements
User authentication and multiple user support
Database persistence with PostgreSQL
Voice input/output capabilities
Mobile application version
Additional AI model integrations
Customizable UI themes
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
OpenAI for their powerful API
shadcn/ui for the component library
All open-source libraries used in this project
Note: This project is for educational and demonstration purposes.
