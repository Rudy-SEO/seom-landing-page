# SEO Marketing Landing Page

A modern, responsive landing page template for an AI-powered SEO marketing agency. Built with HTML5, CSS3, and vanilla JavaScript.

## Features

- Responsive design using CSS Grid and Flexbox
- Modern UI with smooth animations and transitions
- Interactive FAQ section
- Contact form with validation
- Mobile-friendly navigation
- Optimized for SEO with proper meta tags and semantic HTML

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/Rudy-SEO/seom-landing-page.git
cd seom-landing-page
```

2. Open the project:
- Open `index.html` directly in your browser
- Or serve it using a local development server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve
```

3. View the site:
- If opening directly: open `index.html` in your browser
- If using a server: visit `http://localhost:8000`

## Project Structure

```
seom-landing-page/
├── index.html          # Main HTML file
├── css/               # CSS styles
│   └── styles.css     # Main stylesheet
├── js/                # JavaScript files
│   └── main.js        # Main JavaScript file
└── README.md          # Project documentation
```

## Customization

### Colors
The color scheme is defined using CSS variables in the `:root` selector:
```css
:root {
    --deep-navy: #0B1F41;
    --electric-blue: #0073E6;
    --vibrant-cyan: #00C3FF;
    --white: #FFFFFF;
    --light-gray: #F5F7FA;
    --dark-gray: #333333;
}
```

### Typography
The site uses Google Fonts:
- Montserrat: Headers and navigation
- Roboto: Body text

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.