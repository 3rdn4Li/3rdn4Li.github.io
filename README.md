# Hongwei Li - Academic Website

This is my personal academic website built with Hugo and the Wowchemy theme.

## Features

- **Personal Information**: Biography, education, work experience
- **Research Areas**: Cybersecurity, Software Engineering, Program Analysis
- **Publications**: Academic papers and research publications
- **Contact Information**: Email, GitHub, Google Scholar
- **Responsive Design**: Works on desktop and mobile devices

## Quick Start

### Prerequisites

- Hugo Extended version (v0.121.1 or later)

### Local Development

1. Clone this repository:
```bash
git clone https://github.com/3rdn4Li/3rdn4Li.github.io.git
cd 3rdn4Li.github.io
```

2. Install Hugo (if not already installed):
```bash
# Download Hugo Extended
wget https://github.com/gohugoio/hugo/releases/download/v0.121.1/hugo_extended_0.121.1_linux-amd64.tar.gz
tar -xzf hugo_extended_0.121.1_linux-amd64.tar.gz
sudo mv hugo /usr/local/bin/
```

3. Run the development server:
```bash
hugo server --buildDrafts --buildFuture
```

4. Open your browser and visit `http://localhost:1313`

### Building for Production

```bash
hugo --minify
```

The built site will be in the `public/` directory.

## Deployment

This site is configured for GitHub Pages deployment. Simply push to the main branch and GitHub Actions will automatically build and deploy the site.

## Customization

### Personal Information
Edit `content/authors/admin/_index.md` to update your personal information, including:
- Name and title
- Contact information
- Education and work experience
- Skills and interests
- Awards and achievements

### Site Configuration
Edit files in `config/_default/` to customize:
- Site title and description (`hugo.yaml`)
- Navigation menu (`menus.yaml`)
- Site parameters (`params.yaml`)

### Content
- Add publications in `content/publication/`
- Add blog posts in `content/post/`
- Add projects in `content/project/`
- Add talks/events in `content/event/`

## Contact

- Email: lihongweiandre@gmail.com
- GitHub: https://github.com/3rdn4Li
- Google Scholar: https://scholar.google.com/citations?hl=zh-CN&user=TODhN38AAAAJ

## License

This website is built with the [Wowchemy](https://wowchemy.com/) theme for Hugo.
