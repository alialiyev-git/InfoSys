# InfoSys - Personal Portfolio Website

A Jekyll-based portfolio website with three main pages: Home, About, and Projects.

## Project Structure

```
InfoSys/
├── _config.yml          # Jekyll configuration (points to src/)
├── Gemfile              # Ruby dependencies
├── Gemfile.lock         # Locked gem versions
├── README.md            # This file
├── .github/
│   └── workflows/       # GitHub Actions for deployment
├── src/                 # Source directory
│   ├── _layouts/        # Jekyll layout templates
│   │   └── default.html
│   ├── _includes/       # Reusable HTML components
│   │   ├── head.html
│   │   ├── nav.html
│   │   └── footer.html
│   ├── pages/           # Page content (markdown)
│   │   ├── index.md     # Home page
│   │   ├── about.md     # About page
│   │   └── projects.md  # Projects page
│   └── assets/          # Static assets
│       ├── css/
│       │   └── style.css
│       ├── js/
│       │   └── script.js
│       └── images/      # Project images
└── _site/               # Generated site (excluded from git)
```

## Live Site

The site is deployed on GitHub Pages at:
**https://alialiyev-git.github.io/InfoSys/**

## Local Development

### Requirements
- Ruby 3.0+ (with gem and bundler)
- See installation instructions below if Ruby is not available

### Setup & Run Locally

1. Clone the repository:
```bash
git clone https://github.com/alialiyev-git/InfoSys.git
cd InfoSys
```

2. Install dependencies:
```bash
gem install bundler      # if Bundler is not installed
bundle install           # install gems from Gemfile
```

3. Run the Jekyll development server:
```bash
bundle exec jekyll serve --livereload
```

4. Open your browser and go to:
```
http://localhost:4000
```

The server will watch for file changes and auto-reload the page when you edit content.

## Pages

- **Home** (`src/pages/index.md`) — Welcome page with hero section and call-to-action
- **About** (`src/pages/about.md`) — Personal bio, skills, and journey
- **Projects** (`src/pages/projects.md`) — Portfolio showcasing projects with descriptions

## Customization

### Edit Content
- Modify markdown files in `src/pages/` to update page content
- Edit `_config.yml` to change site title, email, and other settings

### Edit Styling
- Update `src/assets/css/style.css` to customize colors, fonts, and layout
- Styles are applied automatically via Jekyll's templating

### Add Project Images
- Place project images in `src/assets/images/`
- Update image references in `src/pages/projects.md`

### Update Navigation
- Edit `src/_includes/nav.html` to add/remove navigation links

## Technologies

- **Jekyll** — Static site generator
- **Liquid** — Template language for Jekyll
- **HTML5** — Markup
- **CSS3** — Styling with Flexbox and CSS Grid
- **JavaScript** — Client-side interactivity

## Notes

- All static assets are in `src/assets/` and served as-is by Jekyll
- The site uses semantic HTML for better accessibility
- Responsive design works on desktop, tablet, and mobile
- GitHub Pages automatically builds and deploys from the `main` branch

## Author

Created as a class project portfolio website.
