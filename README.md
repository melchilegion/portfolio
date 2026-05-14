# Chief Decision Architect - Portfolio

> AI Systems & Strategic Innovation Platform

## Overview

A modern, high-performance portfolio showcasing Melchisedec Nyapson's work as a Chief Decision Architect specializing in AI systems, predictive analytics, and strategic innovation.

## Features

✨ **Modern Design**
- Dark theme with cyan/indigo/purple accents
- Smooth animations and transitions
- Glassmorphism UI elements
- Responsive mobile-first design

⚡ **Performance**
- Built with Next.js 14 for optimal performance
- SEO optimized with metadata
- Core Web Vitals optimized
- Image optimization

🎯 **Interactive Elements**
- Smooth scroll navigation
- Mobile hamburger menu
- Staggered animations
- Scroll-to-top button
- Hover effects on all interactive components

♿ **Accessibility**
- WCAG 2.1 compliant
- Keyboard navigation
- ARIA labels
- Semantic HTML

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Deployment**: Vercel
- **CI/CD**: GitHub Actions

## Getting Started

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/melchilegion/portfolio.git
cd portfolio

# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Build for Production

```bash
npm run build
npm start
```

## Deployment

### Option 1: Deploy to Vercel (Recommended)

```bash
npm i -g vercel
vercel
```

### Option 2: Vercel GitHub Integration

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Select your GitHub repository
4. Click "Deploy"

### Option 3: GitHub Actions (Automatic)

Add these secrets to your GitHub repository:
- `VERCEL_TOKEN` - Get from [Vercel Settings](https://vercel.com/account/tokens)
- `VERCEL_ORG_ID` - Your Vercel organization ID
- `VERCEL_PROJECT_ID` - Your Vercel project ID

## File Structure

```
portfolio/
├── app/
│   ├── layout.tsx          # Root layout with metadata
│   ├── page.tsx            # Main portfolio page
│   └── globals.css         # Global styles and animations
├── public/                 # Static assets
├── package.json            # Dependencies
├── tailwind.config.ts      # Tailwind configuration
├── tsconfig.json           # TypeScript configuration
├── next.config.js          # Next.js configuration
├── postcss.config.js       # PostCSS configuration
├── vercel.json             # Vercel deployment config
└── .github/workflows/
    └── deploy.yml          # GitHub Actions CI/CD
```

## Customization

### Update Personal Information

Edit `app/page.tsx`:
- Update email in contact section (line ~231)
- Add social media links
- Update project descriptions
- Modify skills list

### Customize Colors

Edit `tailwind.config.ts` to change the color scheme.

### Add More Projects

Add items to the `projects` array in `app/page.tsx`.

## Performance Metrics

- ✅ Lighthouse Performance: 95+
- ✅ Lighthouse Accessibility: 95+
- ✅ Lighthouse Best Practices: 95+
- ✅ Lighthouse SEO: 100

## SEO Optimization

- Meta tags for all social platforms
- Open Graph tags
- Twitter Card support
- Structured data ready
- Sitemap compatible

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## License

MIT License - feel free to use this template for your own portfolio.

## Support

For issues or questions, please open a GitHub issue.

---

**Built with ❤️ by Melchisedec Nyapson**