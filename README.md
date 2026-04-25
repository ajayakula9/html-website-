# HTML Website

A simple HTML website ready for GitHub Pages deployment.

## Features

- Semantic HTML5 structure
- Responsive CSS styling
- Modern, clean design
- GitHub Actions workflow for automatic deployment

## Local Development

1. Clone this repository
2. Open `index.html` in your web browser
3. Make changes to the HTML and CSS files as needed

## Deployment to GitHub Pages

### Option 1: Using GitHub Actions (Recommended)

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Under "Build and deployment", select "Source" as "GitHub Actions"
4. The `.github/workflows/deploy.yml` workflow will automatically deploy your site

### Option 2: Using Main Branch

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Under "Build and deployment", select "Source" as "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Click Save

Your website will be available at: `https://yourusername.github.io/html-website/`

## Customization

- Edit `index.html` to change the content
- Edit `styles.css` to modify the styling
- Add new HTML files for additional pages

## License

This project is open source and available for personal and commercial use.

## Deployment Status

Website deployed via GitHub Actions.
