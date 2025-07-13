# 🏁 Racing Pigeon Tracker

A mobile-friendly web application for tracking racing pigeons' speed and performance. Perfect for pigeon racing enthusiasts who want to calculate average speeds and manage multiple pigeons in a race.

## 🌟 Features

- **Mobile-Optimized**: Works perfectly on iPhone, Android, and desktop
- **Time Input**: Custom hours, minutes, seconds input (no native pickers)
- **Speed Calculation**: Automatic average speed calculation in km/h
- **Unit Conversion**: Toggle between km/h and meters per minute
- **Multiple Pigeons**: Add unlimited pigeons to track
- **Real-time Updates**: Instant calculations and display updates
- **No Installation**: Works directly in any web browser
- **PWA Ready**: Can be added to home screen on mobile devices

## 🚀 Live Demo

Visit the live application: [https://zbla92.github.io/pigeo-speed-calculator/](https://zbla92.github.io/pigeo-speed-calculator/)

## 📱 How to Use

1. **Set Race Parameters**:
   - Enter release time (hours, minutes, seconds)
   - Enter race distance in kilometers

2. **Add Pigeons**:
   - Name each pigeon
   - Enter arrival time
   - Click "Add Pigeon"

3. **View Results**:
   - See calculated average speed for each pigeon
   - Toggle between km/h and m/min units
   - Delete pigeons as needed

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No frameworks or build process required
- **iOS Compatible**: Uses techniques that work on all iOS devices
- **Responsive Design**: Adapts to any screen size
- **Progressive Web App**: Can be installed on mobile devices
- **GitHub Pages**: Hosted for free on GitHub Pages

## 📋 Requirements

- Modern web browser (Chrome, Safari, Firefox, Edge)
- No internet connection required after initial load
- Works offline once loaded

## 🔧 Setup for Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/zbla92/pigeo-speed-calculator.git
   cd pigeo-speed-calculator
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server for development

3. **For local server** (optional):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 🚀 Deployment

This project is automatically deployed to GitHub Pages. To enable:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Save

Your app will be available at: `https://yourusername.github.io/pigeo-speed-calculator/`

## 📱 Mobile Usage

### iPhone/iPad
- Open Safari or Chrome
- Navigate to the app URL
- Tap "Add to Home Screen" for app-like experience
- Works perfectly with touch input

### Android
- Open Chrome or any browser
- Navigate to the app URL
- Can be added to home screen
- Full touch support

## 🎯 Use Cases

- **Pigeon Racing Clubs**: Track multiple pigeons in races
- **Individual Breeders**: Monitor performance of specific pigeons
- **Race Officials**: Calculate official race results
- **Training**: Track training flight speeds
- **Competition**: Compare pigeon performance

## 🔢 Speed Calculation

The app calculates average speed using the formula:
```
Speed (km/h) = Distance (km) / Time (hours)
```

Where time is calculated as:
```
Time = (Arrival Time - Release Time) in hours
```

## 🎨 Customization

The app is easily customizable:
- Colors and styling in the CSS section
- Functionality in the JavaScript section
- Layout and structure in the HTML

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built for the pigeon racing community
- Inspired by the need for simple, mobile-friendly tracking tools
- Thanks to all pigeon racing enthusiasts for feedback

## 📞 Support

If you have any questions or need help:
- Open an issue on GitHub
- Contact the maintainer
- Check the live demo for usage examples

---

**Made with ❤️ for pigeon racing enthusiasts** 