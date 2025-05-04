# 🎨 Omar Faisal - Design Portfolio

<div align="center">
  <img src="https://via.placeholder.com/1200x400?text=UI/UX+Design+Portfolio" alt="Design Portfolio Banner" />
  <p><em>Crafting digital experiences that delight and inspire</em></p>
</div>

## ✨ About This Project

This portfolio website showcases the creative work and professional journey of Omar Faisal, a UI/UX Designer and Front-end Developer. Built with a focus on accessibility, aesthetics, and user experience, the site serves as both a demonstration of design skills and a practical example of modern web development techniques.

### 🌗 Unique Features

- **Theme Switcher**: Toggle between light and dark modes based on user preference
- **Sidebar Navigation**: Elegant and accessible navigation system
- **Tabbed Content**: Dynamic content presentation in the About section
- **Portfolio Filtering**: Interactive project filtering by category
- **Testimonial Slider**: Showcase client feedback with an interactive slider
- **Timeline Display**: Visual representation of education and work experience

## 🛠️ Built With

- **Semantic HTML5** - For accessible and SEO-friendly markup
- **Custom CSS3** - Including CSS variables, Flexbox, and Grid
- **Vanilla JavaScript** - For interactive components (no frameworks)
- **CSS Animations** - For engaging user interactions
- **Responsive Design** - Mobile-first approach for all devices
- **Local Storage API** - To persist user theme preferences

## 📋 Page Sections

| Section       | Description                                         |
|---------------|-----------------------------------------------------|
| Home          | Introduction and primary call-to-action             |
| About         | Professional background with tabbed information     |
| Services      | Design and development services offered             |
| Portfolio     | Gallery of projects with filtering capability       |
| Testimonials  | Client feedback and recommendations                 |
| Contact       | Contact information and inquiry form                |

## 📱 Responsive Design

This portfolio implements a comprehensive responsive strategy:

- **Mobile** (< 576px): Single column layout, optimized for touch
- **Tablet** (576px - 768px): Adjusted navigation and two-column grid
- **Desktop** (> 768px): Full sidebar navigation and multi-column layouts

## 🚀 Getting Started

1. **Download the files**
   ```
   git clone https://github.com/username/omar-portfolio.git
   ```

2. **Open the project**
   ```
   cd omar-portfolio
   ```

3. **View in browser**
   - Open `index.html` in your preferred browser
   - Or use a local development server:
     ```
     npx serve .
     ```

## 💡 Code Highlights

### Theme Switching Functionality
```javascript
function switchTheme(e) {
    if (e.target.checked) {
        document.documentElement.setAttribute('data-theme', 'dark');
        localStorage.setItem('theme', 'dark');
    } else {
        document.documentElement.setAttribute('data-theme', 'light');
        localStorage.setItem('theme', 'light');
    }
}
```

### CSS Variables for Theming
```css
:root {
    --primary-color: #6c5ce7;
    --secondary-color: #a29bfe;
    --bg-color: #ffffff;
    /* Additional variables... */
}

[data-theme="dark"] {
    --primary-color: #7e72e8;
    --bg-color: #121212;
    /* Dark theme overrides... */
}
```

## 👤 About the Developer

Omar Faisal is a UI/UX Designer and Front-end Developer with over 7 years of experience creating intuitive and engaging digital experiences. Specializing in user-centered design and creative problem-solving, Omar brings a unique blend of technical knowledge and aesthetic sensibility to every project.

- **Email:** [OmarFaisal.Alrwabdah@my-aolcc.com](mailto:OmarFaisal.Alrwabdah@my-aolcc.com)
- **Location:** Vancouver, Canada

## 📝 Future Enhancements

- [ ] Add blog section for design articles
- [ ] Implement case studies for major projects
- [ ] Create downloadable resources for other designers
- [ ] Add multilingual support
- [ ] Integrate a design process visualization

## 📜 License & Attribution

- Developed by Omar Faisal Hussein Alrwabdah
- Font Awesome icons used under their free license
- Google Fonts: Raleway
- Placeholder images courtesy of placeholder.com

---

<div align="center">
  <p>© 2023 Omar Faisal Hussein Alrwabdah. All rights reserved.</p>
</div> 