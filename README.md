# SeeNano.nl - Portfolio Website

**Personal portfolio for Xiaojun Yang / SeeNano Technology BV**

## About

Card-based portfolio showcasing Micro-SaaS products and research work:
- ReceiptSort (receiptsort.seenano.nl)
- StemBot (stembot.seenano.nl)
- Biosensor Research (sensor.seenano.nl)
- NanoSim (nanosim.seenano.nl)

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Static site (no build process)

## Structure

```
seenano-site/
├── index.html          # Main portfolio page
├── images/             # Project screenshots
│   ├── receiptsort-screenshot.png
│   ├── stembot-screenshot.png
│   ├── sensor-photo.jpg
│   └── nanosim-placeholder.png
├── README.md           # This file
└── .gitignore
```

## Local Development

Simply open `index.html` in your browser. No build process needed.

```bash
# Option 1: Double-click index.html

# Option 2: Use Python simple server
python -m http.server 8000

# Option 3: Use VS Code Live Server extension
```

## Deployment

### To Cloudflare Pages:

1. Push to GitHub
2. Connect repo to Cloudflare Pages
3. Configure:
   - Build command: (leave empty)
   - Build output directory: /
   - Root directory: (leave empty)
4. Deploy

### To Netlify (Alternative):

1. Push to GitHub
2. Connect repo to Netlify
3. Build settings:
   - Build command: (leave empty)
   - Publish directory: .
4. Deploy

## Custom Domain

Point `seenano.nl` to Cloudflare Pages:
- CNAME: www → [project-name].pages.dev
- CNAME: @ → [project-name].pages.dev

## Images

### Required Images:

Place these in `/images` folder:

1. **receiptsort-screenshot.png** (1200x675px)
   - Screenshot of ReceiptSort landing page
   - Compress to ~200KB

2. **stembot-screenshot.png** (1200x675px)
   - Screenshot of StemBot landing page
   - Compress to ~200KB

3. **sensor-photo.jpg** (1200x675px)
   - Lab photo or research visual
   - Compress to ~200KB

4. **nanosim-placeholder.png** (1200x675px)
   - Placeholder image
   - Compress to ~200KB

### Image Optimization:

Use https://tinypng.com or similar tools to compress images.

## Features

- ✅ Responsive design (mobile-first)
- ✅ Card-based project showcase
- ✅ Smooth scroll navigation
- ✅ Hover animations
- ✅ Status badges (Live, In Dev, Planned)
- ✅ Social links
- ✅ SEO optimized
- ✅ Fast loading (<1 second)
- ✅ No build process (simple deployment)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

Target metrics:
- PageSpeed Score: 95+
- First Contentful Paint: <1s
- Largest Contentful Paint: <2s
- Time to Interactive: <2s

## License

© 2025 SeeNano Technology BV. All rights reserved.

## Contact

- Email: xiaojun@seenano.nl
- Twitter: @XiaojunYang0805
- LinkedIn: xiaojunyang
- Reddit: u/NanoSoftNL
