# Modern Next.js Starter Template

A modern, feature-rich starter template built with Next.js 15, Shadcn/UI, next-themes, and Tailwind CSS.

## Features

- ⚡ **Next.js 15** - The React framework for production
- 🎨 **Shadcn/UI** - High-quality, reusable components built with Radix UI and Tailwind CSS
- 🌓 **Dark Mode** - Seamless dark/light mode integration with next-themes
- 💅 **Tailwind CSS** - Utility-first CSS framework
- 🎯 **TypeScript** - Static type checking
- 📏 **ESLint & Prettier** - Code formatting and linting
- 🎭 **Lucide Icons** - Beautiful & consistent icon set

## Getting Started

### Prerequisites

- Node.js 18+ (LTS recommended)
- pnpm, npm, or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/YassinMashaly7/NextJs-15-Starter
```

2. Install dependencies:

```bash
pnpm install
# or
npm install
# or
yarn install
```

3. Run the development server:

```bash
pnpm dev
# or
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
├── src/
│   ├── app/
│   ├── components/
│   └── styles/
├── public/
├── tailwind.config.ts
├── next.config.ts
└── package.json
```

## Customization

### Styling

This template uses Tailwind CSS for styling. The configuration file can be found in `tailwind.config.ts`.

### Theme

Dark mode is implemented using `next-themes`. You can modify the theme in your components using:

```tsx
import { useTheme } from "next-themes";

const { theme, setTheme } = useTheme();
```

### Components

Shadcn/UI components can be added using the CLI:

```bash
npx shadcn-ui@latest add button
```

### Icons

This template includes Lucide React icons. You can use them in your components like this:

```tsx
import { Home, Settings, Moon } from "lucide-react";

// Use in JSX
<Home size={24} />;
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [Shadcn/UI](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [next-themes](https://github.com/pacocoursey/next-themes)
- [Lucide Icons](https://lucide.dev/)
