# Muhammad Nazim - Data & Analytics Portfolio

Professional portfolio showcasing enterprise data architecture and analytics projects.

## Live Site
Visit: https://nazimchaudhary.github.io (once deployed)

## Technologies
- HTML5
- CSS3 (Custom responsive design)
- JavaScript (ES6+)
- GitHub Pages (Hosting)

## Features
- Responsive design for all devices
- Project filtering by technology and industry
- Detailed case studies for major projects
- Professional, enterprise-focused design
- Fast loading and optimized performance

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/nazimchaudhary/nazimchaudhary.github.io.git
cd nazimchaudhary.github.io
```

2. Open `index.html` in your browser to view locally

## Deployment to GitHub Pages

### First Time Setup

1. Create a GitHub account at https://github.com

2. Create a new repository named: `nazimchaudhary.github.io`
   - Make it Public
   - Don't initialize with README (we have one)

3. Upload all files to the repository:
   - Go to your repository on GitHub
   - Click "uploading an existing file"
   - Drag and drop all files and folders
   - Click "Commit changes"

4. Enable GitHub Pages:
   - Go to repository Settings
   - Click "Pages" in left sidebar
   - Under "Source", select: `main` branch
   - Click Save

5. Your site will be live at: `https://nazimchaudhary.github.io`
   - It may take 2-3 minutes to deploy

### Updating Content

To update your portfolio:
1. Edit files locally
2. Go to your GitHub repository
3. Click "Upload files" or edit directly in GitHub
4. Changes will automatically deploy in 1-2 minutes

## Project Structure

```
portfolio/
├── index.html              # Homepage with project grid
├── about.html              # About page
├── contact.html            # Contact information
├── projects/               # Individual project pages
│   ├── signal.html
│   ├── coca-cola.html
│   ├── starlinks.html
│   └── [other projects]
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── filter.js       # Project filtering
│   └── images/             # Project images/diagrams
└── README.md               # This file
```

## Adding New Projects

1. Create new HTML file in `projects/` folder
2. Use existing project pages as template
3. Add project card to `index.html` in the projects grid
4. Include appropriate `data-filters` attribute for filtering
5. Upload architecture diagram to `assets/images/`

## Customization

### Colors
Edit CSS variables in `assets/css/style.css`:
```css
:root {
    --primary-navy: #1B4F72;
    --secondary-blue: #2E86AB;
    --accent-amber: #E87E04;
}
```

### Content
- Homepage: Edit `index.html`
- About: Edit `about.html`
- Contact: Edit `contact.html`
- Projects: Edit files in `projects/` folder

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance
- No external dependencies
- Optimized CSS and JavaScript
- Fast page load times
- Mobile-first responsive design

## Contact
Muhammad Nazim
- Email: nazimch77@gmail.com
- LinkedIn: https://www.linkedin.com/in/nazim-chaudhary

## License
© 2024 Muhammad Nazim. All rights reserved.
