# Viral X Threads Landing Page

A clean, modern landing page for viral thread analytics on X (formerly Twitter), built with pure HTML and CSS using design principles inspired by shadcn-ui.

## 🚀 Features

- **Minimal Design**: Clean aesthetic with shadcn-ui inspired components
- **Fully Responsive**: Mobile-first approach with breakpoints for tablet and desktop
- **Zero Dependencies**: Pure HTML/CSS implementation, no JavaScript required
- **Modular CSS Architecture**: Organized styles with separation of concerns
- **Accessibility**: Semantic HTML, ARIA labels, and keyboard navigation support
- **Performance Optimized**: System font stack, minimal CSS, fast loading

## 📁 Project Structure

```
viral-threads-landing/
├── index.html          # Main HTML file with all sections
├── css/
│   ├── variables.css   # CSS custom properties for theming
│   ├── base.css       # Reset and base typography
│   ├── components.css # Reusable UI components
│   └── layout.css     # Layout and responsive styles
```

## 🎨 Design System

### Color Palette
- Primary: Orange (#f97316) - Eye-catching CTAs
- Background: Clean whites and subtle grays
- Text: Zinc color scale for hierarchy
- Borders: Subtle #e4e4e7 for separation

### Typography
- System font stack for optimal performance
- Clear hierarchy from 12px to 60px
- Responsive scaling for mobile devices

### Components
- Ghost-style buttons with hover effects
- Clean cards with subtle shadows
- Numbered step indicators
- Statistics with gradient effects
- Responsive grid layouts

## 📄 Page Sections

1. **Navigation** - Sticky header with blur effect
2. **Hero** - Compelling headline with CTA
3. **Features** - 3-column grid of key benefits
4. **How It Works** - 4-step process flow
5. **Stats** - Impressive metrics display
6. **CTA** - Email capture with final call-to-action
7. **Footer** - Links and social media

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/viral-threads-landing.git
```

2. Navigate to the project:
```bash
cd viral-threads-landing
```

3. Open in browser:
```bash
open index.html
```

Or simply drag `index.html` into your browser.

## 💻 Development

No build process required! Edit the HTML and CSS files directly and refresh your browser to see changes.

### File Organization:
- `variables.css` - Modify colors, spacing, typography scales
- `base.css` - Adjust reset styles and base elements
- `components.css` - Edit reusable component styles
- `layout.css` - Modify layout and responsive behavior

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Performance

- **PageSpeed Score**: 95+ (estimated)
- **No JavaScript**: Pure CSS interactions
- **Optimized Assets**: System fonts, minimal CSS
- **Fast Paint**: < 1s first contentful paint

## 🛠 Customization

### Changing Colors
Edit the color variables in `css/variables.css`:
```css
--color-primary: #f97316;  /* Change primary color */
--color-background: #ffffff;  /* Change background */
```

### Modifying Spacing
Adjust the spacing scale in `css/variables.css`:
```css
--space-4: 1rem;  /* Base spacing unit */
--space-8: 2rem;  /* Double spacing */
```

### Adding Sections
1. Add HTML section in `index.html`
2. Create styles in `layout.css`
3. Add any reusable components to `components.css`

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

Built with ❤️ using clean HTML and CSS