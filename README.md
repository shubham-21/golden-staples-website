# GOLDEN STAPLES - Static Website

This is a static website version of the GOLDEN STAPLES Spring Boot application. The site showcases premium Sattu products with information about recipes, health benefits, and the manufacturing process.

## Project Structure

```
goldengitHubStatic/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Custom styles
├── images/             # All image assets
│   ├── logo.png
│   ├── background.png
│   ├── Sattu-drink.png
│   ├── Sattu-Paratha.png
│   ├── Sattu-ladoo.png
│   ├── Sattu-Halwa.png
│   └── ...
└── README.md           # This file
```

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Beautiful, modern interface with smooth animations
- **Product Showcase**: Displays premium Sattu products
- **Recipe Section**: Interactive recipe cards with YouTube video links
- **Health Benefits**: Information about the health benefits of Sattu
- **Process Information**: Details about how the products are made
- **Contact Section**: Contact information and social media links

## How to Use

### Local Development

1. Simply open `index.html` in your web browser
2. Or use a local web server:

   **Using Python:**
   ```bash
   python -m http.server 8000
   ```
   Then open http://localhost:8000

   **Using Node.js (http-server):**
   ```bash
   npx http-server
   ```

   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

### Deployment

This static website can be deployed to any static hosting service:

#### GitHub Pages
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select the branch and folder (usually `main` and `/root`)
4. Your site will be available at `https://yourusername.github.io/goldengitHubStatic`

#### Netlify
1. Drag and drop this folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository for continuous deployment

#### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this directory
3. Follow the prompts

#### Other Options
- **Surge.sh**: `surge . your-domain.surge.sh`
- **Firebase Hosting**: Use Firebase CLI
- **AWS S3 + CloudFront**: Upload to S3 bucket and configure CloudFront
- **Any web server**: Upload files via FTP/SFTP

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **Tailwind CSS**: Utility-first CSS framework for enhanced styling and animations
- **Bootstrap 5**: Responsive framework and components
- **Bootstrap Icons**: Icon library
- **Google Fonts**: Poppins and Playfair Display fonts
- **Vanilla JavaScript**: Smooth scrolling functionality

## Tailwind CSS Features

This website uses Tailwind CSS for enhanced styling and animations:

- **Custom Color Palette**: Golden theme colors (`golden`, `golden-dark`) configured in Tailwind
- **Smooth Animations**: Fade-in animations, hover effects, and transitions
- **Interactive Elements**: 
  - Hover scale and rotate effects on cards
  - Enhanced button hover states with shadows
  - Social media icons with rotation and scale effects
- **Utility Classes**: Used throughout for spacing, colors, transforms, and transitions
- **Group Hover**: Interactive card effects that respond to hover states
- **Responsive Design**: Tailwind utilities work seamlessly with Bootstrap's grid system

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- All images are included in the `images/` folder
- External resources (Bootstrap, Google Fonts) are loaded from CDN
- The site is fully static and requires no server-side processing
- All Thymeleaf template syntax has been converted to standard HTML

## Original Project

This static website was converted from a Spring Boot application located at:
`C:\Workdrive\Private\golden\golden`

## License

© 2025 GOLDEN STAPLES. All rights reserved.

