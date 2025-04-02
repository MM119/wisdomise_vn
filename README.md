# Wisdomise.vn Website

This is the GitHub Pages repository for wisdomise.vn. The site is hosted using GitHub Pages with a custom domain configured.

## Project Structure

- `index.html` - Main website content
- `css/style.css` - Stylesheet for the website
- `js/main.js` - JavaScript for interactive functionality
- `CNAME` - Custom domain configuration file
- `images/` - Directory for website images

## Development

To run this site locally:

```bash
# Clone the repository
git clone https://github.com/MM119/wisdomise_vn.git

# Navigate to the project
cd wisdomise_vn

# You can use any simple HTTP server to test locally, e.g.:
python -m http.server
# Then visit http://localhost:8000 in your browser
```

## Deployment

This site is deployed automatically through GitHub Pages when changes are pushed to the main branch.

## Custom Domain Setup

The website is configured to use the custom domain `wisdomise.vn`. DNS configuration includes:

- A Records pointing to GitHub Pages IP addresses
- CNAME Record for www subdomain pointing to MM119.github.io
