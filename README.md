# Proaxis AI Website

A modern Jekyll website for Proaxis AI, a conversational AI consulting company founded by PhDs specializing in research, design, development, and deployment of AI solutions.

## Quick Start

### Prerequisites
- Ruby (version 2.7 or higher)
- Jekyll
- Bundler

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd proaxis-ai
```

2. Install dependencies:
```bash
bundle install
```

3. Serve the site locally:
```bash
bundle exec jekyll serve
```

4. Open your browser and navigate to `http://localhost:4000`

### Windows Setup

If you're on Windows, you can install Ruby and Jekyll using:

1. Download and install Ruby from [rubyinstaller.org](https://rubyinstaller.org/)
2. Install Jekyll and Bundler:
```powershell
gem install jekyll bundler
```

## Site Structure

- `_config.yml` - Site configuration
- `_layouts/` - Page layouts
- `_includes/` - Reusable components
- `_team/` - Team member profiles
- `assets/` - CSS, images, and other assets
- `*.md` - Main pages (about, services, team, contact)
- `index.html` - Homepage

## Features

- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **Team Profiles**: Collection-based team member pages
- **Service Showcase**: Detailed service offerings
- **Contact Form**: Ready for integration with form handlers
- **SEO Optimized**: Jekyll SEO tag integration
- **Modern Typography**: Uses Inter font family
- **Clean Navigation**: Sticky header with smooth transitions

## Customization

### Adding Team Members

Create new files in the `_team/` directory with the following front matter:

```yaml
---
name: Team Member Name
title: Their Title
photo: /assets/images/team/filename.jpg
bio: Their biography...
---
```

### Updating Content

- **Homepage**: Edit `index.html`
- **About Page**: Edit `about.md`
- **Services**: Edit `services.md`
- **Team Page**: Edit `team.md`
- **Contact**: Edit `contact.md`

### Styling

The main stylesheet is located at `assets/styles.css`. The design uses CSS custom properties (variables) for easy color and spacing customization.

### Contact Form

The contact form is currently set up as a static form. To make it functional, you'll need to:

1. Set up a form handler service (Netlify Forms, Formspree, etc.)
2. Update the form action in `contact.md`
3. Configure any necessary JavaScript for form validation

## Deployment

### GitHub Pages
This site is ready for GitHub Pages deployment. Simply push to a GitHub repository and enable Pages in the settings.

### Netlify
1. Connect your Git repository to Netlify
2. Set the build command to `jekyll build`
3. Set the publish directory to `_site`

### Other Hosting
Build the site locally with `bundle exec jekyll build` and upload the `_site` directory to your web server.

## Content Updates

All content currently uses Lorem Ipsum placeholder text. Update the following:

1. Replace placeholder text with actual company content
2. Add real team member photos to `assets/images/team/`
3. Update contact information in `contact.md` and `_config.yml`
4. Configure social media links in `_config.yml`
5. Set up the contact form with a real form handler

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE 11+ (with some CSS Grid fallbacks)

## License

This project is licensed under the MIT License.
