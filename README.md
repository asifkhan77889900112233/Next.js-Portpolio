# NextJS Pro - Stunning Web Application

A beautiful, modern Next.js project with professional folder structure, TypeScript, Tailwind CSS, and best practices.

## 🚀 Features

- **Next.js 15** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for beautiful UI
- **Turbopack** for fast development
- **ESLint** for code quality
- **Professional folder structure**
- **Reusable components**
- **Custom hooks**
- **Utility functions**

## 📁 Project Structure

```
src/
├── app/                 # App Router and pages
├── components/
│   ├── common/         # Reusable UI components
│   ├── layout/         # Layout components
│   └── hero/           # Feature-specific components
├── styles/             # Global styles
├── hooks/              # Custom React hooks
├── utils/              # Utility functions
├── services/           # API services
├── types/              # TypeScript type definitions
├── constants/          # Application constants
└── public/             # Static assets
```

## 🛠️ Getting Started

### Prerequisites
- Node.js 18+ 
- npm, yarn, pnpm, or bun

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📝 Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint
- `npm run type-check` - Check TypeScript types

## 🎨 Component Library

### Button Component
```tsx
import { Button } from '@/components/common/Button'

<Button variant="primary" size="lg">
  Click me
</Button>
```

### Card Component
```tsx
import { Card } from '@/components/common/Card'

<Card hover>
  Card content here
</Card>
```

## 🎯 Key Technologies

- **React 19** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS
- **Next.js 15** - React framework
- **Turbopack** - Fast bundler
- **ESLint** - Code linting

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and pull requests.

---

**Happy Coding! 🚀**
