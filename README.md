# Minimalist Timer

A lightweight, single-purpose countdown timer built with pure JavaScript. Features a clean design with an ad-ready architecture that doesn't compromise user experience.

## Features

- ⏱️ **Countdown Timer** - Set custom timers with hours, minutes, and seconds
- 🔔 **Smart Notifications** - Browser notifications when timer reaches zero
- 🔊 **Audio Alerts** - Pleasant beep sounds using Web Audio API
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- 🎨 **Dark Mode Design** - Easy on the eyes with modern aesthetics
- 💰 **Ad-Ready Architecture** - Strategic ad placement without hurting UX
- 🚀 **Zero Dependencies** - Pure HTML, CSS, and JavaScript
- 🪶 **Ultra Lightweight** - Single HTML file (~7KB)

## Demo

[Live Demo](https://minimalist-timer-counter.vercel.app/) *(Add your GitHub Pages link here)*

## Screenshots

*Add screenshots here*

## Quick Start

### Option 1: Direct Download
1. Download `index.html`
2. Open in any modern web browser
3. Start using immediately

### Option 2: GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select main branch as source
4. Access at `https://yourusername.github.io/minimalist-timer`

### Option 3: Local Development
```bash
git clone https://github.com/yourusername/minimalist-timer.git
cd minimalist-timer
# Open index.html in your browser
```

## Usage

### Setting Up a Timer
1. Enter your desired time using the input fields (hours:minutes:seconds)
2. Click **Start** to begin the countdown
3. Click **Pause** to temporarily stop
4. Click **Reset** to return to your set time

### Notifications
The timer will notify you when it reaches zero through:
- **Browser Notification** - System notification (you'll be asked for permission on first use)
- **Audio Alert** - Two pleasant beep sounds
- **Pop-up Alert** - Visual confirmation message

> **Note:** For browser notifications to work, you must grant permission when prompted on your first interaction with the page.

## Ad Integration

The template includes strategic ad placements:

- **Left Sidebar**: 160×600 (Skyscraper)
- **Right Sidebar**: 160×600 (Skyscraper)
- **Bottom**: 728×90 (Leaderboard) or responsive

### Adding Google AdSense

Replace the ad slot placeholders with your ad code:

```html
<!-- Example: Left Ad Slot -->
<aside class="ad-slot left">
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
  <ins class="adsbygoogle"
       style="display:block"
       data-ad-client="ca-pub-XXXXXXXXXX"
       data-ad-slot="XXXXXXXXXX"
       data-ad-format="auto"></ins>
  <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
</aside>
```

## Template Duplication

This tool is designed to be easily duplicated for other single-purpose utilities:

### Steps to Create a New Tool

1. **Copy the file**
   ```bash
   cp index.html new-tool.html
   ```

2. **Update the header**
   ```html
   <header><h1>Your New Tool Name</h1></header>
   ```

3. **Replace tool content**
   - Update the `.tool` section with your new UI
   - Modify the JavaScript logic for your tool's functionality
   - Keep the same ad slot structure for consistency

4. **Test responsiveness** on different devices

### Example Tool Ideas
- Pomodoro Timer (add work/break cycles)
- Stopwatch (count up instead of down)
- Word Counter
- Unit Converter
- Random Number Generator
- Color Picker
- Password Generator
- BMI Calculator

## Browser Support

Works on all modern browsers that support:
- Web Audio API
- Notification API
- ES6+ JavaScript

**Tested on:**
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

**Note:** Notification permissions must be granted by the user for system notifications to work.

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid and Flexbox
- **Vanilla JavaScript** - No frameworks or dependencies

## Project Structure

```
minimalist-timer/
│
├── index.html          # Single-file application
├── README.md           # This file
├── LICENSE             # MIT License
```

## Customization

### Colors
Edit the CSS variables in the `<style>` section:

```css
/* Dark theme colors */
background: #0f0f0f;  /* Main background */
background: #1a1a1a;  /* Card background */
color: #4a9eff;       /* Primary accent */
```

### Layout
Modify the grid template in `.container`:

```css
.container {
  grid-template-columns: 1fr minmax(320px, 800px) 1fr;
}
```

### Font
Change the font family:

```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, ...;
```

## Performance

- **File Size**: ~7KB (uncompressed)
- **Load Time**: < 100ms on average connection
- **No External Dependencies**: Instant loading, no CDN delays
- **Browser APIs Used**: 
  - Web Audio API for sound notifications
  - Notification API for system alerts
  - No external audio files required

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by minimalist design principles
- Built for developers who need quick, monetizable tools
- Perfect for learning web development basics

## Support

If you find this project helpful, consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 📢 Sharing with others

---

Made with ❤️ for developers who appreciate simplicity
