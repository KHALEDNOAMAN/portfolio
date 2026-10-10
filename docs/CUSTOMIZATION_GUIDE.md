# Portfolio - Customization Guide

## How to Make It Yours

### 1. Personal Info
Update your name, bio, and social links in the config file.

### 2. Projects Section
| Field | Description |
|-------|-------------|
| title | Project name |
| description | Short description |
| image | Screenshot/preview |
| tech | Technologies used |
| github | Repository link |
| live | Live demo URL |

### 3. Skills
Add/remove skill icons and labels in the skills component.

### 4. Theme Colors
Edit CSS variables to match your brand:
```css
:root {
  --primary: #6366f1;
  --secondary: #8b5cf6;
  --background: #0f172a;
  --text: #e2e8f0;
}
```

## Deployment
| Platform | Command |
|----------|---------|
| Vercel | vercel deploy |
| Netlify | netlify deploy --prod |
| GitHub Pages | npm run build + deploy |

## Performance Tips
- Optimize images (WebP format)
- Lazy load below-fold sections
- Use responsive breakpoints