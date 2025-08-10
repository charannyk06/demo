# Demo Website Project

A modern, responsive website built with HTML5, CSS3, and JavaScript showcasing best practices in web development.

## 🚀 Features

- **Modern HTML5**: Semantic elements, accessibility features, and SEO optimization
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox layouts
- **Interactive JavaScript**: Smooth scrolling, mobile menu, form validation, and scroll animations
- **CSS Custom Properties**: Maintainable theming system with CSS variables
- **Performance Optimized**: Lazy loading, efficient animations, and optimized assets
- **Development Workflow**: Live reload development server and build process

## 📁 Project Structure

```
demo/
├── src/                    # Source files
│   ├── index.html         # Main HTML file
│   ├── styles/
│   │   └── main.css       # Main stylesheet
│   └── scripts/
│       └── main.js        # Main JavaScript file
├── public/                # Static assets (images, fonts, etc.)
├── dist/                  # Build output (generated)
├── package.json           # Node.js project configuration
├── .gitignore            # Git ignore rules
└── README.md             # Project documentation
```

## 🛠️ Setup Instructions

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd demo
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

The website will automatically open in your browser at `http://localhost:3000`.

## 📜 Available Scripts

### Development

- **`npm run dev`**
  - Starts the development server with live reload
  - Serves files from `src/` directory
  - Opens browser automatically at `http://localhost:3000`
  - Perfect for development and testing

### Build

- **`npm run build`**
  - Copies all source files to `dist/` directory
  - Prepares files for production deployment

- **`npm run build:prod`**
  - Cleans the `dist/` directory and builds the project
  - Recommended for production builds

- **`npm run clean`**
  - Removes all files from `dist/` directory
  - Useful for cleaning build artifacts

### Production

- **`npm run start`**
  - Serves the built files from `dist/` directory
  - Runs on `http://localhost:8080`
  - Use this to test production builds locally

## 🎯 Usage

### Development Workflow

1. **Start development**: `npm run dev`
2. **Make changes** to files in the `src/` directory
3. **View changes** automatically in the browser (live reload)
4. **Build for production**: `npm run build:prod`
5. **Test production build**: `npm run start`

### Customization

#### Colors and Theming
Edit CSS custom properties in `src/styles/main.css`:
```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #64748b;
  /* ... other variables */
}
```

#### Content
- **HTML**: Edit `src/index.html` to modify content and structure
- **Styles**: Edit `src/styles/main.css` for styling changes
- **JavaScript**: Edit `src/scripts/main.js` for interactive features

#### Assets
- Add images, fonts, and other static assets to the `public/` directory
- Reference them in HTML with relative paths: `../public/your-image.jpg`

## 🌟 Features Overview

### HTML5 Features
- Semantic elements (`<header>`, `<main>`, `<section>`, `<footer>`)
- Accessibility attributes and proper heading hierarchy
- SEO meta tags and structured content
- Responsive images with lazy loading

### CSS Features
- **CSS Grid** for complex layouts
- **Flexbox** for component alignment
- **CSS Custom Properties** for theming
- **Media queries** for responsive design
- **Smooth animations** and transitions
- **Mobile-first** responsive approach

### JavaScript Features
- **Mobile menu toggle** with smooth animations
- **Smooth scrolling** navigation
- **Contact form validation** with error handling
- **Scroll-to-top** button
- **Intersection Observer** for scroll animations
- **Active navigation** highlighting
- **Performance optimizations** (debounce, throttle)

## 🎨 Browser Support

- **Modern browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Responsive design**: Works on all screen sizes from mobile to desktop

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: > 768px

## 🔧 Development Notes

### Code Style
- Modern ES6+ JavaScript
- CSS follows BEM-like naming conventions
- Semantic HTML5 structure
- Mobile-first responsive design

### Performance
- Optimized CSS with efficient selectors
- JavaScript uses modern APIs (Intersection Observer)
- Lazy loading for images
- Minimal dependencies

### Accessibility
- Proper ARIA attributes
- Keyboard navigation support
- Focus management
- Screen reader friendly
- High contrast mode support

## 🚀 Deployment

### Static Hosting
1. Run `npm run build:prod`
2. Upload the `dist/` folder to your hosting provider
3. Configure your server to serve `index.html` as the default file

### Popular Hosting Options
- **Netlify**: Drag and drop the `dist/` folder
- **Vercel**: Connect your Git repository
- **GitHub Pages**: Push `dist/` contents to `gh-pages` branch
- **Firebase Hosting**: Use Firebase CLI to deploy

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test thoroughly: `npm run dev` and `npm run start`
5. Commit your changes: `git commit -m 'Add feature'`
6. Push to the branch: `git push origin feature-name`
7. Submit a pull request

## 📄 License

This project is licensed under the ISC License - see the package.json file for details.

## 🆘 Troubleshooting

### Common Issues

**Port already in use**
- Change the port in package.json scripts or kill the process using the port

**Dependencies not installing**
- Delete `node_modules/` and `package-lock.json`, then run `npm install`

**Live reload not working**
- Check if you're editing files in the `src/` directory
- Restart the development server: `npm run dev`

**Build files not updating**
- Run `npm run clean` then `npm run build`

---

**Happy coding! 🎉**

