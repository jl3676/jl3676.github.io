# Personal Academic Website

A personal academic website built using Jekyll and based on the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Overview

This website serves as an academic portfolio featuring:

- **Publications**: Automatically generated from BibTeX bibliography with keyword filtering
- **Projects**: Research projects and academic work
- **CV**: Academic curriculum vitae
- **Blog**: Academic blog posts and research notes

## Customizations

This website extends the original al-folio theme with several custom features:

- **Publication Keyword Filtering**: Interactive sidebar filters to browse publications by venue and research topics
- **Custom CSS Designs**: Enhanced styling for better visual presentation and user experience
- **Optimized Layout**: Improved publication entry layouts with better spacing and responsive design

## Built With

- **Jekyll** - Static site generator
- **al-folio** - Academic Jekyll theme
- **GitHub Pages** - Hosting and deployment
- **Bootstrap** - Responsive design framework

## Local Development

To run the website locally:

```bash
# Install dependencies
bundle install

# Start the Jekyll server
bundle exec jekyll serve --host 0.0.0.0 --port 4000 --livereload
```

The site will be available at `http://localhost:4000`.

## Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the `master` branch. The deployment workflow includes:

- Automated building with Jekyll
- CSS optimization and purging
- Link checking and code formatting
- GitHub Pages deployment

## Configuration

Key configuration files:

- `_config.yml` - Site configuration and settings
- `_bibliography/papers.bib` - Publication bibliography
- `_data/cv.yml` - CV data
- `_pages/` - Main website pages

## License

This project is based on the [al-folio](https://github.com/alshedivat/al-folio) theme, which is available under the [MIT License](https://github.com/alshedivat/al-folio/blob/master/LICENSE).

---

_Built with ❤️ using Jekyll and al-folio_
