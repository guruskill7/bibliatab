# BiBliaTab - Chrome Extension

> *"As for me and my house, we will serve the Lord" — Joshua 24:15*

A beautiful, minimalist homepage extension for Chrome featuring daily Bible verses, weather, and customizable features. Transform your new tab into a divine sanctuary that inspires and uplifts you every day.

![BiBliaTab Logo](logo.png)

## ✨ Features

### 📖 **Biblical Inspiration**
- **Daily Bible Verses**: Automatically fetched from comprehensive Bible APIs
- **Multi-language Support**: English, French, Spanish, Portuguese
- **Multiple Translations**: KJV, NIV, ESV, RVR60, LSG, and more
- **Thematic Verses**: Choose by theme (Hope, Faith, Strength, Peace, Love, Wisdom, Joy)
- **Verse Search**: Look up any specific Bible reference (e.g., John 3:16)
- **One-click Copy**: Share verses easily with built-in copy functionality

### 🌤️ **Weather Integration**
- **Real-time Weather**: Current conditions for your location
- **Beautiful Weather Icons**: Contextual emoji-based weather display
- **Location-based**: Automatic geolocation with privacy respect
- **Minimal Design**: Clean, unobtrusive weather widget

### ⏰ **Time & Date**
- **Dynamic Time Display**: Beautiful, large time with customizable format
- **Smart Date**: Localized date display matching your Bible language
- **12/24 Hour Format**: Choose your preferred time display

### 🔍 **Smart Search**
- **Instant Search**: Direct Google search integration
- **Keyboard-friendly**: Type anywhere to start searching
- **Clean Interface**: Minimalist search bar with smooth animations

### 🎨 **Customizable Backgrounds**
- **Divine Gradients**: Beautiful, heavenly color schemes
- **Custom Images**: Upload your own inspirational backgrounds
- **Unsplash Integration**: Random beautiful nature photos
- **Overlay Control**: Adjustable opacity for perfect readability

### 🔗 **Quick Links**
- **Customizable Shortcuts**: Add your most-visited sites
- **Icon Support**: Emoji icons for visual appeal
- **Drag & Drop**: Easy reordering (coming soon)
- **Smart Defaults**: Pre-loaded with popular sites

### ⚙️ **Advanced Settings**
- **Theme Selection**: Choose verse themes that inspire you
- **Auto-refresh**: Daily verse updates at midnight
- **Import/Export**: Backup and restore your settings
- **Keyboard Shortcuts**: Power-user friendly hotkeys

## 🚀 Installation

### Method 1: Load as Unpacked Extension (Recommended for Development)

1. **Download the Extension**
   ```bash
   git clone https://github.com/guruskill7/bibliatab.git
   # or download and extract the ZIP file
   ```

2. **Open Chrome Extensions**
   - Navigate to `chrome://extensions/`
   - Enable "Developer mode" (toggle in top right)

3. **Load the Extension**
   - Click "Load unpacked"
   - Select the `bibliatab` folder
   - BiBliaTab will now replace your new tab page!

### Method 2: Chrome Web Store (Coming Soon)
*BiBliaTab will be available on the Chrome Web Store soon for easy one-click installation.*

## 🛠️ Setup & Configuration

### Weather Setup (Optional)
To enable weather features:

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Open `script.js` in your extension folder
3. Find line ~420 and replace `'your-openweather-api-key'` with your actual API key
4. Reload the extension in `chrome://extensions/`

**Note**: Bible verses work immediately without any API keys required!

### Icon Files
Add these icon files to the `icons/` folder:
- `icon16.png` (16×16 pixels)
- `icon32.png` (32×32 pixels)
- `icon48.png` (48×48 pixels)
- `icon128.png` (128×128 pixels)

## 📖 Bible Translations & Languages

### 🇺🇸 English
- **KJV** - King James Version (1611)
- **NIV** - New International Version
- **ESV** - English Standard Version
- **ASV** - American Standard Version
- **WEB** - World English Bible
- **NASB** - New American Standard Bible

### 🇪🇸 Spanish
- **RVR60** - Reina-Valera 1960
- **NVI** - Nueva Versión Internacional

### 🇫🇷 French
- **LSG** - Louis Segond

### 🇧🇷 Portuguese
- **ARC** - Almeida Revista e Corrigida
- **NVI-PT** - Nova Versão Internacional

*More languages and translations are being added regularly!*

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + ,` | Open Settings |
| `Ctrl/Cmd + R` | Get New Verse |
| `Ctrl/Cmd + C` | Copy Current Verse |
| `Escape` | Close Settings Modal |
| `Type anywhere` | Focus Search Bar |
| `Ctrl/Cmd + Shift + ?` | Show Keyboard Help |

## 🎯 Verse Themes

Choose from carefully curated themes:

- **🌅 Hope & Future** - Verses about God's plans and promises
- **🙏 Faith & Trust** - Building confidence in God's faithfulness  
- **💪 Strength & Courage** - Finding power in difficult times
- **☮️ Peace & Comfort** - Rest and tranquility in God's presence
- **❤️ Love & Grace** - God's unconditional love and mercy
- **🧠 Wisdom & Guidance** - Seeking God's direction and understanding
- **😊 Joy & Thanksgiving** - Celebrating God's goodness and blessings

## 🗂️ File Structure

```
bibliatab/
├── manifest.json          # Extension configuration
├── index.html             # Main homepage structure
├── styles.css             # Beautiful CSS styling
├── script.js              # Main application logic
├── bible-verses.js        # Bible API integration
├── icons/                 # Extension icons
│   ├── icon16.png
│   ├── icon32.png
│   ├── icon48.png
│   └── icon128.png
└── README.md              # This documentation
```

## 🛡️ Privacy & Security

BiBliaTab respects your privacy:

- **Local Storage Only**: Settings stored locally on your device
- **Optional Location**: Weather requires location permission (optional)
- **No Tracking**: No analytics, cookies, or user tracking
- **No Data Collection**: We don't collect or transmit personal data
- **Secure APIs**: All Bible content fetched from trusted, public APIs
- **Open Source**: Full transparency with public code

## 🔧 Development

### Prerequisites
- Chrome browser
- Basic knowledge of HTML, CSS, JavaScript
- Text editor (VS Code recommended)

### Local Development
1. Clone the repository
2. Make your changes
3. Reload extension in `chrome://extensions/`
4. Test your changes

### Contributing
We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a Pull Request

#### Adding New Bible Translations
1. Update `BIBLE_API_CONFIG` in `bible-verses.js`
2. Add translation to `TRANSLATION_MAPPINGS`
3. Test with various verses
4. Update documentation

## 🐛 Troubleshooting

### Common Issues

**Verses Not Loading**
- Check internet connection
- Verify console for API errors
- Try different translation/language

**Weather Not Working**
- Ensure location permissions are granted
- Add valid OpenWeatherMap API key
- Check browser location settings

**Extension Not Loading**
- Verify all files are in the same folder
- Check `manifest.json` syntax
- Reload extension in Chrome settings

**Settings Not Saving**
- Check browser storage permissions
- Try refreshing the page
- Clear browser cache if needed

### Getting Help
1. Check the [Issues](https://github.com/guruskill7/bibliatab/issues) page
2. Search existing solutions
3. Create a new issue with detailed information
4. Include browser version and error messages

## 🚧 Roadmap

### Version 1.1 (Coming Soon)
- [ ] Verse of the Day based on liturgical calendar
- [ ] Favorite verses bookmarking
- [ ] Reading plans integration
- [ ] More Bible translations (German, Italian, Arabic)
- [ ] Dark/Light theme toggle
- [ ] Verse sharing to social media

### Version 1.2 (Future)
- [ ] Bible study notes integration
- [ ] Community verse sharing
- [ ] Offline verse caching
- [ ] Progressive Web App (PWA) features
- [ ] Voice reading of verses
- [ ] Multiple verse displays

### Long-term Vision
- [ ] Bible study groups integration
- [ ] Church calendar integration
- [ ] Devotional content
- [ ] Prayer request features
- [ ] Christian music integration

## 🤝 Support

### Ways to Support BiBliaTab
- ⭐ **Star the Repository** on GitHub
- 🐛 **Report Bugs** or suggest features
- 💝 **Share with Friends** who would appreciate daily Bible verses
- 🙏 **Pray for the Project** and its impact on users' lives
- 💻 **Contribute Code** or translations

### Contact
- **GitHub Issues**: [Report bugs or request features](https://github.com/guruskill7/bibliatab/issues)
- **Email**: support@bibliatab.com (coming soon)
- **Twitter**: @BiBliaTab (coming soon)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Bible APIs**: [bible-api.com](https://bible-api.com) and [bolls.life](https://bolls.life) for free Bible access
- **Weather Data**: [OpenWeatherMap](https://openweathermap.org) for weather information
- **Icons**: Various emoji providers for beautiful iconography
- **Community**: All beta testers and contributors

## 📊 Stats

- **Bible Translations**: 8+ translations in 4 languages
- **Verses Available**: 31,000+ verses from the complete Bible
- **Themes**: 8 carefully curated inspirational themes
- **Install Size**: < 1MB (lightweight and fast)
- **Load Time**: < 500ms (optimized for speed)

---

**BiBliaTab** - *Start each day with God's Word* 🙏

> *"Your word is a lamp for my feet, a light on my path."* — Psalm 119:105

---

*Made with ❤️ and 🙏 for the global Christian community*