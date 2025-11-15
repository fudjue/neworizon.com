# New Horizon - Tech Website

A modern, responsive tech company website built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern, gradient-based design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🎯 Interactive navigation
- 📧 Contact form with validation
- 🚀 Lightweight and fast loading

## Project Structure

```
neworizon.com/
├── index.html       # Main HTML file
├── styles.css       # CSS styles
├── script.js        # JavaScript functionality
├── package.json     # Project metadata
├── vercel.json      # Vercel deployment config
├── netlify.toml     # Netlify deployment config
└── README.md        # This file
```

## Running Locally

### Option 1: Python HTTP Server
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000 in your browser.

### Option 2: Using npm
```bash
npm start
```

## Deployment Options

### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to complete deployment.

### Deploy to Netlify

1. Install Netlify CLI:
```bash
npm i -g netlify-cli
```

2. Deploy:
```bash
netlify deploy
```

3. For production:
```bash
netlify deploy --prod
```

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select branch (main) and folder (root)
4. Click Save

Your site will be available at: `https://yourusername.github.io/neworizon.com`

### Deploy to Surge

1. Install Surge:
```bash
npm i -g surge
```

2. Deploy:
```bash
surge
```

## Customization

- **Colors**: Edit CSS variables in `styles.css` (lines 7-13)
- **Content**: Modify text in `index.html`
- **Animations**: Adjust transitions in `styles.css`
- **Functionality**: Add features in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this template for your projects!