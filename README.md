# BiBliaTab - Chrome Extension

> *"As for me and my house, we will serve the Lord" — Joshua 24:15*

A beautiful, minimalist homepage extension for Chrome featuring daily Bible verses, weather, and customizable features. Transform your new tab into a divine sanctuary that inspires and uplifts you every day.


<img width="128" height="128" alt="icon128" src="https://github.com/user-attachments/assets/640dca85-8c88-46e5-849f-a773f9d0bf7a" />


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
- **Keyboard Shortcuts**: Power-user friendly hotkeys


### Method 2: Chrome Web Store (Coming Soon)
*BiBliaTab will be available on the Chrome Web Store soon for easy one-click installation.*

## 🛠️ Setup & Configuration

**Note**: Bible verses work immediately without any API keys required!

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

### Contributing
We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a Pull Request

## 🐛 Troubleshooting

### Common Issues

**Verses Not Loading**
- Check internet connection
- Try different translation/language - the Portuguese bible translation is only available in some chapters

**Weather Not Working**
- Ensure location permissions are granted
- Check browser location settings

**Extension Not Loading**
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

### Version 1.30.0 (Coming Soon)
- [ ] Bible study sync notes
- [ ] Reading plans integration
- [ ] More Bible translations (German, Italian, Arabic)
- [ ] Dark/Light theme toggle
- [ ] Verse sharing to social media

### Version 1.31 (Future)
- [ ] Bible study notes integration
- [ ] verse sharing
- [ ] Offline verse caching
- [ ] Progressive Web App (PWA) features
- [ ] Voice reading of verses 

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
