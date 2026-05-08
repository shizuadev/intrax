# Intrax+ Intelligence

A modern, sleek network diagnostics tool built with vanilla JavaScript and glassmorphism design. Intrax+ provides real-time insights into your network performance with an elegant, interactive interface. 
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Features

✨ **Real-Time Network Diagnostics**
- Download speed measurement
- Upload speed measurement
- Latency (ping) analysis
- Connection type detection

🌍 **Global Edge Node Selection**
- Auto-detect optimal local server
- Manual selection from 7+ global locations
- Dynamic performance metrics based on target server

📊 **Advanced Telemetry**
- ISP and ASN information
- Public IPv4 address detection
- Client device and browser identification
- Connection type analysis (4G, 5G, WiFi, etc.)

🎨 **Premium UI/UX**
- Glassmorphism design with backdrop blur effects
- Smooth animations and transitions
- Responsive grid layout
- Real-time animated progress tracking
- Live clock and date display

⚙️ **Customizable Testing**
- Adjustable measurement duration (3, 5, 8, 15 seconds, or custom)
- Multiple fallback endpoints for reliability
- Animated metric counters with easing functions

## Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern glassmorphism design with CSS variables, animations, and Grid/Flexbox
- **Vanilla JavaScript** - No dependencies, pure ES6+ implementation
- **Geolocation APIs** - ipapi.co, Cloudflare Trace for location detection

## Getting Started

### Installation

1. Clone or download the repository
2. Simply open `main.html` in a modern web browser
3. No build process or dependencies required

```bash
git clone https://github.com/shizuadev/intrax.git
cd intrax
# Open main.html in your browser
```

### Usage

1. **Select Edge Node** - Choose from auto-detected optimal server or manually select a global location
2. **Configure Duration** - Set test duration (default: 8 seconds)
3. **Start Test** - Click "Start Diagnostic" button to begin testing
4. **View Results** - Watch real-time metrics and detailed telemetry data

## Project Structure

```
intrax/
├── main.html          # Complete application (HTML, CSS, JS)
└── README.md          # This file
```

## Key Components

### Header
- Brand logo with hover animation
- Live date and time display

### Control Panel
- Global network selector with auto-detection
- Server badge with connection status
- Primary action button with shine effect

### Metrics Display
- Download speed card
- Upload speed card
- Latency card
- Animated progress bar with shimmer effect

### Telemetry Section
- Selected node information
- Precise geolocation coordinates
- ISP/ASN details
- Public IP address
- Connection type
- Client device information

### Settings
- Customizable measurement duration
- Multiple test endpoint fallbacks

## Performance Features

- **No Dependencies** - Single HTML file, zero external libraries
- **Lightweight** - Minimal CSS and optimized JavaScript
- **Responsive** - Works seamlessly on desktop and mobile devices
- **Fallback Endpoints** - Multiple CDN sources for reliability
- **Smart Estimation** - Server location penalties and speed multipliers for realistic simulation

## Browser Support

- Chrome/Edge (88+)
- Firefox (87+)
- Safari (14+)
- Mobile browsers (iOS Safari, Chrome Mobile)

## API Integrations

- **ipapi.co** - Location and ISP detection
- **Cloudflare Trace** - Fallback geolocation
- **Cloudflare Speed** - Download/upload testing endpoints
- **OVH & httpbin** - Fallback test servers

## Customization

### Colors
Modify CSS variables in `:root` selector:
```css
:root {
  --accent-blue: #3b82f6;
  --accent-teal: #14b8a6;
  --accent-purple: #8b5cf6;
  /* ... */
}
```

### Animation Speed
Adjust timing in keyframes and transitions:
```css
.btn-run { transition: all 0.4s var(--ease-spring); }
```

### Test Duration
Default is 8 seconds. Configure via the duration selector in the UI.

## License

MIT License - feel free to use, modify, and distribute

## Author

**Shizua Dev**  
GitHub: [@shizuadev](https://github.com/shizuadev)

## Contributing

DM At @sakai.ss in discord for forking, please.

## Changelog

### v1.0.0
- Initial release
- Core diagnostics functionality
- Global edge node selection

---
⚠ README FILE IS MADE WITH AI BECAUSE TO MEET MY PERSONAL DEADLINE ⚠
**Made with ❤️**
