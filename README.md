# 🐧 Penguin World

A sleek, modern mobile web application about penguins with a glacier-themed, liquid glassmorphic design.

## Features

- **Interactive Penguin Gallery** - Explore 4 featured penguin species
- **Smooth Carousel** - Swipe through amazing penguin facts
- **Detailed Species Information** - Height, weight, diet, habitat, and behavior
- **Responsive Design** - Optimized for mobile devices (375px+)
- **Modern UI** - Liquid glassmorphic design with frosted glass effects
- **Smooth Animations** - Touch-friendly interactions and transitions

## Design

- **Theme**: Glacier-inspired with cool blues and icy accents
- **Color Palette**: 
  - Background: Deep blues (#0f1419 - #1a3a52)
  - Accent: Glacier cyan (#4dd0e1, #00e5ff)
  - Glass Effect: Backdrop blur and semi-transparent overlays

## Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Glassmorphism, gradients, animations
- **Vanilla JavaScript** - No dependencies

## How to Run

### Option 1: Direct File
```bash
open /Users/bart/Desktop/"mom game"/index.html
```

### Option 2: Local Server
```bash
cd /Users/bart/Desktop/"mom game"
python3 -m http.server 8000
```
Then visit `http://localhost:8000`

### Option 3: Live Server (VS Code)
Right-click `index.html` → "Open with Live Server"

## Mobile Testing

Use Chrome DevTools:
1. Press F12 (Cmd+Option+I on Mac)
2. Click the device toggle icon
3. Select a mobile device preset

## File Structure

```
mom game/
├── index.html       # Main HTML structure
├── styles.css       # Glassmorphic styling
├── script.js        # Interactive functionality
└── README.md        # This file
```

## Features

### Tabs
- **Explore** - Browse featured penguin species
- **Facts** - Carousel of amazing penguin facts
- **About** - Learn more about penguin conservation

### Species Modal
Click any penguin card to open detailed information with:
- Species name and illustration
- Physical stats (height, weight, diet)
- Behavior and habitat information
- Tab navigation for facts/habitat

### Carousel
- Auto-rotating facts with manual controls
- Swipe support for touch devices
- Keyboard navigation (arrow keys)
- Dot indicators for current slide

## Created By

Anon360-CODER

## License

MIT
