# AdmitAssist

An AI-powered platform to help students plan and manage their college applications.

## Project Structure

This is a monorepo containing three main packages:

- `frontend`: Next.js-based web application
- `backend`: Express.js API server
- `shared`: Common types and utilities shared between frontend and backend

## Prerequisites

- Node.js 18.x or later
- npm 9.x or later

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development servers:
   ```bash
   npm run dev
   ```
   This will start both the frontend (Next.js) and backend (Express) servers concurrently.

3. Frontend will be available at `http://localhost:3000`
4. Backend will be available at `http://localhost:4000`

## Development

- `npm run dev`: Start both frontend and backend in development mode
- `npm run dev:frontend`: Start only the frontend
- `npm run dev:backend`: Start only the backend
- `npm run build`: Build all packages
- `npm run lint`: Run ESLint on all packages
- `npm run format`: Format code using Prettier

## Project Structure

```
admit-assist/
├── frontend/          # Next.js frontend application
├── backend/           # Express.js backend server
├── shared/           # Shared types and utilities
├── package.json      # Root package.json for workspace management
└── tsconfig.base.json # Base TypeScript configuration
```

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Run tests and linting
4. Submit a pull request

## License

MIT 