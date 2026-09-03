# Privacy Policy for BibliaTab

**Last Updated: September 2, 2026** · Applies to v1.41.0 and later

Your privacy is critically important to us. BibliaTab is designed with privacy as a core principle. This policy explains what data we collect (spoiler: almost nothing), how we use it, and your rights.

For the same content as a browsable webpage, see [privacy-policy.html](privacy-policy.html).

---

## Data Collection

**BibliaTab does NOT collect, sell, or transmit personal data to any server we operate.** Nearly everything it stores stays on your device or in your own browser account's sync — under your control.

**What we DON'T collect:**
- ❌ No browsing history
- ❌ No personal information (name, email, etc.)
- ❌ No tracking cookies
- ❌ No analytics or usage tracking
- ❌ No user accounts or authentication
- ❌ No advertising identifiers

---

## Local & Synced Storage

- ✅ **Settings, notes, and shortcuts** are saved via your browser's built-in `storage.sync` API. If you're signed into your browser (Chrome, Edge, or Firefox account) with sync enabled, this data travels through your browser vendor's own encrypted sync — the same mechanism used for your bookmarks or other extensions' settings. BibliaTab never sends this data to a server we operate.
- ✅ **Custom background photos** you upload stay in local browser storage on that one device only (they're too large for sync storage).
- ✅ **Verse highlights** are kept in local browser storage.
- ✅ If sync isn't available, everything above falls back to plain local storage on that device.
- ✅ Uninstalling the extension, or clearing its site data, removes all of it.

---

## External APIs Used

These requests happen only when you use the related feature, and never include your name, email, or any account identifier — BibliaTab has no accounts.

### 📖 **bolls.life** and **bible.helloao.org**
- **Purpose**: Fetch Bible verse and chapter text
- **Data sent**: Book, chapter, and translation requested
- **Data stored**: None

### 📚 **api.scripture.api.bible**
- **Purpose**: Fetch the list of books for certain Bible translations in the Bible Reader
- **Data sent**: The translation ID selected, plus an app-level API key (not tied to you personally)
- **Data stored**: None

### 🌤️ **Open-Meteo Weather API**
- **Purpose**: Provide weather information
- **Data sent**: Latitude/longitude only
- **Data stored**: None by this service

### 🖼️ **Picsum Photos**
- **Purpose**: Provide background images when "Picsum Photos" is selected as the background type
- **Data sent**: A randomly generated seed number and the requested image size — no personal data, no category label is transmitted
- **Data stored**: None
- **Privacy**: Publicly available stock photos

### 🌍 **BigDataCloud Geolocation API**
- **Purpose**: Coarse, city-level location fallback for weather — used only if device location is denied or unavailable
- **Data sent**: Your IP address, sent automatically by the browser like any web request
- **Data received**: Approximate city/region and coordinates
- **Data stored**: None by this service

### 🗺️ **OpenStreetMap Nominatim**
- **Purpose**: Convert coordinates to a readable city name (after device/IP location), or convert a city name you type into coordinates
- **Data sent**: Either device/IP-derived coordinates, or the city name you manually enter in Settings
- **Data stored**: None by this service

**All API communications use HTTPS encryption.**

---

## Permissions Explained

### **Storage Permission** (Required)
- **Why**: Save your preferences, notes, and settings as described above
- **What it does NOT do**: Cannot access your browsing history, other tabs, files, downloads, or passwords

### **Search Permission** (Required)
- **Why**: The new-tab search bar uses the browser's Search API to send your query directly to *your own default search engine* — the same one your address bar already uses
- **What it does NOT do**: BibliaTab does not see, log, or store your search queries; the browser forwards them straight to your search engine

### **Geolocation Permission** (Used for weather; has fallbacks)
Used only for the weather widget, in this order:
1. **Device location** (GPS / Wi-Fi / network) via your browser's own one-time permission prompt — you may Allow or Deny
2. If denied or unavailable: **coarse IP-based location** (city-level, via BigDataCloud)
3. If that also fails: a default forecast is shown, with a prompt to type your city manually in Settings

You can skip all of this at any time by entering a city name or exact coordinates directly in Settings → Weather Location.

### **What BibliaTab never requests**
- ❌ Your tabs, bookmarks, or downloads
- ❌ Your files, camera, or microphone
- ❌ Any account, sign-in, email, or password
- ❌ Advertising or analytics identifiers

---

## Data Security

- ✅ **HTTPS Encryption** for all external API communications
- ✅ **Content Security Policy (CSP)** restricting network requests to a known allowlist of the endpoints listed above
- ✅ **Input sanitization** against cross-site scripting
- ✅ **No `eval()`** or dynamic code execution
- ✅ **Open Source** — code is publicly reviewable on GitHub

---

## Third-Party Data Sharing

**We do not sell or share your data with third parties.**

- ❌ No data brokers, ad networks, or analytics companies
- ❌ No social media platforms
- ❌ No marketing services

The only data transmission occurs when:
1. You request a Bible verse or chapter (to bolls.life, HelloAO, or scripture.api.bible)
2. You request weather data (to Open-Meteo)
3. BibliaTab looks up your location for weather (to your browser's own location service, then BigDataCloud and/or OpenStreetMap)
4. You load a background image (to Picsum Photos)

All of these are necessary for the extension's core functionality and contain no personal information.

---

## Children's Privacy

BibliaTab collects no personal data from anyone, including children, and has no accounts, ads, or communication features, in line with COPPA.

---

## Your Privacy Rights

- **Access**: All your data lives in your browser; view it via developer tools (F12 → Application → Storage)
- **Delete**: Remove the extension, or clear its site data via your browser's settings
- **Opt-out**: Turn off the weather widget, switch to a Gradient/Solid background, or type a manual location — each stops the related network requests

---

## Changes to This Policy

Material changes will update the date at the top of this page and be noted in BibliaTab's in-app "what's new" notice after an update.

---

## Contact

- **GitHub Issues**: [github.com/guruskill7/bibliatab/issues](https://github.com/guruskill7/bibliatab/issues)
- **Email**: devproduction51@proton.me
- **Developer**: Snoubs Dev Studio ([@guruskill7](https://github.com/guruskill7))

---

## Version History

**v1.41.0 (September 2, 2026)**
- Added device geolocation (with IP-based and manual-entry fallbacks) for weather; corrected this section to reflect that a real location permission is now used
- Disclosed two additional Bible data sources (bible.helloao.org, api.scripture.api.bible)
- Documented the `search` permission
- Corrected the Picsum Photos entry (no category data is actually transmitted)
- Clarified that settings/notes/shortcuts sync via the browser's own account sync, not purely local-only storage

**v1.40.0 (February 10, 2026)**
- Updated API listing (Picsum Photos instead of Unsplash)
- Added highlighting, notes, and bookmarks to local storage section
- Added OpenStreetMap Nominatim disclosure

**v1.30.2 (August 17, 2025)**
- Initial privacy policy

---

📖 Made by Snoubs Dev Studio.
