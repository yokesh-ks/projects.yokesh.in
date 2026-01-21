# Projects by Yokesh KS

A modern, responsive portfolio showcasing my web applications, developer tools, and creative projects. Built with Next.js 15, Tailwind CSS 4, and TypeScript.

![Projects Portfolio](https://img.shields.io/badge/Next.js-15-black) ![TypeScript](https://img.shields.io/badge/TypeScript-5-blue) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC)

## 🚀 Features

- **Modern Design**: Clean, responsive layout with dark/light mode support
- **Interactive Cards**: Hover animations, gradient backgrounds, and smooth transitions
- **Smart Filtering**: Search by title, description, or tags + category filtering
- **Favicon Integration**: Displays actual project favicons when available
- **UTM Tracking**: Automatic tracking parameters for analytics attribution
- **Mobile-First**: Fully responsive design for all screen sizes

## 📋 Projects Showcase

This portfolio features a curated collection of projects including:

- **Developer Tools**: NPM Stats, Domain Explorer, Markdown Live Preview
- **Web Applications**: HTML Code Editor, Postal Codes lookup
- **Educational**: React Learning Hub
- **E-commerce**: Medusa Plugins collection
- **Entertainment**: Ingenious Stream platform

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS 4
- **Icons**: Lucide React
- **Deployment**: Cloudflare Pages (OpenNext)
- **Language**: TypeScript

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm/yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yokesh-ks/projects.yokesh.in.git
cd projects.yokesh.in
```

2. Install dependencies:
```bash
pnpm install
```

3. Run the development server:
```bash
pnpm dev
```

4. Open [http://localhost:3007](http://localhost:3007) in your browser

## 📁 Project Structure

```
src/
├── app/
│   ├── layout.tsx      # Root layout with metadata
│   └── page.tsx        # Main projects page
├── components/
│   └── ProjectCard.tsx # Reusable project card component
└── data/
    └── projects.json   # Project data and configuration
```

## 🎨 Customization

### Adding New Projects

Edit `src/data/projects.json` to add new projects:

```json
{
  "id": "your-project-id",
  "title": "Your Project Name",
  "description": "Brief description of your project",
  "url": "https://your-project.com",
  "status": "live",
  "category": "Developer Tools",
  "tags": ["tag1", "tag2", "tag3"],
  "icon": "lucide:code",
  "gradient": "from-blue-500 to-purple-500",
  "favicon_url": "https://your-project.com/favicon.ico"
}
```

### Styling

- Colors and gradients can be customized in the project data
- Tailwind CSS classes are used throughout for consistent styling
- Dark mode is automatically supported

## 🚀 Deployment

### Cloudflare Pages (Recommended)

```bash
# Build for production
pnpm run build

# Deploy to Cloudflare
pnpm run deploy
```

### Other Platforms

The app can be deployed to any platform supporting Next.js:

- Vercel: `vercel --prod`
- Netlify: `netlify deploy --prod`
- Any Node.js hosting provider

## 📊 Analytics & Tracking

All external links include UTM parameters for proper analytics attribution:
- `utm_source=projects.yokesh.in`
- `utm_medium=website`
- `ref=projects.yokesh.in`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

© 2026 Yokesh KS. All rights reserved.

## 🔗 Links

- **Live Site**: [projects.yokesh.in](https://projects.yokesh.in)
- **Portfolio**: [yokesh.in](https://yokesh.in)
- **GitHub**: [yokesh-ks](https://github.com/yokesh-ks)

---

Built with ❤️ by [Yokesh KS](https://yokesh.in)
