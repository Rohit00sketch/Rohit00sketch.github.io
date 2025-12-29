# Rohit Kumar - Data Scientist Portfolio

A modern, professional portfolio website showcasing data science projects, skills, and experience.

## 🚀 Features

- **Clean & Modern Design**: Professional aesthetic optimized for hiring managers and recruiters
- **Dark/Light Mode**: Toggle between themes for comfortable viewing
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Animations**: Subtle animations that enhance user experience without being distracting
- **Dashboard-style Sections**: Visual representations of skills and project outcomes
- **Performance Optimized**: Fast loading with lazy loading and debounced scroll events
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Accessible**: Keyboard navigation and ARIA labels

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with animated data visualization
2. **About**: Professional summary highlighting business impact and technical depth
3. **Projects**: 6 featured projects with problem statements, approaches, and measurable outcomes
4. **Skills Dashboard**: Visual representation of technical expertise across different domains
5. **Experience Timeline**: Professional journey with achievements and responsibilities
6. **Coding Profiles**: Links to GitHub, LinkedIn, and LeetCode
7. **Contact**: Simple, recruiter-friendly contact section with form

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

## 📦 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── styles.css              # All styles with responsive design
├── script.js               # Interactive functionality
├── Rohit_kumar_DataScientist.pdf  # Resume file
└── README.md               # This file
```

## 🎨 Customization Guide

### Update Personal Information

1. **Hero Section** (`index.html` lines 40-70):
   - Update name, role, and value proposition
   - Update social media links

2. **About Section** (`index.html` lines 82-135):
   - Customize professional summary
   - Update statistics (years, projects, LeetCode count)

3. **Projects** (`index.html` lines 147-450):
   - Replace with your actual projects
   - Update problem statements, metrics, and tech stacks
   - Add real GitHub/demo links

4. **Skills** (`index.html` lines 461-620):
   - Adjust skill levels and progress bars
   - Add or remove technologies

5. **Experience** (`index.html` lines 632-750):
   - Update with your actual work experience
   - Modify achievements and tech stacks

6. **Contact** (`index.html` lines 814-880):
   - Update email address
   - Connect form to backend (currently console logs only)

### Styling Customization

All colors and spacing are controlled via CSS variables in `styles.css` (lines 1-40):

```css
:root {
    --accent-primary: #2563eb;      /* Primary brand color */
    --accent-secondary: #3b82f6;    /* Secondary brand color */
    --accent-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* ... more variables */
}
```

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Update** personal information and project details
3. **Replace** `Rohit_kumar_DataScientist.pdf` with your resume
4. **Open** `index.html` in a browser to preview
5. **Deploy** to your preferred hosting platform

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a repository named `username.github.io`
2. Push your code
3. Enable GitHub Pages in repository settings

### Netlify (Free)
1. Drag and drop your folder to Netlify
2. Your site is live instantly

### Vercel (Free)
1. Import your GitHub repository
2. Deploy with one click

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Tips

- Images are lazy-loaded
- Scroll events are debounced
- CSS animations use `transform` and `opacity` for better performance
- Minimal external dependencies

## 🎯 Target Audience

This portfolio is specifically designed for:
- Hiring Managers at product-based companies
- Technical Recruiters
- Senior Engineers evaluating candidates
- Anyone looking to understand your data science capabilities

## 📈 Key Messaging

The portfolio emphasizes:
- **Credibility**: Real projects with measurable outcomes
- **Clarity**: Clear problem statements and approaches
- **Impact**: Business value and technical depth
- **Readiness**: Signals "ready for ownership" not "student portfolio"

## 🔧 Future Enhancements

- [ ] Add case study pages for detailed project walkthroughs
- [ ] Integrate blog section for technical articles
- [ ] Connect contact form to backend service (EmailJS, Formspree, etc.)
- [ ] Add PWA support with service worker
- [ ] Implement analytics (Google Analytics, Plausible)
- [ ] Add automated testing

## 📝 License

This portfolio template is free to use and customize for your personal use.

## 🤝 Connect

- **GitHub**: [https://github.com/Rohit00sketch](https://github.com/Rohit00sketch)
- **LinkedIn**: [https://www.linkedin.com/in/rohit-kumar-mlds/](https://www.linkedin.com/in/rohit-kumar-mlds/)
- **LeetCode**: [Your LeetCode Profile]

---

**Built with ❤️ for data science professionals**

*Last Updated: December 2025*
