# Miguel Barreiro - Portfolio Site

A modern, responsive portfolio website showcasing professional experience and technical skills.

## Project Structure

```
miguel-site/
├── public/              # Static assets for deployment
│   ├── index.html      # Main HTML file
│   ├── styles.css      # Stylesheet
│   └── script.js       # JavaScript for interactions
├── wrangler.toml       # Cloudflare configuration
└── README.md           # This file
```

## Deployment to Cloudflare Pages

### Option 1: Using Wrangler CLI (Recommended)

1. Install Wrangler if you haven't already:
```bash
npm install -g wrangler
```

2. Login to Cloudflare:
```bash
wrangler login
```

3. Deploy the site:
```bash
wrangler pages deploy ./public --project-name=miguelbarreiro-site
```

### Option 2: Using Cloudflare Dashboard

1. Go to [Cloudflare Pages](https://dash.cloudflare.com/pages)
2. Click "Create a project"
3. Connect your Git repository (or upload directly)
4. Configure build settings:
   - **Build command:** (leave empty - no build needed)
   - **Build output directory:** `public`
5. Click "Save and Deploy"

## Local Development

To test the site locally with Cloudflare Pages dev server:

```bash
wrangler pages dev ./public
```

Or simply open `public/index.html` in your browser.

## Features

- Responsive design for all devices
- Smooth scrolling navigation
- Animated sections on scroll
- Modern dark theme with gradient accents
- Professional timeline for work experience
- Interactive skill tags

## Technologies Used

- HTML5
- CSS3 (with CSS variables and animations)
- Vanilla JavaScript
- Cloudflare Pages for hosting

## Contact

- **Email:** miguelbarreiro85@gmail.com
- **LinkedIn:** [miguel-barreiro-096243138](https://www.linkedin.com/in/miguel-barreiro-096243138/)
- **GitHub:** [miguelBarreiro85](https://github.com/miguelBarreiro85)
