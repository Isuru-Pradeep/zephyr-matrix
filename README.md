# Zephyr Matrix

A modern enterprise website built with Next.js, TypeScript, and Tailwind CSS.

## 🚀 Features

- ⚡️ Next.js with App Router
- 💎 TypeScript for type safety
- 🎨 Tailwind CSS for styling
- 📱 Responsive design
- 🔍 SEO optimized
- 🌙 Dark mode support
- 🎯 ESLint and Prettier for code consistency

## 🛠️ Tech Stack

- [Next.js ](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/Isuru-Pradeep/zephyr-matrix.git
```

2. Install dependencies:

```bash
cd zephyr-matrix
npm install
```

3. Run the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🚧 Project Structure

```
zephyr-matrix/
├── public/
│   ├── assets/
│   │   ├── images/
│   │   ├── videos/
│   │   └── icons/
│   └── favicon.ico
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── loading.tsx        # Spinner for initial load
│   │   ├── page.tsx
│   │   ├── vision/
│   │   │   └── page.tsx
│   │   ├── solutions/
│   │   │   ├── page.tsx
│   │   │   └── [id]/
│   │   │       └── page.tsx
│   │   ├── impact/
│   │   │   ├── page.tsx
│   │   │   └── [slug]/
│   │   │       └── page.tsx
│   │   ├── connect/
│   │   │   └── page.tsx
│   │   └── insights/
│   │       ├── page.tsx
│   │       └── [slug]/
│   │           └── page.tsx
│   ├── components/
│   │   ├── core/
│   │   │   ├── Button.tsx
│   │   │   ├── Surface.tsx
│   │   │   └── Typography.tsx
│   │   ├── layout/
│   │   │   ├── Navigation.tsx
│   │   │   ├── Footer.tsx
│   │   │   └── Grid.tsx
│   │   └── experiences/
│   │       ├── Hero.tsx
│   │       ├── Showcase.tsx
│   │       └── Gallery.tsx
│   ├── styles/
│   │   └── globals.css        # Tailwind imports
│   └── lib/
│       ├── animations/
│       │   └── useParallax.ts
│       └── api/
│           └── fetchData.ts
├── tailwind.config.js         # Tailwind configuration
├── postcss.config.js          # PostCSS configuration
├── next.config.js
├── tsconfig.json
├── package.json
└── README.md
```

## 🔑 Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_API_URL=your_api_url
```

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
