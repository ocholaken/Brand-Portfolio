# Kenneth Ochola - Portfolio Website

A modern, responsive portfolio website showcasing my skills, education, and professional background as a web developer and legal advisor.

## 🌟 Features

- **Responsive Design** - Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Hover effects and animated skill progress bars
- **Mobile-First Approach** - Blue line elements hidden on mobile screens for better UX
- **Downloadable CV** - Direct CV download functionality

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with:
  - Flexbox and Grid layouts
  - CSS animations and transitions
  - Media queries for responsiveness
  - Custom properties (CSS variables)
  - Box shadows and gradients

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── index.css           # Stylesheet
├── index.js            # JavaScript functionality
├── README.md           # Project documentation
├── cv.pdf              # Downloadable CV (add your file)
├── js.jpg              # Profile image
├── muguna.jpg          # Additional images
├── image.png           # Additional images
└── WhatsApp Image 2025-04-02 at 20.03.24.jpeg  # Testimonial images
```

## 🎨 Design Features

### Color Scheme
- **Primary**: `#00ffe0` (Cyan/Teal)
- **Secondary**: `#00bfff` (Blue)
- **Background**: `#000808` (Dark)
- **Text**: White and light colors

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Responsive font sizes** using rem units

### Layout Components
- **Header**: Fixed navigation with logo and menu
- **Hero Section**: Introduction with animated text
- **Education Timeline**: Vertical timeline with dots and dates
- **Skills Section**: Animated progress bars
- **Services Grid**: 2x2 grid layout
- **Testimonials**: Card-based layout
- **Contact Form**: Responsive form design
- **Footer**: Social links and navigation

## 📱 Responsive Breakpoints

- **Desktop**: 1285px and above
- **Tablet**: 991px - 1284px
- **Mobile**: 895px and below
- **Small Mobile**: 600px and below

## 🎯 Key Sections

### 1. Home Section
- Animated typing effect for job titles
- Download CV button
- Professional photo with hover effects

### 2. Education Timeline
- Vertical timeline with connecting lines
- Timeline dots with glow effects
- Responsive layout (lines hidden on mobile)

### 3. Programming Skills
- Animated progress bars
- Percentage-based skill visualization
- Smooth CSS transitions

### 4. Services
- Grid layout with hover animations
- Service cards with descriptions
- Color transitions on hover

### 5. Testimonials
- Card-based testimonials
- Profile images with borders
- Hover effects and shadows

### 6. Contact Form
- Responsive form layout
- Input styling with focus states
- Submit button with animations

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd portfolio
   ```

2. **Add your CV**
   - Place your `cv.pdf` file in the project root
   - The download button will automatically work

3. **Customize content**
   - Update personal information in `index.html`
   - Modify colors in `index.css` (CSS variables in `:root`)
   - Replace images with your own

4. **Deploy**
   - Upload to GitHub Pages, Netlify, or any web hosting service
   - All files are static and ready for deployment

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `index.css`:
```css
:root {
    --big-color: #000808;
    --second-big-color: #131313;
    --text-color: white;
    --main-color: #00ffe0;
}
```

### Adding Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS styles in `index.css`
3. Update navigation links if needed

### Modifying Animations
- Progress bar animations: Modify `.progress` transition
- Hover effects: Edit `:hover` states
- Text animations: Update `@keyframes` rules

## 📱 Mobile Optimizations

- **Hidden elements**: Blue timeline lines hidden on mobile
- **Responsive images**: Scaled appropriately for different screens
- **Touch-friendly**: Buttons and links sized for mobile interaction
- **Readable text**: Font sizes adjusted for mobile screens

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Kenneth Ochola**
- Web Developer & Legal Advisor
- Based in Yala, Siaya County, Kenya
- Email: ocholakenna1@gmail.com

---

*Built with ❤️ using HTML5 and CSS3* 