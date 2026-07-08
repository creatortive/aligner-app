# Aligner Tracker

Track your orthodontic aligner wear time with daily logging and Excel export.

## Features
- ⏱️ Real-time timer with visual ring indicator
- 📅 Daily session tracking
- 📊 Excel export functionality
- 💾 Data persistence with localStorage
- 🎨 Dark mode UI

## Quick Start

### Local Development
```bash
npm install
npm start
```

The app will open at `http://localhost:3000`

### Build for Production
```bash
npm run build
```

## Deploy

### Vercel (Recommended)
1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Click Deploy

### GitHub Pages
```bash
npm run build
# Deploy the build/ folder to GitHub Pages
```

## Usage
1. Enter your current aligner set name (optional)
2. Press **Start** to begin tracking for the day
3. Press **Pause** to pause within a day
4. Press **Resume** to continue
5. Press **Stop** to end the day
6. Click **Export Excel** to download your wear log

## Technologies
- React 18
- XLSX (Excel export)
- localStorage (data persistence)
