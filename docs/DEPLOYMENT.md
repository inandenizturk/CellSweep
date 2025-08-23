# Deployment Guide

This document explains how to deploy CellSweep to various platforms.

## GitHub Pages (Recommended)

CellSweep is configured for automatic deployment to GitHub Pages.

### Automatic Deployment
1. Push changes to the `main` branch
2. GitHub Actions will automatically deploy to GitHub Pages
3. Site will be available at `https://yourusername.github.io/CellSweep/`

### Manual Deployment
```bash
npm install
npm run deploy
```

## Local Development Server

### Using Node.js
```bash
npm start
# Opens on http://localhost:8000
```

### Using Python
```bash
python3 -m http.server 8000
# Opens on http://localhost:8000
```

### Using PHP
```bash
php -S localhost:8000
# Opens on http://localhost:8000
```

## Custom Domain Setup

1. Add your domain to the `cname` field in `.github/workflows/deploy.yml`
2. Configure DNS records to point to GitHub Pages
3. Enable HTTPS in repository settings

## Environment Variables

No environment variables are required for basic deployment. The game runs entirely client-side.

## HTTPS Requirements

Solana wallet integration requires HTTPS in production. GitHub Pages provides HTTPS automatically.

## Performance Optimization

- All assets are embedded in HTML files
- No external dependencies except Solana Web3.js
- Optimized for fast loading and minimal bandwidth

## Troubleshooting

### Common Issues

1. **Wallet not connecting**: Ensure HTTPS is enabled
2. **Game not loading**: Check browser console for errors
3. **Mobile issues**: Verify viewport meta tag is present

### Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

Mobile browsers with Web3 wallet support recommended for full functionality.
