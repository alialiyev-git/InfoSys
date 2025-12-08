# InfoSys - Personal Portfolio Website

A Jekyll-based portfolio website with three main pages: Home, About, and Projects.

## Project Structure

```
InfoSys/
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Main site layout template
├── _includes/
│   ├── head.html        # HTML head (meta, links, title)
│   ├── nav.html         # Navigation bar
│   └── footer.html      # Footer
├── index.md             # Home page (markdown)
├── about.md             # About page (markdown)
├── projects.md          # Projects showcase page (markdown)
├── css/
│   └── style.css        # Main stylesheet
├── js/
│   └── script.js        # JavaScript functionality
├── assets/
│   └── images/          # Project images
├── Gemfile              # Ruby dependencies
├── Gemfile.lock         # Locked gem versions
└── README.md            # This file
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

- **Home** (`index.md`) — Welcome page with hero section and call-to-action
- **About** (`about.md`) — Personal bio, skills, and journey
- **Projects** (`projects.md`) — Portfolio showcasing three projects with descriptions

## Customization

### Edit Content
- Modify markdown files (`index.md`, `about.md`, `projects.md`) to update page content
- Edit `_config.yml` to change site title, email, and other settings

### Edit Styling
- Update `css/style.css` to customize colors, fonts, and layout
- Styles are applied automatically via Jekyll's templating

### Add Project Images
- Place project images in `assets/images/`
- Update image paths in `projects.md` if needed

### Update Navigation
- Edit `_includes/nav.html` to add/remove navigation links

## Technologies

- **Jekyll** — Static site generator
- **Liquid** — Template language for Jekyll
- **HTML5** — Markup
- **CSS3** — Styling with Flexbox and CSS Grid
- **JavaScript** — Client-side interactivity

## Notes

- All static assets (`css/`, `js/`, `assets/`) are served as-is by Jekyll
- The site uses semantic HTML for better accessibility
- Responsive design works on desktop, tablet, and mobile
- GitHub Pages automatically builds and deploys from the `main` branch

## Author

Created as a class project portfolio website.
