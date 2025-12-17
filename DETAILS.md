# Portfolio Website - Ankit Kumar

> **Domain**: ankit.cnarte.com  
> **Template**: MyResume v4.7.0 by BootstrapMade  
> **License**: https://bootstrapmade.com/license/  
> **Last Updated**: December 17, 2025

---

## PROJECT OVERVIEW

This is a personal portfolio website for **Ankit Kumar**, a Data Scientist, ML-Ops Engineer, and ML Developer with 4+ years of industry experience. The website showcases professional experience, skills, education, and contact information using a single-page responsive design with smooth scrolling navigation.

**Owner Information:**
- **Name**: Ankit Kumar
- **Role**: Data Scientist, ML-Ops Engineer, ML Developer
- **Location**: Pune, India
- **Email**: ankitkrchy.54@gmail.com
- **Phone**: +91 9939086064
- **LinkedIn**: https://www.linkedin.com/in/cnarte/
- **GitHub**: https://github.com/cnarte
- **Website**: http://cnarte.tech

---

## REPOSITORY STRUCTURE

```
Ankit_cnarte/
├── CNAME                          # Custom domain configuration for GitHub Pages
├── index.html                     # Main portfolio page (single-page application)
├── portfolio-details.html         # Portfolio details template (currently unused)
├── DETAILS.md                     # This documentation file
│
├── assets/                        # All static assets
│   ├── css/                       # Stylesheets
│   │   ├── style.css              # Main custom stylesheet (1050 lines)
│   │   ├── DarkReader-1---0-0-1---00.css  # Dark mode stylesheet
│   │   └── workspace.code-workspace  # VS Code workspace config
│   │
│   ├── img/                       # Images and graphics
│   │   ├── mypic_bw.jpg           # Profile picture (black & white)
│   │   ├── my_pic1.jpg            # Profile picture variant
│   │   ├── pic2.jpg, pic3.gif     # Additional profile images
│   │   ├── *.gif                  # Various animated GIFs for projects
│   │   ├── *.png                  # Project screenshots (SMS app, tic-tac-toe)
│   │   └── *.jpg                  # Background and decorative images
│   │
│   ├── js/                        # JavaScript files
│   │   └── main.js                # Main JavaScript (264 lines) - handles navigation, animations, lightbox
│   │
│   └── vendor/                    # Third-party libraries
│       ├── aos/                   # Animate On Scroll library
│       ├── bootstrap/             # Bootstrap 5 CSS framework
│       ├── bootstrap-icons/       # Bootstrap icon font
│       ├── boxicons/              # Boxicons icon library
│       ├── glightbox/             # Lightbox gallery plugin
│       ├── isotope-layout/        # Masonry layout library
│       ├── php-email-form/        # Email form validation
│       ├── purecounter/           # Number counter animation
│       ├── swiper/                # Touch slider library
│       ├── typed.js/              # Typing animation library
│       └── waypoints/             # Scroll-triggered events
│
└── forms/                         # Server-side form handling
    ├── contact.php                # Contact form PHP handler (requires pro version library)
    └── Readme.txt                 # Form usage instructions

```

---

## FILE PURPOSES

### Root Level Files

**CNAME**
- Contains custom domain: `ankit.cnarte.com`
- Used by GitHub Pages for custom domain routing
- Critical for deployment - do not modify unless changing domain

**index.html** (546 lines)
- Main portfolio single-page application
- Contains all primary sections: Hero, About, Facts, Skills, Resume, Services, Contact
- Fully responsive design with mobile navigation
- Uses data attributes for animation triggers (`data-aos`)

**portfolio-details.html** (113 lines)
- Template for detailed portfolio item pages
- Currently not actively used in navigation
- Contains Swiper slider implementation
- Can be used for future project showcase expansions

---

## WEBSITE SECTIONS

The website is organized as a single-page application with the following sections accessible via smooth-scroll navigation:

### 1. **Hero Section** (`#hero`)
- Full-screen landing section
- Animated typing effect: "Data Scientist, ML-Ops Engineer, ML Developer"
- Social media links (GitHub, LinkedIn)
- Uses Typed.js for text animation

### 2. **About Section** (`#about`)
- Personal introduction and philosophy
- Profile image (mypic_bw.jpg)
- Key personal details:
  - Birthday: 23 Feb 2000
  - Age: 22 (Note: should be updated to 25 as of 2025)
  - Website: http://cnarte.tech
  - Phone: +91 9939086064
  - Email: ankitkrchy.54@gmail.com
  - Location: Pune, India
  - Freelance: Available

### 3. **Facts Section** (`#facts`)
- Animated counters displaying statistics
- 4 years industry experience
- 25+ projects
- 2 awards
- Uses PureCounter.js for number animations

### 4. **Skills Section** (`#skills`)
- Progress bar visualizations for technical skills
- Left column:
  - Python: 100%
  - Tensorflow: 90%
  - Pytorch: 75%
- Right column:
  - Django: 80%
  - WordPress/CMS: 90%
  - JavaScript: 55%

### 5. **Resume Section** (`#resume`)
- **Education:**
  - Bachelor of Engineering (Computer Engineering)
  - Army Institute of Technology, Pune
  - CGPA: 9.27
  - Years: 2019-2023

- **Leadership & Achievements:**
  - Founder of Quantum Computing Club at AIT
  - Taught 100+ students basics of Q-circuits and Qiskit
  - Collaboration with CDAC research team on Q-cryptography

- **Professional Experience:**
  1. **NLP Intern** - Prodigal Technology (Jun 2022 - Aug 2022)
     - Redaction engine for customer service providers
     - Processing 100k+ calls per day
     - 30% pipeline optimization
  
  2. **ML Time Series Intern** - Solytics Partners (Sep 2021 - Jan 2022)
     - Time series model pipelines for financial institutions
     - End-to-end training and deployment
     - Macro and micro economics analysis
  
  3. **AI Intern** - Blue Bricks Pty Ltd (Jun 2021 - Jul 2021)
     - Document parsing and ID verification systems
     - Meta few-shot learning for eKYC
     - Deployed API endpoints
  
  4. **ML Intern** - Solytics Partners (Nov 2020 - May 2021)
     - Financial risk modeling platform
     - Production scripts for Fortune 500 clients
     - 7x optimization of NLP pipeline (used by HSBC)

### 6. **Services Section** (`#services`)
- **NLP Services**: End-to-end NLP pipelines with AWS deployment and serverless inference
- **Computer Vision**: SOTA paper implementations for research and edge deployment with TF-lite
- **ML Support**: Production pipeline development and optimization

### 7. **Contact Section** (`#contact`)
- Contact form with PHP backend
- Email: ankitkrchy.54@gmail.com
- Phone: +91 9939086064
- Form fields: Name, Email, Subject, Message
- Form submits to `forms/contact.php`

---

## TECHNICAL STACK

### Frontend Technologies
- **HTML5**: Semantic markup with accessibility considerations
- **CSS3**: Custom styles + Bootstrap 5 framework
- **JavaScript (ES6+)**: Vanilla JS for interactivity
- **Bootstrap 5**: Responsive grid system and components
- **Font**: Open Sans, Raleway, Poppins (Google Fonts)

### JavaScript Libraries
1. **AOS (Animate On Scroll)**: Scroll-triggered animations
2. **Bootstrap 5**: Component framework
3. **Bootstrap Icons**: Icon library
4. **Boxicons**: Additional icon set
5. **GLightbox**: Image/video lightbox gallery
6. **Isotope**: Masonry grid layout
7. **PureCounter**: Animated number counters
8. **Swiper**: Touch-enabled slider
9. **Typed.js**: Typewriter text effect
10. **Waypoints**: Scroll position detection

### Backend
- **PHP**: Contact form processing (requires pro version library)
- **Static Hosting**: GitHub Pages compatible

---

## KEY FEATURES

### Navigation
- Fixed sidebar navigation on desktop
- Mobile hamburger menu toggle
- Smooth scrolling to sections
- Active state highlighting based on scroll position

### Animations
- Fade-in effects on scroll (AOS library)
- Typing animation in hero section (Typed.js)
- Number counting animations (PureCounter)
- Progress bar animations
- Zoom-in effects on service cards

### Responsive Design
- Mobile-first approach
- Breakpoints: `xl` (desktop), `lg`, `md`, `sm` (mobile)
- Mobile navigation toggle at `xl` breakpoint
- Responsive grid layouts using Bootstrap

### Performance Optimizations
- Minified vendor libraries (`.min.css`, `.min.js`)
- Lazy loading images with AOS
- Efficient DOM manipulation with vanilla JS
- Preloader for initial page load

---

## CONFIGURATION & CUSTOMIZATION

### Updating Personal Information
**Location**: [index.html](index.html#L100-L110)
- Modify About section for personal details
- Update social links in Hero section (lines 68-72)
- Update footer links (line 524)

### Updating Skills
**Location**: [index.html](index.html#L170-L220)
- Modify skill names and percentages
- Update `aria-valuenow` attributes to match percentages

### Updating Experience
**Location**: [index.html](index.html#L240-L330)
- Add/remove resume items in `.resume-item` divs
- Follow existing HTML structure for consistency

### Updating Services
**Location**: [index.html](index.html#L370-L480)
- Modify `.icon-box` containers
- Change icons by updating Boxicons classes

### Styling Customization
**Location**: [assets/css/style.css](assets/css/style.css)
- Primary color: `#0563bb` (line 17)
- Hover color: `#067ded` (line 22)
- Font families: Open Sans (body), Raleway (headings)
- 1050 lines of custom CSS organized by sections

---

## JAVASCRIPT FUNCTIONALITY

### Main.js Components

1. **Navigation**
   - Mobile nav toggle
   - Active state management on scroll
   - Smooth scrolling to anchors

2. **Header Behavior**
   - Fixed header on scroll
   - Collapse mobile nav on link click

3. **Animations**
   - AOS initialization (duration: 1000ms, easing: ease-in-out)
   - Typed.js for hero section typing effect
   - PureCounter for statistics

4. **Portfolio**
   - Isotope layout for filtering
   - GLightbox for image galleries
   - Swiper for detail sliders

5. **Utilities**
   - Back-to-top button with scroll threshold
   - Preloader on page load
   - Form validation (via vendor library)

---

## DEPLOYMENT

### GitHub Pages Setup
1. Repository must be public
2. CNAME file configures custom domain: `ankit.cnarte.com`
3. DNS settings must point to GitHub Pages servers
4. All paths are relative for portability

### Local Development
1. No build process required (static site)
2. Can be opened directly in browser
3. PHP form requires local server (XAMPP, MAMP, etc.)
4. For PHP testing: `php -S localhost:8000`

### Production Considerations
- Contact form requires PHP Email Form Pro library (not included)
- Update email address in `forms/contact.php` (line 10)
- Configure SMTP settings if needed (lines 27-34 in contact.php)
- Ensure all image paths are correct
- Test responsive design across devices

---

## ASSET MANAGEMENT

### Images
**Location**: [assets/img/](assets/img/)
- **Profile**: mypic_bw.jpg (primary), my_pic1.jpg (alternate)
- **Projects**: Various GIFs and PNGs for project demos
- **Decorative**: Background images and animations

### Icon Libraries
1. **Bootstrap Icons**: General UI icons
2. **Boxicons**: Social media and service icons
3. Font-based icons (scalable, customizable via CSS)

### CSS Organization
**Main Stylesheet** ([assets/css/style.css](assets/css/style.css)):
- General styles (body, links, headings)
- Back-to-top button
- Header/navigation
- Sections (hero, about, facts, skills, resume, etc.)
- Media queries for responsive design

---

## KNOWN ISSUES & TODO

### Issues
1. Age in About section needs updating (currently shows 22, should be 25)
2. Contact form email has typo: missing closing tag `<p>ankitkrchy.54@gmail.com/p>` (should be `</p>`)
3. PHP Email Form library not included (pro version required)
4. portfolio-details.html page not linked in navigation

### Potential Improvements
1. Add actual portfolio projects with working links
2. Implement blog section
3. Add testimonials section with real content
4. Integrate analytics (Google Analytics)
5. Add meta descriptions and OG tags for SEO
6. Implement dark mode toggle
7. Add more project images and case studies
8. Create dynamic portfolio filtering
9. Add download CV button
10. Implement working contact form backend

---

## MAINTENANCE GUIDE

### Regular Updates
1. **Experience**: Update years of experience counter annually
2. **Age**: Update age in About section on birthday (Feb 23)
3. **Projects**: Increment project count as completed
4. **Skills**: Adjust skill percentages as proficiency grows

### Content Updates
- All content is in `index.html`
- No database or CMS required
- Direct HTML editing
- Git commit after changes for version control

### Adding New Sections
1. Create HTML structure in `index.html`
2. Add corresponding CSS in `assets/css/style.css`
3. Update navigation menu in header
4. Test responsiveness across breakpoints

---

## BROWSER COMPATIBILITY

- **Chrome**: Full support ✓
- **Firefox**: Full support ✓
- **Safari**: Full support ✓
- **Edge**: Full support ✓
- **IE11**: Partial support (vendor prefixes may be needed)

### Required Browser Features
- CSS Grid & Flexbox
- ES6 JavaScript
- CSS Animations
- Intersection Observer (for AOS)
- Smooth scrolling behavior

---

## VENDOR LIBRARY VERSIONS

- **Bootstrap**: 5.x
- **AOS**: Latest
- **Swiper**: 8.x
- **GLightbox**: 3.x
- **Typed.js**: 2.x
- **PureCounter**: Latest
- **Isotope**: 3.x
- **Waypoints**: 4.x

All vendor libraries are included locally (not via CDN) for offline functionality and version stability.

---

## CONTACT FORM SETUP

### Current Status
- Form HTML is in place
- PHP handler exists but requires pro library
- Validation JavaScript included

### Setup Requirements
1. Purchase PHP Email Form Pro from BootstrapMade
2. Place library at: `assets/vendor/php-email-form/php-email-form.php`
3. Update receiving email in `forms/contact.php` (line 10)
4. Configure SMTP if needed (optional)

### Alternative Solutions
- Use Formspree (https://formspree.io)
- Use Netlify Forms
- Use EmailJS (JavaScript-based)
- Implement custom backend API

---

## SEO CONSIDERATIONS

### Current Implementation
- Basic meta tags present (viewport, charset)
- Title tag: "Ankit Kumar"
- Empty description and keywords meta tags

### Recommendations
1. Add meaningful meta description
2. Add relevant keywords
3. Implement Open Graph tags for social sharing
4. Add Twitter Card meta tags
5. Create sitemap.xml
6. Add robots.txt
7. Implement structured data (Schema.org)

---

## ACCESSIBILITY

### Current Features
- Semantic HTML5 elements
- ARIA attributes on progress bars
- Alt text on images (needs verification)
- Keyboard navigation support
- Focus states on interactive elements

### Improvements Needed
- Add skip navigation link
- Ensure all images have descriptive alt text
- Add ARIA labels to icon-only buttons
- Test with screen readers
- Ensure color contrast ratios meet WCAG AA standards

---

## PERFORMANCE OPTIMIZATION

### Current Optimizations
- Minified vendor files
- Lazy loading with AOS
- Preloader for smooth initial load
- Efficient vanilla JavaScript

### Further Optimizations
- Compress images (WebP format)
- Implement lazy loading for images
- Defer non-critical JavaScript
- Minimize CSS (currently unminified)
- Enable browser caching via .htaccess
- Consider CDN for vendor libraries

---

## VERSION CONTROL

### Git Workflow
- Main branch for production
- Feature branches for new sections
- Commit messages should be descriptive
- Tag releases for major updates

### Deployment Process
1. Make changes locally
2. Test across browsers
3. Commit to Git
4. Push to GitHub
5. GitHub Pages auto-deploys
6. Verify live site

---

## AGENT INSTRUCTIONS

When working with this repository:

1. **Content Updates**: All content is in `index.html` - search for section IDs to locate specific areas
2. **Styling**: Check `assets/css/style.css` - organized by section with clear comments
3. **JavaScript**: Main functionality in `assets/js/main.js` - well-commented code
4. **Images**: Use existing images in `assets/img/` or add new ones to this directory
5. **Testing**: Open `index.html` in browser, no build step needed
6. **Forms**: Contact form requires PHP server and pro library
7. **Responsive**: Always test changes at different breakpoints (mobile, tablet, desktop)
8. **Icons**: Use Boxicons or Bootstrap Icons classes, documentation available online
9. **Colors**: Primary brand color is `#0563bb`, maintain consistency
10. **Navigation**: Update both desktop (#navbar) and mobile nav when adding sections

### Common Modifications
- **Add skill**: Duplicate `.progress` div in Skills section
- **Add experience**: Duplicate `.resume-item` in Resume section
- **Change colors**: Search and replace hex codes in style.css
- **Update stats**: Modify `data-purecounter-end` values in Facts section
- **Add service**: Duplicate `.icon-box` in Services section

---

## SUPPORT & DOCUMENTATION

- **Template Docs**: https://bootstrapmade.com/free-html-bootstrap-template-my-resume/
- **Bootstrap Docs**: https://getbootstrap.com/docs/5.0/
- **AOS Docs**: https://michalsnik.github.io/aos/
- **Swiper Docs**: https://swiperjs.com/
- **Typed.js Docs**: https://mattboldt.com/demos/typed-js/

---

## LICENSE

Template: MyResume v4.7.0 by BootstrapMade  
License: https://bootstrapmade.com/license/  
Content: © Ankit Kumar

---

*This documentation was generated on December 17, 2025. For questions or updates, contact ankitkrchy.54@gmail.com*
