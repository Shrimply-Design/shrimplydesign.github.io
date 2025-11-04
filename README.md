# Shrimply Design - Artist Portfolio

A modern, responsive artist portfolio website built with Astro and deployed on GitHub Pages.

## 🌐 Live Site

Visit the live site at [shrimply.design](https://shrimply.design)

## 🚀 Features

- **Modern Design**: Clean, responsive layout that works on all devices
- **Portfolio Gallery**: Showcase artworks with a beautiful grid layout
- **About Page**: Tell your story and highlight your skills
- **Contact Form**: Easy way for visitors to get in touch
- **Fast Performance**: Built with Astro for optimal speed and SEO
- **Custom Domain**: Configured for shrimply.design

## 🛠️ Tech Stack

- **Framework**: Astro 4.16.1
- **Styling**: CSS (scoped and global styles)
- **Deployment**: GitHub Pages
- **TypeScript**: Strict type checking

## 📦 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Shrimply-Design/shrimplydesign.github.io.git
cd shrimplydesign.github.io
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:4321`

## 🏗️ Build

To build the site for production:

```bash
npm run build
```

The built site will be in the `dist/` directory.

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run astro` - Run Astro CLI commands

## 🎨 Customization

### Pages

- `src/pages/index.astro` - Home page
- `src/pages/portfolio.astro` - Portfolio gallery
- `src/pages/about.astro` - About page
- `src/pages/contact.astro` - Contact page

### Layout

- `src/layouts/Layout.astro` - Main layout with navigation and footer

### Styling

The site uses CSS variables for easy theming. Edit colors in `src/layouts/Layout.astro`:

```css
:root {
  --primary-color: #2d3748;
  --secondary-color: #4a5568;
  --accent-color: #ed8936;
  /* ... */
}
```

## 🚢 Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch via GitHub Actions.

### Custom Domain Setup

The site is configured for the custom domain `shrimply.design`:

1. The `public/CNAME` file contains the domain
2. DNS records should point to GitHub Pages
3. GitHub Pages settings should have the custom domain configured

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!