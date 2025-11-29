# Minimalist Timer Counter

A lightweight, single-purpose web tool built with pure JavaScript. Features a clean design with an ad-ready architecture that doesn't compromise user experience.

## Features

- ⏱️ **Timer** - Set custom countdown timers with hours, minutes, and seconds
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- 🎨 **Dark Mode Design** - Easy on the eyes with modern aesthetics
- 💰 **Ad-Ready Architecture** - Strategic ad placement without hurting UX
- 🚀 **Zero Dependencies** - Pure HTML, CSS, and JavaScript

## Demo

[Live Demo](https://minimalist-timer-counter.vercel.app/) *(Add your GitHub Pages link here)*

## Screenshots

![](https://github.com/user-attachments/assets/326f941f-3565-483f-91fd-ec6ade64a122)

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

### Timer
1. Set your desired time using the input fields (hours:minutes:seconds)
2. Click **Start** to begin countdown
3. Click **Pause** to temporarily stop
4. Click **Reset** to return to your set time

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
   <header h1>Your New Tool Name</h1>
   ```

3. **Modify tabs** (optional - keep tabs for multiple modes or remove for single function)

4. **Replace tool content**
   - Update the `.tool` section with your new UI
   - Modify the JavaScript logic
   - Keep the same ad slot structure

5. **Test responsiveness** on different devices

### Example Tool Ideas
- Pomodoro Timer
- Stopwatch
- Word Counter
- Unit Converter
- Random Number Generator
- Color Picker
- Password Generator

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

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

- **File Size**: ~8KB (uncompressed)
- **Load Time**: < 100ms on average connection
- **No External Dependencies**: Instant loading, no CDN delays

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
