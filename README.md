# NVIDIA NIM Frontend

Simple Web interface written in Svelte 5 to use NVIDIA NIM Image Generator Services.

## Features

- ⚡ Built with [Svelte 5](https://svelte.dev/)
- 🎨 Styled with [Tailwind CSS](https://tailwindcss.com/)
- 📦 TypeScript support
- 🚀 Static site generation with GitHub Pages deployment
- 🔧 Vite for fast development and building

## Development

### Prerequisites

- Node.js 18+ 
- npm

### Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run check` - Run TypeScript checks

## Deployment

The project is configured for automatic deployment to GitHub Pages via GitHub Actions. When you push to the `main` branch, the site will be automatically built and deployed.

### Manual Deployment

To build for production:

```bash
npm run build
```

The built site will be in the `build/` directory.

## Tech Stack

- **Framework**: Svelte 5
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Build Tool**: Vite
- **Deployment**: GitHub Pages via GitHub Actions

## License

GPL-3.0 License - see [LICENSE](LICENSE) file for details.
