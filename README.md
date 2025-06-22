# ALX Project 0x05 Setup - AI Image Generator

A Next.js-based web application that generates AI-powered images from text prompts using the GPT-4 Image Generation API.

## 🎯 Learning Objectives

- Implement React state management with `useState`
- Create and utilize custom React hooks
- Manage environment variables for API security
- Build API routes in Next.js
- Develop reusable React components
- Handle asynchronous operations
- Apply responsive design with Tailwind CSS
- Follow React best practices

## 🛠️ Requirements

- Node.js (v14+)
- Next.js (v13+)
- React (v18+)
- TypeScript
- Tailwind CSS
- GPT-4 API key (RapidAPI)
- Modern web browser

## 📁 Project Structure

```
alx-project-0x07/
├── components/
│   ├── common/
│   │   └── ImageCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── constants/
│   └── index.ts
├── hooks/
│   └── useFetchData.ts
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── generate-image.ts
│   ├── _app.tsx
│   └── index.tsx
├── public/
└── styles/
    └── globals.css
```

## ✨ Key Features

- **Image Generation**: Text-to-image conversion using AI
- **Image Gallery**: History and preview of generated images
- **Responsive UI**: Mobile and desktop compatibility
- **Custom Hooks**: Reusable data fetching logic
- **Type Safety**: Full TypeScript implementation

## 🏗️ Best Practices

- Component organization and separation
- Secure API key management
- Proper error handling and loading states
- Type-safe development with TypeScript
- Clean, responsive UI design

## 🚀 Development Progression

The project evolves through versions 0x07-0x13, progressively adding:
- Basic setup and layout
- State management
- Environment configuration
- API integration
- Image tracking
- Custom hooks implementation

## 🔧 Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Configure environment variables
4. Run development server: `npm run dev`

## 📝 Note

This project demonstrates modern React patterns, clean architecture, and production-ready practices for building AI-powered web applications.
