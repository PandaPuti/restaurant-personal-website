# 🍽️ Restaurant Personal Website

A modern, responsive restaurant website built with HTML and CSS to showcase our menu, services, and create an engaging online presence for our customers.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [File Structure](#file-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Overview

This is a static restaurant website designed to provide visitors with essential information about the restaurant, including the menu, location, opening hours, and contact details. The website features a clean, modern design that's fully responsive and works seamlessly across all devices.

## ✨ Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and intuitive interface with smooth animations
- **Menu Showcase**: Dedicated section to display food and beverage offerings
- **Contact Information**: Easy-to-find contact details and location
- **Image Gallery**: Visual presentation of dishes and restaurant ambiance
- **Fast Loading**: Lightweight design with optimized images
- **Cross-browser Compatible**: Works on all modern browsers
- **SEO Friendly**: Proper HTML structure and meta tags for better search visibility

## 📁 File Structure

```
restaurant-personal-website/
│
├── index.html          # Main HTML file
├── style.css           # CSS stylesheet
├── .gitignore          # Git ignore file
├── README.md           # Project documentation
│
└── images/             # Image assets folder
    
```

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/PandaPuti/restaurant-personal-website.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd restaurant-personal-website
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

## 💻 Usage

### Viewing the Website

1. Open `index.html` in any modern web browser
2. Navigate through different sections using the navigation menu
3. The website is fully functional offline as it's a static site

### Deployment

You can deploy this website to various platforms:

- **GitHub Pages**: Push to GitHub and enable Pages in repository settings
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your repository to Vercel
- **Traditional Hosting**: Upload files via FTP to your web host

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
}
```

### Adding Images

1. Place your images in the `images/` folder
2. Update the image paths in `index.html`:
   ```html
   <img src="images/your-image.jpg" alt="Description">
   ```

### Updating Content

- **Restaurant Name**: Search and replace in `index.html`
- **Menu Items**: Edit the menu section in `index.html`
- **Contact Info**: Update contact details in the footer section
- **Opening Hours**: Modify the hours section in `index.html`

### Fonts

The website uses web-safe fonts. To use custom fonts:

1. Add Google Fonts link in `<head>` of `index.html`:
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
   ```

2. Update font-family in `style.css`:
   ```css
   body {
       font-family: 'Your Font', sans-serif;
   }
   ```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@PandaPuti](https://github.com/PandaPuti)
- Email: munu7199@gmail.com

## 🙏 Acknowledgments

- Design inspiration from modern restaurant websites
- Images from [Unsplash](https://unsplash.com) / [Pexels](https://pexels.com)
- Icons from [Font Awesome](https://fontawesome.com)

## 📞 Contact & Support

For questions or support, please:
- Open an issue on GitHub
- Email: munu7199@gmail.com

---

**⭐ If you like this project, please give it a star on GitHub! ⭐**

---

*Last Updated: April 2026*