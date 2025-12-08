 # My Portfolio Website (Jekyll)

This repository contains a small Jekyll-based portfolio website. The original HTML pages were converted to Jekyll markdown pages and use a shared layout and includes.

## Project Structure

```
my_portfolio/
├── _config.yml         # Jekyll config
├── _layouts/
│   └── default.html    # Main site layout
├── _includes/
│   ├── head.html
│   ├── nav.html
│   └── footer.html
├── index.md            # Home page (markdown)
├── about.md            # About page (markdown)
├── projects.md         # Projects page (markdown)
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   └── images/
└── README.md
```

## Local development (Jekyll)

Requirements: Ruby and Bundler installed and available in your shell.

From the `my_portfolio` folder run:

```powershell
Set-Location 'C:\Users\User\Downloads\InfoSys\my_portfolio'
gem install bundler     # if Bundler is not installed
bundle install          # install gems from Gemfile
bundle exec jekyll serve --livereload
```

Open `http://localhost:4000` in your browser to preview the site. The server supports live reload when you edit files.

## Notes

- Static assets (`css`, `js`, `assets/images`) are served as-is by Jekyll.
- If you prefer to keep the static HTML copies, they have been removed to avoid duplicate content. The markdown pages are the canonical source.
- Keep `Gemfile` and `Gemfile.lock` inside `my_portfolio/` to ensure reproducible gem versions.

## Author

Created as a class project portfolio website.
