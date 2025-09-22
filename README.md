# Digital Talent Release Form

A comprehensive web application for capturing digital talent release forms with signature capture, photo integration, and PDF generation. **100% offline operation with no servers - all data stays on your device for maximum privacy and security.** Perfect for photographers, videographers, and production companies who need legally compliant talent releases in the field.

## 🚀 Features

### Core Functionality
- **Digital Signature Capture** - Canvas-based drawing with touch and mouse support
- **Photo Integration** - Take a photo to easily link the form to the person who signed it [optional]
- **PDF Generation** - Professional PDF output with embedded signatures and photos
- **Form Validation** - Real-time validation with user-friendly error messages
- **100% Offline Operation** - No servers, no data transmission, complete privacy protection
- **PWA Support** - Installable on any device for native app experience

### Advanced Features
- **Persistent Project Data** - Client and project information saved across sessions
- **Witness Signatures** - Persistant witness signature
- **Children/Dependants Support** - Guardian consent forms for minors
- **Customizable Talent Release Agreement** - HTML-editable terms with live preview and historical preservation
- **Custom Client Logo** - Add your client or production company logo to be embedded in the PDF
- **Lock Mode** - Prevent changes to key fields and block history deletion. Hold lock for 3 seconds to activate.
- **Form History** - Local storage of all submissions with PDF re-generation
- **Dark/Light Theme** - User preference theming with automatic persistence

### Technical Highlights
- **Responsive Design** - Mobile-first approach optimized for tablets and phones
- **Progressive Web App** - Installable on mobile devices
- **Local Storage** - All data stored locally for privacy and offline use
- **No Backend Required** - Pure client-side implementation
- **Cross-Platform** - Works on iOS, Android, Windows, and macOS

## 🛠️ Installation

### 👉 Option 1: Use in Browser
1. Go to [the web app](https://jakelodder.github.io/talent-release/) via the link in the top-right corner of this GitHub repo.
2. The app works instantly — no setup required.
3. Once opened, it will continue to work offline thanks to PWA support.

### 📲 Option 2: Add to Home Screen (PWA Install)

#### On iPhone/iPad (Safari):
1. Open the app link in Safari: [jakelodder.github.io/talent-release](https://jakelodder.github.io/talent-release/)
2. Tap the **Share** button (bottom of screen).
3. Select **Add to Home Screen**.
4. Tap **Add** — the app will now appear on your home screen like a regular app.

#### On Android (Chrome or Edge):
1. Visit the app link: [jakelodder.github.io/talent-release](https://jakelodder.github.io/talent-release/)
2. Open the browser menu (⋮) and choose **Install App** or **Add to Home Screen**.
3. Confirm to add — the app will now launch full screen from your home screen.

## 📋 Usage

### Quick Start
1. **Set Project Information** - Enter client, project, location, and crew details
2. **Fill Talent Details** - Name, contact information, and age confirmation
3. **Capture Signatures** - Digital signatures for talent and witness
4. **Take Photo** (Optional) - In-app camera capture for record keeping
5. **Submit Form** - Generates PDF automatically and saves to history

### Persistent Data
- Client and project information persists across sessions
- Witness signatures are saved and reused
- Custom talent release agreements are preserved
- Theme preferences remembered

### Form History
- All submissions stored locally - no cloud usage for privacy security
- Re-download PDFs anytime with original terms preserved
- Clear history with confirmation
- Export data for backup

## ⚖️ Legal Compliance

This form includes a generic talent releases covering:
- Image and video recording rights
- Usage permissions (commercial, promotional, social media)
- Worldwide, perpetual licensing
- No payment, royalties, or other compensation
- Guardian consent for minors
- Privacy notice compliance

**Note**: Consult with legal counsel to ensure terms meet your use case and jurisdiction's requirements.

## 🔧 Customization

### Talent Release Agreement
0. If Locked: Press and hold lock icon at top of screen
1. Click "Modify Talent Release Agreement"
3. Edit HTML content in the textarea (tip: use [text-html.com](https://text-html.com/) for easy HTML formatting)
4. Save changes to update both display and PDF output
5. Restore to default anytime
6. Historical preservation ensures PDFs always reflect the terms that were signed
7. Press and hold lock icon at top of screen to prevent changes.

## 🏗️ Technical Architecture

### Dependencies
- **jsPDF** - PDF generation
- **HTML5 Canvas** - Signature capture
- **MediaDevices API** - Camera access
- **Local Storage** - Data persistence
- **Service Worker** - PWA functionality

### Browser Support
- Chrome/Chromium 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## 🔒 Privacy & Security

- **No Data Transmission** - All data stays on the device
- **Local Storage Only** - No cloud storage or external APIs
- **No Tracking** - No analytics or third-party scripts
- **Offline Capable** - Works completely offline after first load

## 📈 Changelog

### v1.3.0 (Current)
- **NEW**: Upload custom logo
- **IMPROVED**: Lock button now locks persistant fields

### v1.2.0
- **NEW**: Ability to lock custom talent release agreement (press and hold)

### v1.1.0 (Current)
- **NEW**: Customizable talent release agreements with HTML editor
- **NEW**: Historical terms preservation in PDFs
- **NEW**: Form history management with clear functionality
- **IMPROVED**: PDF layout optimization and content density
- **FIXED**: Removed location tracking for better privacy
- **FIXED**: Signature overlap issues in PDF generation
- **ENHANCED**: Better error handling and data corruption protection

### v1.0.0 (Initial Release)
- Complete talent release functionality
- Digital signature capture (talent + witness)
- Photo capture with camera integration
- PDF generation with professional layout
- Form history with local storage
- PWA support with dark/light themes

*See [CHANGELOG.md](CHANGELOG.md) for complete version history*

## 🙏 Acknowledgments

**Created by**: [Jake Lodder](https://jakelodder.com.au)

Special thanks to:
- The open-source community for the underlying technologies
- Photographers and videographers who provided feedback during development
- Legal professionals who reviewed the default terms and conditions

---

*Built with ❤️ for the creative community*
