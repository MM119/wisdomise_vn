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

## Color Palette

The website uses the following color palette:

```css
:root {
    --primary-color: #2A4E63;  /* Dark teal/blue - main brand color */
    --secondary-color: #FFFFFF; /* White for contrast */
    --accent-color: #CACACA;   /* Light gray accent */
    --text-color: #333333;     /* Dark text */
    --light-bg: #F5F5F5;       /* Light background */
    --footer-color: #1F3A4A;   /* Darker teal for footer */
}
```

### Color Usage Guidelines

- Primary color (#2A4E63): Used for headers, backgrounds, and primary UI elements. Represents the professional corporate identity.
- Secondary color (#FFFFFF): Used for text on dark backgrounds and as the main content background.
- Text color (#333333): Used for body text to ensure readability.
- Light background (#F5F5F5): Used for cards, service items, and secondary sections.
- Footer color (#1F3A4A): Used for the footer area, a slightly darker version of the primary color.

### Typography

- Headings: Playfair Display (serif)
- Body text: Raleway (sans-serif)
