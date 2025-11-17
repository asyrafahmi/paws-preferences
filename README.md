# 🐱 Paws & Preferences - Find Your Favourite Kitty

A mobile-first web application that helps users discover their cat preferences through an intuitive swipe-based interface, similar to popular dating apps but for adorable cats!

## 🌟 Live Demo

**🚀 Website:** [https://asyrafahmi.github.io/paws-preferences/](https://asyrafahmi.github.io/paws-preferences/)

## 📱 Features

### Core Functionality
- **Swipe Interface**: Swipe right to like, left to dislike cats
- **Touch & Mouse Support**: Works seamlessly on mobile and desktop
- **Keyboard Navigation**: Arrow keys and spacebar support
- **Stack Effect**: Beautiful card stacking with depth perception
- **Progress Tracking**: Real-time counter showing progress through cats

### User Experience
- **Mobile-First Design**: Optimized for mobile devices with responsive layouts
- **Loading Progress**: Visual progress bar with smooth animations
- **Image Fallbacks**: Multiple fallback URLs ensure images always load
- **Performance Optimized**: Image preloading reduces lag and loading times
- **Summary Screen**: Shows match statistics and favorite cats at the end

### Technical Highlights
- **Vanilla JavaScript**: No frameworks, pure HTML/CSS/JS for fast loading
- **Progressive Loading**: Smart image preloading system
- **Error Handling**: Graceful fallbacks when images fail to load
- **Cross-Device Compatibility**: Works on iOS, Android, and desktop browsers
- **GitHub Pages Deployment**: Easy hosting and continuous deployment

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: CSS Grid, Flexbox, CSS Animations
- **Images**: Cataas API (https://cataas.com/)
- **Hosting**: GitHub Pages
- **Version Control**: Git & GitHub

## 🎮 How to Use

1. **Start Swiping**: View cat images one by one
2. **Make Your Choice**: 
   - Swipe right or click ❤️ to like a cat
   - Swipe left or click ❌ to dislike
   - Use arrow keys for keyboard navigation
3. **See Results**: View your match statistics and favorite cats
4. **Try Again**: Restart with new cats anytime

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for cat images

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/asyrafahmi/paws-preferences.git
   cd paws-preferences
   ```

2. **Start a local server**
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### Deployment
The app is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## 📱 Mobile Optimization

### Responsive Design
- **Mobile First**: Designed primarily for mobile devices
- **Touch-Friendly**: Large touch targets and smooth swipe gestures  
- **Performance**: Optimized loading and minimal resource usage
- **Cross-Platform**: Tested on iOS Safari, Chrome Mobile, and other mobile browsers

### Technical Optimizations
- Image preloading for smooth experience
- Multiple fallback URLs for reliability
- Efficient memory management
- Optimized CSS animations

## 🎨 Design Features

### Visual Design
- **Modern UI**: Clean, gradient-based design
- **Smooth Animations**: Swipe animations with rotation effects
- **Loading States**: Skeleton loading with progress indication
- **Card Stack Effect**: Depth perception with multiple card layers

### UX Enhancements
- **Immediate Feedback**: Visual response to user interactions
- **Error Recovery**: Graceful handling of failed image loads
- **Progress Indication**: Clear progress tracking throughout experience
- **Accessibility**: Keyboard navigation support

## 🔧 Configuration

You can customize the app by modifying these variables in `index.html`:

```javascript
const CAT_COUNT = 12; // Number of cats to show (default: 12)
const threshold = 100; // Swipe distance threshold (default: 100px)
```

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ iOS Safari 12+
- ✅ Chrome Mobile 60+

## 📊 Performance Features

- **Lazy Loading**: Images load on demand
- **Preloading**: Next images load in background
- **Fallback System**: Multiple backup image sources
- **Optimization**: Minimal resource usage
- **Caching**: Browser caching for repeated visits

## 🚀 Future Enhancements

- [ ] Cat breed information and filtering
- [ ] User preferences persistence (localStorage)
- [ ] Social sharing of favorite cats
- [ ] PWA (Progressive Web App) features
- [ ] Cat adoption center integration
- [ ] Advanced matching algorithm

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Cataas API** - For providing adorable cat images
- **GitHub Pages** - For free hosting
- **Cat lovers everywhere** - For inspiration! 🐱

## 📞 Contact

**Muhamad Asyraf Fahmi**
- LinkedIn: [asyrafahmi](https://www.linkedin.com/in/asyrafahmi)
- GitHub: [@asyrafahmi](https://github.com/asyrafahmi)
- Email: asyraf11fahmi@gmail.com

---

Made with ❤️ and 🐱 by [Asyraf Fahmi](https://github.com/asyrafahmi)
