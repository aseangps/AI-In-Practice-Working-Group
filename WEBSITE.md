# AI-In-Practice Working Group Website

This repository now includes a simple, responsive website for the AI-In-Practice Working Group.

## Files

- `index.html` - Homepage with group overview, principles, current chapter, and workflow
- `about.html` - Detailed about page with mission, ground rules, and how to participate
- `style.css` - Responsive CSS styling for both pages
- `WEBSITE.md` - This documentation file

## Local Development

To view the website locally:

1. Navigate to the repository directory
2. Start a local web server:
   ```bash
   python3 -m http.server 8080
   ```
3. Open your browser and go to `http://localhost:8080`

## Updating the Website

The website is designed to be easy to update as the group evolves:

### Adding New Chapters
1. Update the "Current Chapter" section in `index.html`
2. Update the sidebar in `about.html` with new chapter information
3. Update any relevant links to chapter-specific resources

### Modifying Group Information
- Main group description and mission: Update both `index.html` hero section and `about.html` mission section
- Principles: Update the principles section in `index.html`
- Ground rules: Update the ground rules grid in `about.html`
- Workflow changes: Update both the workflow section in `index.html` and detailed workflow in `about.html`

### Styling Changes
All styling is contained in `style.css`. The design uses:
- CSS Grid and Flexbox for responsive layouts
- CSS custom properties for easy color scheme changes
- Mobile-first responsive design with breakpoints at 768px and 480px

## GitHub Pages

The website can be easily deployed using GitHub Pages:
1. Go to repository Settings > Pages
2. Select "Deploy from a branch"
3. Choose the main branch
4. The website will be available at `https://aseangps.github.io/AI-In-Practice-Working-Group/`

## Key Features

- **Responsive Design**: Works well on desktop, tablet, and mobile devices
- **Clean Navigation**: Simple navigation between home and about pages
- **External Links**: Direct links to GitHub repository, project boards, and other resources
- **Professional Appearance**: Modern gradient design with good typography
- **Accessible**: Semantic HTML structure and good color contrast
- **Fast Loading**: No external dependencies, pure HTML/CSS