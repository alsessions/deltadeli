# Delta Deli Website

A static website for Delta Deli, a small deli and restaurant in Rome, NY. Built with Eleventy and Tailwind CSS 3.

## Prerequisites

- Node.js (v14 or higher)
- npm

## Installation

1. Install dependencies:

```bash
npm install
```

## Development

Start the development server with live reload:

```bash
npm start
```

This will:
- Start Eleventy dev server at `http://localhost:8080`
- Watch and compile Tailwind CSS
- Auto-reload on file changes

## Build

Build the production-ready site:

```bash
npm run build
```

The compiled site will be in the `_site` directory.

## Project Structure

```
DeltaDeli/
├── src/
│   ├── _data/          # Global data files
│   ├── _includes/      # Reusable components
│   ├── _layouts/       # Page layouts
│   ├── images/         # Image assets
│   ├── styles/         # Tailwind CSS source
│   ├── index.njk       # Home page
│   ├── menu.njk        # Menu page
│   ├── about.njk       # About page
│   └── contact.njk     # Contact page
├── _site/              # Built site (generated)
├── .eleventy.js        # Eleventy configuration
├── tailwind.config.js  # Tailwind configuration
└── package.json
```

## Technologies

- **Eleventy** - Static site generator
- **Tailwind CSS 3** - Utility-first CSS framework
- **Nunjucks** - Templating engine

## License

MIT