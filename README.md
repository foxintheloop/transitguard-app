# TransitGuard Mobile App

**Real-time safety alerts for Chicago transit riders.**

Mobile application providing push notifications and SMS alerts when safety incidents are predicted or reported near CTA stations and routes.

## Features

- **Location-based alerts** - Get notified about incidents near your current station
- **Predictive warnings** - Receive alerts for high-risk time windows before you travel
- **GenAI chatbot** - Ask natural language questions about safety by location and time
- **Route planning** - See safety scores for your planned commute

## Part of TransitGuard

This mobile app is one component of the TransitGuard platform. See also:

- [TransitGuard Dashboard](https://github.com/foxintheloop/transitguard-dashboard) - Web analytics for CTA operations
- [TransitGuardRAG](https://github.com/foxintheloop/TransitGuardRAG) - GenAI RAG API chatbot backend
- [TransitGuard (main)](https://github.com/foxintheloop/transitguard) - Project overview and documentation

## Getting Started

### Prerequisites

- Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

### Installation

Follow these steps to get started:

```sh
# Step 1: Clone the repository
git clone https://github.com/foxintheloop/transitguard-app.git

# Step 2: Navigate to the project directory
cd transitguard-app

# Step 3: Install the necessary dependencies
npm i

# Step 4: Start the development server with auto-reloading
npm run dev
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run build:dev` - Build for development
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## Stack

`React Native` `TypeScript` `Node.js`

## Deployment

The application can be deployed to any static hosting service that supports Node.js applications, such as:
- Vercel
- Netlify
- GitHub Pages
- AWS Amplify

## Team

Northwestern University MSDS 498 Capstone (2025)

## License

MIT




