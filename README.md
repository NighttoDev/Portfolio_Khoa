# Portfolio Website - Khoa Tran

A professional, responsive portfolio website built with HTML, CSS, and JavaScript. Designed to showcase skills, education, experience, and contact information for a Backend Web Developer.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Sections**:
  - Hero/Home - Eye-catching introduction
  - About - Personal information and background
  - Education - Academic credentials
  - Experience - Professional work history
  - Skills - Technical proficiencies with visual progress bars
  - Contact - Contact form and information
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Mobile hamburger menu
  - Scroll-to-top button
  - Form validation
  - Scroll animations
  - Typing effect on hero subtitle

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Getting Started

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/Portfolio_Khoa.git
```

2. Navigate to the project directory:
```bash
cd Portfolio_Khoa
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Or using Node.js with live-server
npx live-server
```

## Customization

### Update Personal Information

1. **Edit HTML Content** (`index.html`):
   - Replace "Khoa Tran" with your name
   - Update personal information in the About section
   - Add your education details
   - Add your work experience
   - Update skills and proficiency levels
   - Add your contact information
   - Update social media links

2. **Add Your Images** (`images/` folder):
   - Add `profile.jpg` - Your hero section profile picture (400x400px recommended)
   - Add `about.jpg` - Your about section image (600x800px recommended)

3. **Customize Colors** (`css/style.css`):
   - Edit CSS variables in `:root` section:
```css
:root {
    --primary-color: #3b82f6;    /* Change primary color */
    --secondary-color: #8b5cf6;  /* Change secondary color */
    --accent-color: #10b981;     /* Change accent color */
}
```

### Contact Form Integration

The contact form currently logs data to console. To make it functional:

1. **Option 1: EmailJS**
   - Sign up at [EmailJS](https://www.emailjs.com/)
   - Follow their integration guide
   - Uncomment the fetch code in `js/script.js`

2. **Option 2: FormSubmit**
   - Use [FormSubmit.co](https://formsubmit.co/)
   - Update form action attribute

3. **Option 3: Your Backend API**
   - Create your own backend endpoint
   - Update the fetch URL in `js/script.js`

## Project Structure

```
Portfolio_Khoa/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Image assets
│   ├── profile.jpg     # (Add your profile picture)
│   └── about.jpg       # (Add your about picture)
├── assets/             # Additional assets
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Optimization Tips

1. **Optimize Images**:
   - Compress images using tools like TinyPNG or ImageOptim
   - Use WebP format for better compression
   - Recommended sizes:
     - Profile image: 400x400px
     - About image: 600x800px

2. **Loading Speed**:
   - Already uses CDN for fonts and icons
   - Consider lazy loading images for better performance
   - Minify CSS and JavaScript for production

## Deployment

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Your site will be live at: `https://yourusername.github.io/Portfolio_Khoa/`

### Deploy to Netlify

1. Drag and drop your project folder to [Netlify](https://www.netlify.com/)
2. Or connect your GitHub repository
3. Site will be deployed automatically

### Deploy to Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

## Future Enhancements

- Add a Projects/Portfolio section
- Implement dark mode toggle
- Add blog section
- Integrate backend for contact form
- Add testimonials section
- Include downloadable resume
- Add animations library (AOS, GSAP)
- Implement progressive web app (PWA)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Khoa Tran - your.email@example.com

Portfolio: [https://yourportfolio.com](https://yourportfolio.com)

GitHub: [https://github.com/yourusername](https://github.com/yourusername)

---

**Note**: Remember to replace all placeholder content with your actual information before deploying!
