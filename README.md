# HaikuAI

> Unleash creativity through AI-powered poetic interaction

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/username/haiku-ai)

## Overview

HaikuAI is an innovative voice-powered AI agent that generates meaningful haiku poems, offering a unique blend of artificial intelligence and creative expression. Designed for language enthusiasts and creative professionals, it transforms interactions into poetic moments.

## Features

- ✨ AI-powered haiku generation
- 🚀 Emotionally intelligent voice interaction
- 💡 Cultural and linguistic sensitivity
- 🔒 Secure user authentication
- 🌐 Multilingual support

## Tech Stack

**Frontend:**
- React 18 with TypeScript
- Tailwind CSS
- Zustand State Management
- Web Speech API

**Backend:**
- Node.js 20
- Next.js API Routes
- PostgreSQL with Prisma ORM
- tRPC for type-safe APIs

**Deployment:**
- Vercel
- Supabase

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/username/haiku-ai.git

# Install dependencies
cd haiku-ai
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Utility functions
│   ├── hooks/          # Custom React hooks
│   └── styles/         # Styling
├── public/             # Static assets
├── tests/              # Test files
└── docs/               # Documentation
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
OPENAI_API_KEY=your-openai-key
NEXTAUTH_SECRET=your-auth-secret
DATABASE_URL=your-postgres-connection-string
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage
```

## Deployment

### Vercel

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/poetic-enhancement`)
3. Commit your changes (`git commit -m 'Add emotional intelligence layer'`)
4. Push to the branch (`git push origin feature/poetic-enhancement`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for GPT language models
- Web Speech API contributors
- Creative writing community

## Support

For support, email support@haikuai.com or open a GitHub issue.

---

**Generated with ❤️ by Neuronix AI**