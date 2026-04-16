# OKEYODEV | Bootstrap 5 Landing Page

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## 📋 Project Overview

A modern, responsive web development course landing page built with **Bootstrap 5**. This project demonstrates practical implementation of Bootstrap components, responsive design patterns, and professional CSS customization techniques.

This landing page serves as a showcase for an online web development course offering training in full-stack technologies including ReactJS, NodeJS, ExpressJS, MongoDB, and Next.js.

## 📸 Demo & Live Preview

### Screenshot

![OKEYODEV Landing Page](screenshot-bs-hw.png.)



### 🌐 Live Demo Link

**Coming Soon**: [View Live Demo](https://yourusername.github.io/hero-bootstrap-landing-page)



---

## ✨ Key Features

- **Responsive Navigation Bar** - Mobile-friendly navbar with collapse functionality
- **Hero Section** - Eye-catching showcase with call-to-action button
- **Registration Modal** - Interactive form modal for user registration
- **Newsletter Signup** - Email collection section with integrated form
- **Feature Cards** - Three-column grid showcasing course benefits (Virtual, Project-Based, Certificates)
- **Course Information Sections** - Detailed content about learning pathways and technologies
- **Instructor Section** - Display of course instructors with ratings
- **Professional Color Scheme** - Custom CSS color system with teal and charcoal palette
- **Smooth Animations** - Hover effects on cards and links for enhanced UX
- **Mobile Optimized** - Fully responsive design for all device sizes

## 🛠️ Technologies Used

| Technology      | Version | Purpose                             |
| --------------- | ------- | ----------------------------------- |
| HTML5           | Latest  | Structure and semantic markup       |
| CSS3            | -       | Styling and custom color system     |
| Bootstrap       | 5.0.2   | Responsive framework and components |
| Bootstrap Icons | 1.3.0   | Icon library for visual elements    |

## 🎨 Color Customization

This project uses a custom CSS variable system for easy color management. All colors are defined in `css/syle.css` and can be modified in the `:root` selector:

```css
:root {
  --primary-color: #0d7377; /* Teal - Main actions */
  --accent-color: #e8a537; /* Warm gold - Highlights */
  --secondary-color: #2c3e50; /* Charcoal - Secondary elements */
  --dark-bg: #1a1a1a; /* Deep dark - Backgrounds */
}
```

To change the entire theme, simply modify these variables. Bootstrap utilities will automatically update throughout the site.

## 📂 Project Structure

```
hero-bootstrap-landing-page/
│
├── index.html              # Main HTML file with all sections
├── css/
│   └── syle.css           # Custom styles and Bootstrap overrides
├── image/                 # Image assets folder
│   ├── img_vic.png        # Profile/hero image
│   └── 4403-removebg-preview.png  # Supporting imagery
│
└── README.md              # Project documentation (this file)
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code, Sublime Text, etc.)
- Basic understanding of HTML, CSS, and Bootstrap

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/hero-bootstrap-landing-page.git
   cd hero-bootstrap-landing-page
   ```

2. **Open the project**
   - Simply double-click `index.html` in your file explorer, OR
   - Use a local server (recommended for better performance):

     ```bash
     # If you have Python 3 installed
     python -m http.server 8000

     # Then open http://localhost:8000 in your browser
     ```

3. **View the site**
   - Open `index.html` in your preferred web browser

## 💻 How to Use

### Navigation

- Click the navbar brand "OKEYODEV" to navigate (currently links to home)
- Use navigation menu items to scroll to sections:
  - **What you'll learn** - Course curriculum highlights
  - **Question** - FAQ section
  - **Instructors** - Meet your teachers

### Registration

- Click the "Register Now!" button to open the registration modal
- Fill in your details (First Name, Last Name, Email, Phone Number)
- Submit to register for the course

### Newsletter

- Enter your email in the "Sign Up for Our Newsletter" section
- Click the button to subscribe

## 🎓 Learning Outcomes

By studying this project, you'll understand:

1. **Bootstrap Grid System** - Responsive column layouts with `container`, `row`, and `col-*` classes
2. **Bootstrap Components** - Navbars, modals, forms, cards, buttons
3. **Responsive Design** - Mobile-first approach with `d-md-flex`, media queries
4. **CSS Customization** - Overriding Bootstrap defaults professionally
5. **CSS Variables** - Using custom properties for maintainable styling
6. **Form Handling** - Floating labels and form validation patterns
7. **Accessibility** - Semantic HTML and ARIA attributes

## 🎨 Customization Guide

### Changing Colors

1. Open `css/syle.css`
2. Modify values in the `:root` CSS variables section
3. Changes apply globally throughout the site

### Updating Content

1. Edit text directly in `index.html`
2. Ensure you maintain proper HTML structure
3. Test on mobile devices after changes

### Replacing Images

1. Add your images to the `image/` folder
2. Update image paths in `index.html`:
   ```html
   <img src="image/your-image.png" alt="Description" />
   ```

## 📚 Lessons Applied

This project was developed following **Hero World Technology's Bootstrap 5 course**, with the following enhancements:

- ✅ Custom color palette implementation
- ✅ Custom image integration
- ✅ Professional CSS systen with variables
- ✅ Enhanced hover effects and transitions
- ✅ Improved form styling

## 🔗 Resources & Credits

- **Course Inspiration**: Hero World Technology Bootstrap 5 Lesson
- **Bootstrap Documentation**: [getbootstrap.com](https://getbootstrap.com)
- **Bootstrap Icons**: [icons.getbootstrap.com](https://icons.getbootstrap.com)
- **Color Palette Generator**: Use tools like [coolors.co](https://coolors.co) for future projects

## 📝 Notes for Developers

### Best Practices Implemented

- ✓ Semantic HTML5 markup
- ✓ Mobile-first responsive design
- ✓ CSS custom properties for maintainability
- ✓ Minimal and organized CSS
- ✓ Proper use of Bootstrap utility classes
- ✓ Accessibility considerations (alt text, ARIA labels)

### Future Enhancement Ideas

- Add JavaScript for form validation
- Implement sending registration data to backend
- Add smooth scroll navigation
- Create instructor detail pages
- Add testimonials section
- Implement dark mode toggle
- Add animation library (AOS.js)

## 🐛 Known Issues

- Modal form does not currently submit data (backend integration needed)
- Links in navigation are placeholder links
- Forms require backend setup for data persistence

## 📄 License

This project is open source and available under the MIT License. See the LICENSE file for more information.

## 👤 Author

**Your Name**

- GitHub: [@yourusername](https://github.com/yourusername)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/hero-bootstrap-landing-page/issues).

## 📞 Support

If you found this project helpful, please consider:

- ⭐ Giving it a star on GitHub
- 🔗 Sharing it with other developers learning Bootstrap
- 📝 Leaving feedback or suggestions

---

**Last Updated**: April 2026 | **Version**: 1.0.0
