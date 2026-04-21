# Sofa - Software & Interaction Design

A modern, responsive landing page for Sofa, a creative software and interaction design company based in Amsterdam. This project showcases clean, semantic HTML and modern CSS techniques to create an elegant web presence.

## Live Demo

View the live site: [sofa.martinmaina.dev](https://sofa.martinmaina.dev)

## Preview

![Sofa Website Preview](Sofa%20webpage.JPG)

## About the Project

Sofa represents a fictive design agency that develops innovative products and helps others design theirs. This landing page was created as a portfolio piece to demonstrate proficiency in:

- Semantic HTML5 markup
- Modern CSS techniques and responsive design
- Web accessibility standards
- SEO optimization
- Clean, maintainable code structure

## Features

- **Fully Responsive Design**: Optimized layouts for mobile, tablet, and desktop devices
- **Semantic HTML5**: Proper use of semantic elements for better accessibility and SEO
- **Modern CSS**: 
  - CSS Custom Properties for easy theming
  - CSS Grid for responsive layouts
  - Smooth transitions and hover effects
  - Mobile-first responsive design approach
- **Accessibility**: ARIA labels, alt text, and keyboard navigation support
- **SEO Optimized**: Comprehensive meta tags including Open Graph for social sharing
- **Performance**: Lightweight, no dependencies, fast loading times

## Technologies Used

- HTML5
- CSS3
- Git for version control

## Project Structure

```
sofa/
├── Images/
│   ├── Arrow.png          # Navigation card icon
│   ├── Kaleidoscope.png   # Footer app icon
│   └── Sofa.png          # Company logo
├── index.html            # Main HTML file
├── styles.css            # Stylesheet with modern CSS
├── Sofa webpage.JPG      # Screenshot for documentation
├── Sofaset.jpg          # Additional asset
└── README.md            # Project documentation
```

## Getting Started

### Prerequisites

No special prerequisites required. You just need a modern web browser.

### Installation

1. Clone the repository
```bash
git clone https://github.com/Martin888Maina/sofa.git
```

2. Navigate to the project directory
```bash
cd sofa
```

3. Open `index.html` in your browser
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or simply drag and drop the `index.html` file into your browser.

### Deployment

The site is deployed on a DigitalOcean Droplet and served by Nginx at [sofa.martinmaina.dev](https://sofa.martinmaina.dev). HTTPS is provided by a Let's Encrypt certificate with automatic renewal.

Because the project is a static HTML/CSS page, deployment is just a `git clone` of this repository onto the server, a small Nginx server block pointing `root` at the clone, and `certbot --nginx` to issue the certificate.

## Development Journey

This project evolved from a basic HTML/CSS layout to a modern, professional website. Key improvements included:

- **Semantic Structure**: Migrated from div-heavy markup to semantic HTML5 elements
- **Responsive Design**: Implemented CSS Grid and media queries for fluid layouts across all devices
- **Maintainability**: Introduced CSS custom properties for consistent theming
- **Accessibility**: Added ARIA labels and proper alt text for screen reader support
- **Modern CSS**: Utilized contemporary techniques like `clamp()` for fluid typography

## Browser Support

This website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

Potential improvements for future iterations:

- Add interactive navigation with smooth scrolling to sections
- Implement a blog section with article cards
- Create individual pages for Software, Design, Company, and Blog sections
- Add a contact form with validation
- Integrate animations using CSS animations or a lightweight library
- Implement dark mode toggle
- Add project portfolio showcases

## Learning Outcomes

Key web development concepts demonstrated:

- Semantic HTML for better structure and accessibility
- CSS Grid and Flexbox for modern layouts
- Responsive design principles and mobile-first approach
- CSS custom properties for maintainable stylesheets
- SEO best practices and meta tag optimization
- Version control with Git using incremental, logical commits

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Project Link: [https://github.com/Martin888Maina/Sofa](https://github.com/Martin888Maina/Sofa)

---

**Note**: This is a portfolio project created to demonstrate front-end development skills. Sofa is a fictive company used for educational purposes.
