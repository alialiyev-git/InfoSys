# InfoSystems - Personal Portfolio Website

A Jekyll-based portfolio website with three main pages: Home, About, and Projects.

## Project Structure

```
alialiyev-git.github.io/
├── _config.yml          # Jekyll configuration (points to src/)
├── Gemfile              # Ruby dependencies
├── Gemfile.lock         # Locked gem versions
├── README.md            # This file
├── .github/
│   └── workflows/       # GitHub Actions for deployment
├── src/                 # Source directory
    ├── _layouts/        # Jekyll layout templates
    │   └── default.html
    ├── _includes/       # Reusable HTML components
    │   ├── head.html
    │   ├── nav.html
    │   └── footer.html
    ├── pages/           # Page content (markdown)
    │   ├── index.md     # Home page
    │   ├── about.md     # About page
    │   └── projects.md  # Projects page
    └── assets/          # Static assets
        ├── css/
        │   └── style.css
        ├── js/
        │   └── script.js
        └── images/      # Project images
```

## Live Site

The site is deployed on GitHub Pages at:
**https://alialiyev-git.github.io/**

## Technologies
- Ruby (with gem and Bundler)
- Jekyll
- Liquid
- HTML5
- CSS3
- JavaScript

## Pages

- **Home** (`src/pages/index.md`) — Welcome page with hero section and call-to-action
- **About** (`src/pages/about.md`) — Personal bio, skills, and journey
- **Projects** (`src/pages/projects.md`) — Portfolio showcasing projects with descriptions

## Notes

- All static assets are in `src/assets/` and served as-is by Jekyll
- The site uses semantic HTML for better accessibility
- Responsive design works on desktop, tablet, and mobile
- The site is built and deployed automatically via GitHub Actions


## Author

- Ali Aliyev

