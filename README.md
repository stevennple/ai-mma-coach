# StrikeMMA AI Coach

An intelligent MMA coaching assistant powered by artificial intelligence. Get personalized answers to your Mixed Martial Arts questions, training advice, and technical guidance - all through an intuitive chat interface.

## Features
- **AI-Powered Coaching:** Instant responses to MMA-related questions using Google's Generative AI
- **Natural Conversation:** User-friendly chat interface for seamless interaction
- **Comprehensive Knowledge:** Covers various aspects of Mixed Martial Arts:
    * Training techniques
    * Fighting strategies
    * Conditioning advice
    * Technical explanations
    * Equipment recommendations
- **Modern Web Interface:** Built with Next.js and styled with TailwindCSS
- **Responsive Design:** Works seamlessly on desktop and mobile devices
- **TypeScript Integration:** Type-safe codebase for reliability

## Getting Started
### Prerequisites
- Node.js (18.x or later recommended)
- npm or yarn package manager
- Google AI API key

### Installation
1. Clone the repository:
```bash
git clone https://github.com/stevennple/ai-mma-coach.git
cd ai-mma-coach
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a .env.local file in the root directory with:
```Code
GOOGLE_AI_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open http://localhost:3000 in your browser

## Tech Stack
### Frontend
- **Framework:** Next.js 14
- **Language:** TypeScript
- **UI Library:** React 18
- **Styling:** TailwindCSS
- **AI Integration:** Google Generative AI

### Development Tools
- ESLint for code linting
- PostCSS for CSS processing
- Autoprefixer for CSS compatibility

## Dependencies
```JSON
{
  "dependencies": {
    "@google/generative-ai": "^0.16.0",
    "next": "14.2.5",
    "react": "^18",
    "react-dom": "^18"
  },
  "devDependencies": {
    "typescript": "^5",
    "tailwindcss": "^3.4.10",
    "autoprefixer": "^10.4.20",
    "postcss": "^8.4.41"
  }
}
```

## Available Scripts
- npm run dev - Start development server
- npm run build - Build production bundle
- npm run start - Start production server
- npm run lint - Run ESLint

## Configuration
The project uses several configuration files:
- next.config.js - Next.js configuration
- tailwind.config.js - TailwindCSS configuration
- tsconfig.json - TypeScript configuration
- postcss.config.js - PostCSS configuration
