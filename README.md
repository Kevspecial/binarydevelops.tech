# Binary Develops - Personal Portfolio & Blog

> A modern, responsive portfolio and blog website built with Hugo, showcasing my work as a Fullstack Engineer and IT Consultant.

[![Netlify Status](https://img.shields.io/badge/Deployed%20on-Netlify-00C7B7?logo=netlify&logoColor=white)](https://binarydevelops.tech/)
[![Hugo](https://img.shields.io/badge/Hugo-v0.87.0+-FF4088?logo=hugo&logoColor=white)](https://gohugo.io/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🌐 Live Demo

Visit the live site: **[binarydevelops.tech](https://binarydevelops.tech/)**

## 📋 About

This is my personal portfolio website featuring my professional experience, technical skills, blog posts, and project showcase. The site is designed with a clean, minimalist aesthetic and provides an interactive way to learn about my work and connect with me.

## ✨ Features

### Design & User Experience
- 📱 **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- 🎨 **Minimalist Design** - Clean and professional interface
- 🌓 **Light/Dark Mode** - Toggle between themes with auto-detection support
- ⚡ **Fast Performance** - Static site generation for lightning-fast load times
- ♿ **Accessible** - Built with accessibility best practices

### Content & Functionality
- 📝 **Blog Section** - Write and share technical articles with markdown support
- 🖼️ **Gallery** - Visual portfolio showcase
- 📊 **Project Showcase** - Highlight your best work
- 🎓 **Experience & Education** - Professional timeline
- 🏆 **Achievements Section** - Display accomplishments
- 📧 **Contact Form** - Easy communication via Formspree integration
- 🔍 **Search Functionality** - Quick content discovery
- 🏷️ **Taxonomies** - Organize content with tags and categories

### Technical Features
- 🔍 **SEO Optimized** - Built-in SEO best practices
- 📈 **Analytics Support** - Google Analytics ready
- 💬 **Comment System** - Disqus integration support
- 🎨 **Customizable Colors** - Easy theme customization
- 🤖 **robots.txt & Sitemap** - Search engine friendly
- 📡 **RSS Feed** - Stay connected with readers

## 🛠️ Technology Stack

- **[Hugo](https://gohugo.io/)** - Static Site Generator (v0.87.0+)
- **[hugo-profile](https://github.com/gurusabarish/hugo-profile)** - Hugo theme
- **[Bootstrap](https://getbootstrap.com/)** - CSS Framework
- **[Font Awesome](https://fontawesome.com/)** - Icons
- **[Netlify](https://www.netlify.com/)** - Hosting & Continuous Deployment

## 🚀 Getting Started

### Prerequisites

- [Hugo Extended](https://gohugo.io/getting-started/installing/) version 0.87.0 or higher
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kevspecial/binarydevelops.tech.git
   cd binarydevelops.tech
   ```

2. **Initialize and update the theme submodule**
   ```bash
   git submodule update --init --recursive
   ```

3. **Run the development server**
   ```bash
   hugo server -D
   ```

4. **Open your browser**
   
   Navigate to `http://localhost:1313/` to see your site in action!

## 📝 Development

### Project Structure

```
binarydevelops.tech/
├── archetypes/          # Content templates
├── content/             # Site content
│   ├── blogs/          # Blog posts
│   └── gallery.md      # Gallery page
├── layouts/            # Custom layouts
├── public/             # Generated static files (gitignored)
├── static/             # Static assets (images, icons, etc.)
├── themes/             # Hugo themes
│   └── hugo-profile/   # Theme submodule
├── config.yml          # Site configuration
└── README.md           # This file
```

### Creating New Content

**Create a new blog post:**
```bash
hugo new blogs/my-new-post.md
```

**Edit the post:**
Navigate to `content/blogs/my-new-post.md` and start writing in markdown.

### Configuration

Edit `config.yml` to customize:
- Personal information (name, title, bio)
- Social media links
- Navigation menu
- Theme colors and fonts
- Contact information
- Analytics IDs

### Building for Production

```bash
hugo --minify
```

This generates optimized static files in the `public/` directory.

## 🌐 Deployment

This site is automatically deployed to [Netlify](https://www.netlify.com/) from the main branch. Any push to the main branch triggers a new build and deployment.

### Manual Deployment

1. Build the site: `hugo --minify`
2. Deploy the `public/` folder to your hosting provider

### Supported Platforms
- Netlify (Current)
- Vercel
- GitHub Pages
- AWS S3 + CloudFront
- Any static hosting service

## 🎨 Customization

### Theme Customization

The site uses the [hugo-profile](https://github.com/gurusabarish/hugo-profile) theme. For detailed customization options:

- [Color Customization Guide](https://github.com/gurusabarish/hugo-profile/wiki/Color-Customization)
- [Configuration Documentation](https://github.com/gurusabarish/hugo-profile#readme)

### Adding Analytics

Uncomment and configure in `config.yml`:
```yaml
googleAnalytics: G-MEASUREMENT_ID
```

### Adding Comments

Uncomment and configure in `config.yml`:
```yaml
disqusShortname: your-disqus-shortname
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Kelvin Nwokike (Binary.OG)**

- Website: [binarydevelops.tech](https://binarydevelops.tech/)
- GitHub: [@Kevspecial](https://github.com/Kevspecial)
- LinkedIn: [Kelvin Nwokike](https://www.linkedin.com/in/kelvin-nwokike-32b1741b4/)
- Twitter: [@binary_og](https://twitter.com/binary_og)
- Instagram: [@binary.og](https://www.instagram.com/binary.og/?hl=en)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Kevspecial/binarydevelops.tech/issues).

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

## 🙏 Acknowledgments

- [Hugo](https://gohugo.io/) - The world's fastest framework for building websites
- [hugo-profile](https://github.com/gurusabarish/hugo-profile) - Awesome Hugo theme by [@gurusabarish](https://github.com/gurusabarish)
- [Netlify](https://www.netlify.com/) - Excellent hosting and deployment platform

---

<p align="center">Made with ❤️ and Hugo</p>