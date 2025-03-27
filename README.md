

A modern, responsive portfolio website designed for a cybersecurity student at BITS. The site showcases skills, projects, and contact information with a sleek, professional design.

## Features

- Fully responsive design that works on all devices
- Modern UI with smooth animations and transitions
- Interactive navigation with smooth scrolling
- Skills section with animated progress bars
- Project showcase with hover effects
- Contact form with validation
- Mobile-friendly navigation

## Technologies Used

- HTML5
- CSS3 (with CSS variables, flexbox, and grid)
- JavaScript (vanilla, no frameworks)
- Font Awesome for icons

## File Structure

```
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
└── images/             # Directory for images (add your own)
```

## Customization Instructions

### 1. Personal Information

Edit the `index.html` file to replace placeholder content with your own:

- Update your name, location, and contact details
- Modify the "About Me" section with your own background and interests
- Adjust skills and their proficiency levels in the Skills section
- Add your own projects with descriptions and links

### 2. Color Scheme

To change the color scheme, edit the CSS variables in the `:root` selector in `css/style.css`:

```css
:root {
    --primary-color: #4a69bd;      /* Main accent color */
    --secondary-color: #6a89cc;    /* Secondary accent color */
    --accent-color: #1e3799;       /* Darker accent for hover states */
    --dark-color: #1e272e;         /* Dark sections background */
    --light-color: #f5f6fa;        /* Light sections background */
    --text-color: #2c3e50;         /* Main text color */
    /* ... other variables ... */
}
```

### 3. Images

- Replace placeholder images with your own by adding them to the `images` directory
- Make sure to update any image paths in the HTML and CSS files

## Browser Compatibility

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Getting Started

1. Clone or download this repository
2. Customize the content in the HTML file
3. Add your own images to the images directory
4. Open index.html in your browser to view the site
5. For deployment, upload all files to your web hosting provider

## Credits

- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by Google Fonts 
