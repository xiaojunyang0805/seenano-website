# SeeNano.nl - Portfolio Website

**Personal portfolio for Xiaojun Yang / SeeNano Technology BV**

Live site: [seenano.nl](https://seenano.nl)

## About

Main portfolio showcasing Micro-SaaS products and research work:
- **ReceiptSort** (receiptsort.seenano.nl) - AI receipt organizer
- **StemBot** (stembot.seenano.nl) - Educational STEM chatbot
- **Biosensor Research** (sensor.seenano.nl) - Hardware & research portfolio
- **NanoSim** (nanosim.seenano.nl) - Planned simulation platform

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

### Deployed on Cloudflare Pages

**Current Setup:**
- GitHub Repo: `xiaojunyang0805/seenano-website`
- Auto-deploy on push to `main` branch
- Custom Domain: `seenano.nl`

**Deployment Steps:**
1. Push changes to GitHub: `git push`
2. Cloudflare Pages auto-deploys (1-2 minutes)
3. Changes live at seenano.nl

**Cloudflare Pages Settings:**
- Build command: (empty)
- Build output directory: `/`
- Root directory: (empty)

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
- ✅ "Why I Build" mission section with AI focus
- ✅ Status badges (Live, In Dev, Planned)
- ✅ Social links (Twitter, LinkedIn, GitHub, Reddit)
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

**Email:** support@seenano.nl
**Twitter:** [@XiaojunYang0805](https://twitter.com/XiaojunYang0805)
**LinkedIn:** [linkedin.com/in/xiaojun-yang-5066b0114](https://www.linkedin.com/in/xiaojun-yang-5066b0114)
**GitHub:** [github.com/xiaojunyang0805](https://github.com/xiaojunyang0805)
**Reddit:** [u/NanoSoftNL](https://reddit.com/u/NanoSoftNL)

## Recent Updates (Nov 2025)

### Major Changes:
1. ✅ Added "Why I Build" section with AI-focused mission statement
2. ✅ Updated contact information to support@seenano.nl
3. ✅ Fixed LinkedIn URL to correct profile
4. ✅ Updated footer to show direct email address
5. ✅ Improved project descriptions and status badges

## Credits

Built with assistance from Claude Code (Anthropic).
