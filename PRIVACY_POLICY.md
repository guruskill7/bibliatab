# Privacy Policy for BibliaTab

**Last Updated: February 10, 2026**

Your privacy is critically important to us. BibliaTab is designed with privacy as a core principle. This policy explains what data we collect (spoiler: almost nothing), how we use it, and your rights.

---

## Data Collection

**BibliaTab does NOT collect, store, or transmit any personal data to external servers.** Your privacy is our absolute priority.

**What we DON'T collect:**
- ❌ No browsing history
- ❌ No personal information
- ❌ No tracking cookies
- ❌ No analytics or usage data
- ❌ No email addresses or contact information
- ❌ No device information
- ❌ No IP addresses (stored)
- ❌ No user accounts or authentication

---

## Local Storage

All your data stays on YOUR device, in YOUR browser, under YOUR control.

**What is stored locally in your browser:**
- ✅ **User preferences**: Language settings, Bible translations, theme choices
- ✅ **Visual customization**: Font selections, background preferences, color schemes
- ✅ **Bible reading data**:
  - Personal notes for Bible chapters
  - Verse highlights with your chosen colors
  - Text highlighting colors and verse bookmarks
  - Bible reader chapter position and last reading location
  - Custom verse selections
- ✅ **Weather preferences**: Location input (city name only, if you provide it)
- ✅ **Search preferences**: Search history (stored locally only, if enabled)
- ✅ **Display settings**: Time format (12/24 hour), greeting visibility, widget toggles

**Important:** 
- All data is stored using your browser's local storage API
- No data is sent to any server or external service
- No data is shared with third parties
- You can clear this data anytime through browser settings
- Uninstalling the extension removes all local data

---

## External APIs Used

BibliaTab uses the following external services to provide functionality. These services receive only the minimum data necessary and do not store your personal information:

### 🙏 **Bible API (bolls.life)**
- **Purpose**: Fetch Bible verses and translations
- **Data sent**: Bible reference (book, chapter, verse), language, translation
- **Data stored**: None
- **Your data**: No personal information is sent

### 🌤️ **Open-Meteo Weather API**
- **Purpose**: Provide weather information
- **Data sent**: Geographic coordinates (latitude/longitude) only
- **Data stored**: None by this service
- **Your data**: No personal information, no precise location tracking

### 🖼️ **Picsum Photos**
- **Purpose**: Provide beautiful background images
- **Data sent**: Image category preference
- **Data stored**: None
- **Tracking**: No tracking or personal data collection
- **Privacy**: Images are publicly available stock photos

### 🌍 **BigDataCloud Geolocation API**
- **Purpose**: Convert your IP address to approximate city location for weather
- **Data sent**: Your IP address (automatically sent by your browser)
- **Data received**: Approximate city/region name, coordinates
- **Data stored**: None by this service
- **Note**: Only used if you don't manually enter a location
- **Privacy**: IP-based geolocation provides city-level accuracy, not precise physical address

### 🗺️ **OpenStreetMap Nominatim**
- **Purpose**: Convert city names to coordinates for weather lookup
- **Data sent**: City name you enter (if you manually set weather location)
- **Data stored**: None by this service
- **Your data**: Only used when you manually enter a city name

**All API communications use HTTPS encryption to protect data in transit.**

---

## Permissions Explained

BibliaTab requests minimal permissions to function:

### **Storage Permission** (Required)
- **Why**: Save your preferences, notes, and settings locally
- **What it does**: Allows the extension to store data in your browser's local storage
- **What it does NOT do**: 
  - ❌ Cannot access your browsing history
  - ❌ Cannot see other websites you visit
  - ❌ Cannot access your files or downloads
  - ❌ Cannot access your passwords or personal data

### **No Additional Permissions**
- ✅ We do NOT request access to:
  - Your browsing history
  - Your tabs
  - Your bookmarks
  - Your downloads
  - Your personal files
  - Your camera or microphone
  - Your location (device-level GPS)
  - Any other browser data

**Browser Geolocation (Optional):**
- Only used if you don't manually enter a location for weather
- Uses IP-based geolocation (city-level, not GPS)
- Never accesses device GPS or precise physical location
- No permission popup required (IP-based only)
- You can always manually enter a city name instead

---

## Data Security

Your security is paramount:

### **Technical Security Measures:**
- ✅ **HTTPS Encryption**: All external API communications use HTTPS
- ✅ **Content Security Policy (CSP)**: Strict CSP prevents unauthorized code execution
- ✅ **XSS Protection**: Comprehensive input sanitization against cross-site scripting
- ✅ **No eval()**: We never use unsafe code execution functions
- ✅ **Input Validation**: All user inputs are sanitized and validated
- ✅ **A+ Security Grade**: Professional security audit passed

### **Code Transparency:**
- ✅ **Open Source**: All code is publicly available on GitHub for review
- ✅ **Community Audited**: Anyone can inspect our security practices
- ✅ **No Obfuscation**: Code is readable and transparent

---

## Third-Party Data Sharing

**We do NOT share your data with third parties. Period.**

- ❌ No data brokers
- ❌ No advertising networks
- ❌ No analytics companies
- ❌ No social media platforms
- ❌ No marketing services
- ❌ No affiliates or partners

The only data transmission occurs when:
1. You request a Bible verse (to Bible API)
2. You request weather data (to Weather API)
3. You load a background image (to Picsum Photos)
4. You allow IP-based location for weather (to BigDataCloud)
5. You manually enter a city for weather (to OpenStreetMap)

All of these are necessary for the extension's core functionality and contain no personal information.

---

## Children's Privacy

**BibliaTab is safe for users of all ages**, including children.

- ✅ Family-friendly content (Bible verses, weather, inspirational themes)
- ✅ No ads or inappropriate content
- ✅ No data collection from children or anyone
- ✅ No user accounts or registration required
- ✅ No social features or communication tools
- ✅ Complies with COPPA (Children's Online Privacy Protection Act)

Parents can confidently allow children to use BibliaTab without privacy concerns.

---

## Your Privacy Rights

You have complete control over your data:

### **Right to Access:**
- All your data is stored locally in your browser
- You can view it anytime through browser developer tools

### **Right to Delete:**
- Clear extension data: Browser Settings → Extensions → BibliaTab → Remove
- Clear local storage: Browser Settings → Privacy → Clear browsing data → Cookies and site data
- Uninstall extension: Removes all associated local data

### **Right to Export:**
- Your notes and settings are in browser local storage
- You can export them using browser developer tools (F12 → Application → Local Storage)

### **Right to Opt-Out:**
- Weather location: Don't enter a location, or disable weather widget
- Background images: Switch to solid color or gradient backgrounds
- Any feature: Toggle off in settings

---

## Cookies and Tracking

**BibliaTab does NOT use cookies or tracking technologies.**

- ❌ No cookies
- ❌ No tracking pixels
- ❌ No fingerprinting
- ❌ No analytics
- ❌ No session tracking
- ❌ No user profiling

---

## Changes to This Privacy Policy

If we update this privacy policy, we will:
1. Update the "Last Updated" date at the top
2. Notify users through the extension (in-app notification)
3. Post changes on our GitHub repository
4. Maintain transparency about what changed and why

**Material changes** will be prominently announced and require your acknowledgment.

---

## Contact & Support

If you have questions, concerns, or requests about this privacy policy or your data:

### **GitHub (Recommended):**
- **Issues**: [https://github.com/guruskill7/bibliatab/issues](https://github.com/guruskill7/bibliatab/issues)
- **Discussions**: [https://github.com/guruskill7/bibliatab/discussions](https://github.com/guruskill7/bibliatab/discussions)

### **Browser Store Support:**
- **Chrome Web Store**: Contact via extension support page
- **Firefox Add-ons**: Contact via extension support page  
- **Microsoft Edge Add-ons**: Contact via extension support page

### **Developer Contact:**
- **GitHub**: [@guruskill7](https://github.com/guruskill7)

We typically respond within 48-72 hours.

---

## Legal Compliance

BibliaTab complies with:
- ✅ **GDPR** (General Data Protection Regulation) - EU
- ✅ **CCPA** (California Consumer Privacy Act) - California, USA
- ✅ **COPPA** (Children's Online Privacy Protection Act) - USA
- ✅ **Chrome Web Store Policies**
- ✅ **Firefox Add-ons Policies**
- ✅ **Microsoft Edge Add-ons Policies**

---

## Open Source Transparency

**BibliaTab is open source.** You can:
- ✅ Review our code on GitHub: [github.com/guruskill7/bibliatab](https://github.com/guruskill7/bibliatab)
- ✅ Audit our security practices
- ✅ Verify our privacy claims
- ✅ Contribute improvements
- ✅ Report security issues

**Transparency is our commitment to you.**

---

## Summary (TL;DR)

**What BibliaTab Does:**
- ✅ Stores your preferences locally in your browser
- ✅ Fetches Bible verses when you request them
- ✅ Gets weather for your location (if you allow it)
- ✅ Loads background images when you choose them

**What BibliaTab Does NOT Do:**
- ❌ Collect personal data
- ❌ Track your browsing
- ❌ Share data with third parties
- ❌ Use cookies or analytics
- ❌ Show ads
- ❌ Require accounts or login

**Your privacy is sacred. Your data is yours. Always.**

---

## Questions?

If anything in this policy is unclear or you have concerns, please don't hesitate to reach out through GitHub Issues or Discussions. We're committed to transparency and will gladly answer any privacy questions.

---

## Version History

**v1.40.0 (February 10, 2026)**
- Updated API listing (Picsum Photos instead of Unsplash)
- Added new features to local storage section (highlighting, notes, bookmarks)
- Added OpenStreetMap Nominatim API disclosure
- Updated browser support (Chrome, Firefox, Edge)
- Expanded security section
- Enhanced clarity and detail

**v1.30.2 (August 17, 2025)**
- Initial privacy policy

---

📖 **"The Lord is my shepherd; I shall not want."** — Psalm 23:1

Made with ❤️ and ✝️ by the BibliaTab Team
