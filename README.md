# UIGen - AI-Powered UI Component Generator

UIGen is a web application that uses AI to generate React components from natural language descriptions. Simply describe the UI component you want, and the app will generate the code and show a live preview instantly.

## Features

- 🤖 AI-powered React component generation
- 👁️ Live preview of generated components
- 📝 Built-in code editor with file tree
- 🔐 User authentication (sign up / sign in)
- 💾 Project saving and history
- 🎨 Tailwind CSS styling

## Tech Stack

- **Frontend**: Next.js 15, React, TypeScript
- **Styling**: Tailwind CSS
- **Database**: SQLite with Prisma ORM
- **AI**: Anthropic Claude / Groq (llama-3.3-70b)
- **Auth**: JWT sessions

## Setup

1. Install dependencies:
\```
npm run setup
\```

2. (Optional) Add your API key in `.env`:
\```
ANTHROPIC_API_KEY=your_key_here
\```
or
\```
GROQ_API_KEY=your_key_here
\```

3. Start the app:
\```
set NODE_OPTIONS=--require ./node-compat.cjs && npx next dev --turbopack
\```

4. Open http://localhost:3000

## Usage

1. Create an account or sign in
2. Type a description like `create a login form` or `create a counter`
3. Watch the AI generate your component in real time
4. View the live preview and edit the code