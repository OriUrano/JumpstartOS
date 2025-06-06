# JumpstartOS

JumpstartOS helps developers find open-source issues that match their skills, making it easier to contribute and grow your portfolio.

## Features

- **Skill-based Matching:** Find issues relevant to your technology stack.
- **Multi-platform Search:** Aggregates issues from GitHub and GitLab.
- **Beginner Friendly:** Highlights "good first issue" and advanced challenges.
- **Community Focused:** Connect with maintainers and other contributors.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v20 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

```bash
git clone https://github.com/yourusername/jumpstartos.git
cd jumpstartos
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Deployment

JumpstartOS is configured for static site deployment (e.g., AWS S3, Netlify, Vercel). See `.github/workflows/deploy.yaml` for an example GitHub Actions workflow for deploying to AWS S3.

## Tech Stack

- [SvelteKit](https://kit.svelte.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/icons/)

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements or bug fixes.

## License

MIT License
