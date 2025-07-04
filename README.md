# DrawDash v1.0 - Modern Progressive Web Drawing Game

A cutting-edge, modern web-based drawing game built with the latest web technologies. Perfect for publishing on **Itch.io**, and **app stores** as a Progressive Web App (PWA). Features advanced multiplayer lobbies, training mode, and professional-grade drawing tools.

## 🚀 **What's in v1.0**

### ⚡ **Modern Architecture**
- **ES6+ JavaScript**: Modern class-based architecture with async/await
- **Progressive Web App**: Installable, offline-capable, app-like experience
- **Performance Optimized**: 60fps drawing, throttled events, intersection observers
- **Accessibility First**: WCAG compliant, keyboard shortcuts, screen reader support

### 🎨 **Enhanced Features**
- **Smart Drawing Engine**: Fixed coordinate precision, multi-touch support
- **Dynamic Difficulty**: Easy/Medium/Hard/Expert word categories
- **Real-time Notifications**: Modern toast notifications instead of alerts
- **Improved Lobbies**: Enhanced UI with animations and better UX
- **Sound System**: Advanced audio with Web Audio API

### 📱 **PWA Capabilities**
- **Install Prompt**: Native app installation on all devices
- **Offline Support**: Service Worker caching for offline play
- **Home Screen Icon**: Add to home screen on mobile devices
- **Background Sync**: Future-ready for real multiplayer features

## 🎮 Game Features

### 🔐 User System
- **Login Screen**: Simple username entry to get started
- **User Session**: Persistent username throughout the game

### 🏠 Lobby System
- **Lobby Browser**: View all available game lobbies
- **Create Lobby**: 
  - Custom lobby name
  - Optional password protection
  - Max player limit (2-8 players)
  - Language selection
  - Custom word lists
- **Join Lobbies**: Join public or password-protected lobbies
- **Lobby Room**: See players, chat, and start games (requires 2+ players)

### 🎨 Game Modes
- **Training Mode**: Practice drawing with random words
- **Multiplayer Game**: Draw and guess with other players
- **Real-time Chat**: Communicate and submit guesses

### 🖌️ Drawing Tools
- **Multiple Colors**: 8 color palette
- **Brush & Eraser**: Switch between drawing and erasing
- **Adjustable Size**: 1-20px brush size
- **Clear Canvas**: Reset your drawing
- **Touch Support**: Works on mobile devices

## 🚀 Deployment

### For Itch.io
1. Create a ZIP file with all game files
2. Upload as an HTML game
3. Set viewport to 1024x768 or use responsive mode
4. Enable fullscreen support

## 📱 Browser Compatibility

- **Desktop**: Chrome, Firefox, Safari, Edge
- **Mobile**: iOS Safari, Chrome Mobile, Samsung Internet
- **Touch Support**: Full touch and gesture support
- **Responsive**: Works on all screen sizes

## 🛠️ Technical Architecture

- **Modern ES6+ JavaScript**: Class-based architecture with modules
- **Progressive Web App**: Service Worker, Web App Manifest, offline support
- **Performance Optimized**: Throttled drawing, efficient event handling
- **Canvas API**: Hardware-accelerated 2D graphics with precision coordinates
- **Web Audio API**: Advanced sound system with pre-loading
- **CSS Custom Properties**: Dynamic theming and dark mode support
- **Intersection Observer**: Smooth animations and performance optimization
- **AbortController**: Modern event cleanup and memory management

## 📁 Modern File Structure

```
DrawDash-v2/
├── index.html          # Modern HTML5 with PWA meta tags
├── main.js            # ES6+ modular game logic  
├── styles.css         # Modern CSS with custom properties
├── sw.js              # Service Worker for PWA
├── manifest.json      # PWA manifest
├── Icon.ico          # App icon and favicon
├── bell.mp3          # Sound effects
├── ticking_clock.wav # Timer sounds
├── package.json      # Modern package config
└── README.md         # This documentation
```

## 🎯 Game Flow

1. **Login** → Enter username
2. **Main Menu** → View lobbies or create new one
3. **Create/Join Lobby** → Set up or join game room
4. **Lobby Room** → Wait for players, start when ready
5. **Training Mode** → Practice drawing random words
6. **Multiplayer Game** → Draw, guess, and chat with others

## 🎨 Customization

The game supports custom word lists in lobby creation, making it perfect for:
- **Educational Use**: Custom vocabulary lists
- **Themed Games**: Holiday or topic-specific words
- **Language Learning**: Words in different languages
- **Age Groups**: Age-appropriate word difficulty

## 🏆 Perfect For

- **Casual Gaming Platforms** (CrazyGames, Poki, etc.)
- **Educational Sites** (Schools, learning platforms)
- **Social Gaming** (Friends, family, online communities)
- **Mobile Gaming** (Touch-friendly interface)

## 📊 Performance

- **Fast Loading**: Minimal assets, quick startup
- **Smooth Drawing**: 60fps canvas rendering
- **Low Bandwidth**: Works on slow connections
- **Battery Efficient**: Optimized for mobile devices

---

**Play it now!** Play it now on itch.io via this link: https://paterik.itch.io/drawdash
