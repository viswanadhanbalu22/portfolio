# Personal Portfolio Website

A modern, responsive personal portfolio website for **Viswanadhan Balu - Full Stack Developer**.

## 🚀 Features

- **Fully Responsive Design** - Mobile-first approach, works seamlessly on all devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Resume Download** - Download button in header and hero section
- **Pure HTML & CSS** - No JavaScript frameworks required
- **Fast Loading** - Lightweight and optimized
- **SEO Friendly** - Semantic HTML structure
- **Modern Color Scheme** - Professional teal/cyan theme

## 📁 Project Structure

```
portfolio-website/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── assets/             # Assets folder
│   └── resume.pdf      # Resume PDF file (replace with your actual resume)
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox & Grid
- **Google Fonts** - Poppins font family
- **CSS Variables** - For consistent theming
- **CSS Animations** - Smooth transitions and effects

## 📋 Sections Included

1. **Header** - Fixed navigation with smooth scroll and resume download button
2. **Hero Section** - Eye-catching introduction with call-to-action buttons and resume download
3. **About** - Personal introduction and background
4. **Skills** - Grid layout showcasing core competencies
5. **Experience** - Timeline-style professional experience
6. **Projects** - Featured projects with technology tags
7. **Education** - Academic background
8. **Contact** - Contact information with clickable links
9. **Footer** - Copyright and credits

## 🎨 Design Features

- **Color Palette**: Modern Teal/Cyan theme (#14b8a6, #0891b2, #06b6d4)
- **Typography**: Poppins font family for modern look
- **Layout**: Card-based design with shadows and hover effects
- **Resume Download**: Prominent download buttons in header and hero section
- **Responsive Breakpoints**:
  - Mobile: Up to 640px
  - Tablet: 641px to 1024px
  - Desktop: 1025px and above

## 🚀 How to Run

### Option 1: Direct File Opening
1. Navigate to the `portfolio-website` folder
2. Double-click `index.html` to open in your default browser

### Option 2: Using a Local Server (Recommended)

#### Using Python:
```bash
# Python 3
cd portfolio-website
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js (http-server):
```bash
# Install http-server globally (if not installed)
npm install -g http-server

# Navigate to folder and start server
cd portfolio-website
http-server -p 8000
```

#### Using PHP:
```bash
cd portfolio-website
php -S localhost:8000
```

Then open your browser and navigate to:
- `http://localhost:8000` (for Python/PHP)
- `http://localhost:8080` (for http-server)

### Option 3: Using VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... other colors */
}
```

### Updating Content
Edit the content directly in `index.html`:
- Personal information in the Hero section
- Skills in the Skills section
- Experience details in the Experience section
- Projects in the Projects section

### Adding Resume PDF
1. Save your resume as `resume.pdf`
2. Place it in the `assets/` folder (replace the placeholder file)
3. The download links in the header and hero section will automatically work

### Adding Images
1. Place images in the `assets/` folder
2. Update the HTML to reference the image paths
3. Example: `<img src="assets/profile.jpg" alt="Profile">`

## 📝 Notes

- All icons are currently using emojis for simplicity
- The design is fully responsive and mobile-friendly
- Smooth scroll behavior is enabled for navigation
- All links are functional (phone, email, LinkedIn)

## 📄 License

This portfolio template is free to use and modify for personal or commercial projects.

## 👤 Contact

**Viswanadhan Balu**
- 📧 Email: viswanadhanbalu@gmail.com
- 📞 Phone: +91 6369885947
- 💼 LinkedIn: [viswanadhanbalu22](https://www.linkedin.com/in/viswanadhanbalu22)
- 📍 Location: Erode, Tamil Nadu, India

---

**Built with ❤️ using HTML & CSS**

