# Countdown to Candela

A romantic advent-style countdown calendar for March 1st, 2026 - Santa Teresa, Costa Rica.

## Features

- Live countdown timer to the reunion date
- 28 flip cards, one for each day from Feb 1st to Feb 28th
- Each day reveals a memory, quote, or photo from your relationship
- Days unlock based on the current date (can't peek ahead!)
- Remembers which days you've already opened
- Beautiful starry night design
- Mobile responsive

## Quick Deploy Options

### 1. GitHub Pages (Free & Easy)

```bash
# Initialize git and push to GitHub
cd candela-countdown
git init
git add .
git commit -m "Initial commit: Countdown to Candela"
gh repo create candela-countdown --public --push --source .

# Go to GitHub repo Settings > Pages > Source: main branch
# Your site will be at: https://yourusername.github.io/candela-countdown/
```

### 2. Netlify (Drag & Drop)

1. Go to [netlify.com](https://netlify.com)
2. Sign up/login
3. Drag the entire `candela-countdown` folder onto the deploy area
4. Done! You'll get a public URL instantly

### 3. Vercel

```bash
npx vercel
```

### 4. Local Testing

```bash
# Open directly in browser
open index.html

# Or use a simple server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

Edit `index.html` to customize:
- Quotes and memories in the `calendarData` array
- Target date (currently March 1, 2026)
- Colors and styling in the CSS
- Add more photos to the `images/` folder

## Made with love

"You are my soulmate. I've never felt that before about anyone. NEVER."

Te amo, mi pedazo de linda
