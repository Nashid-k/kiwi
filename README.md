# Kiwi Ice Cream - Static Website

A pixel-perfect clone of the Kiwi Ice Cream marketing website (https://kiwiicecreams.com/), built with pure HTML5 and CSS3.

## Features

- **Fully Responsive Design**: Works seamlessly across all devices (desktop, tablet, mobile)
- **Modern CSS3**: Utilizes flexbox, grid, CSS variables, and smooth animations
- **Google Fonts**: Uses Poppins, Questrial, Quicksand, and Montserrat fonts
- **Hotlinked Images**: All images are loaded directly from the original Kiwi Ice Cream CDN
- **CSS Animations**: Includes fade-ins, slide effects, hover transitions, and floating animations
- **No JavaScript**: Pure CSS interactions and animations
- **Semantic HTML**: Clean, accessible markup structure

## Technologies

- HTML5
- CSS3
- Google Fonts API

## Structure

```
.
├── index.html          # Main HTML file with all page sections
├── style.css           # Complete styling with animations and responsive design
├── README.md           # Project documentation
└── .gitignore         # Git ignore rules
```

## Sections

1. **Header/Navigation**: Fixed header with logo and navigation menu
2. **Hero Section**: Main banner with headline, description, and CTA button
3. **Promo Banner**: Full-width promotional image with overlay button
4. **Motto Section**: Company philosophy and values
5. **Video Section**: Embedded YouTube video showcase
6. **Taste Section**: Product features and benefits
7. **Products Section**: Ice cream flavors grid with product cards
8. **Journey Section**: Blog/news posts gallery
9. **Newsletter Section**: Email subscription form
10. **Footer**: Multi-column footer with company information and links

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Laptop**: 992px - 1199px
- **Tablet**: 768px - 991px
- **Mobile**: 480px - 767px
- **Small Mobile**: 479px and below

## Color Palette

- Primary (Pink): `#F44571`
- Secondary (Yellow): `#FFD046`
- Dark Blue: `#0B1E3F`
- Navy Blue: `#073662`
- Text Dark: `#111F3D`
- Text Gray: `#6E6E6E`

## Typography

- **Primary**: Poppins (headings, buttons, features)
- **Secondary**: Questrial (body text, descriptions)
- **Tertiary**: Quicksand (decorative elements)
- **Additional**: Montserrat (accent text)

## Animations

- **Header**: Slide-down entrance animation
- **Hero**: Fade-in-up for content, floating effect for product images
- **Sections**: Staggered fade-in effects on scroll
- **Buttons**: Hover effects with color transitions and elevation
- **Images**: Scale and rotation effects on hover
- **Cards**: Lift effect on hover with shadow transitions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Development

To view the site locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Assets

All images and media are hotlinked from the original Kiwi Ice Cream CDN:
- Logo: `https://kiwiicecreams.com/wp-content/uploads/2025/10/logo-white-2.webp`
- Favicon: `https://kiwiicecreams.com/wp-content/uploads/2025/10/favicon-150x150.jpg`
- Product images (updated): `https://kiwiicecreams.com/wp-content/uploads/2022/03/...`
  - Pistachio: Pistachio-293x293.jpg
  - Vanilla: Vanilla-293x293.jpg
  - Strawberry: Strawberry-293x293.jpg
  - Pineapple: Pineapple-293x293.jpg
- Decorative graphics: `https://kiwiicecreams.com/wp-content/uploads/2020/06/...`
  - Hero: Group-7573.png
  - Banner: Mask-Group-5.png
  - Motto: Group-125.png
  - Taste section: Group-4.png
  - Blog/Journey: Blog-01-970x1049.jpg, Blog-02-970x1049.jpg
  - Newsletter: Group-5.png, Group-6.png

## License

This is a clone project created for educational purposes. All rights to the original design and branding belong to Kiwi Ice Creams / E.K. Foods Pvt. Ltd.

## Credits

- Original Design: Foxiom Leads
- Original Website: https://kiwiicecreams.com/
- Company: E.K. Foods Pvt. Ltd, Kerala, India
