# Sagarmatha Investments - Next.js Website

A modern, responsive website for Sagarmatha Investments built with Next.js 14+, TypeScript, and Tailwind CSS.

## Features

- ⚡ **Next.js 14+** with App Router and TypeScript
- 🎨 **Tailwind CSS** with custom design system
- 🌙 **Dark/Light Theme** with system preference detection
- 📱 **Fully Responsive** design for all devices
- ♿ **Accessible** with proper ARIA labels and semantic HTML
- 🚀 **Performance Optimized** with image optimization and lazy loading
- 🔍 **SEO Optimized** with proper meta tags and structured data
- 📱 **PWA Ready** with service worker and manifest
- 📊 **Google Analytics 4** integration
- 🎯 **Modern UI/UX** with smooth animations and interactions

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd sagarmatha-investments
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```

Edit `.env.local` and add your Google Analytics Measurement ID:
```
NEXT_PUBLIC_GA_MEASUREMENT_ID=G-XXXXXXXXXX
```

4. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the website.

## Project Structure

```
src/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles and Tailwind config
│   ├── layout.tsx         # Root layout with metadata
│   ├── page.tsx           # Home page
│   ├── not-found.tsx      # 404 page
│   ├── robots.ts          # Robots.txt
│   └── sitemap.ts         # Sitemap generation
├── components/            # React components
│   ├── layout/           # Layout components (Navbar, Hero, Footer)
│   ├── sections/         # Page sections
│   ├── ui/               # Reusable UI components
│   ├── analytics.tsx     # Google Analytics
│   ├── pwa-registration.tsx # PWA service worker
│   └── theme-provider.tsx # Theme management
└── lib/                  # Utility functions
    └── utils.ts          # Helper functions
```

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy automatically

### Other Platforms

The app can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `NEXT_PUBLIC_GA_MEASUREMENT_ID` | Google Analytics 4 Measurement ID | No |
| `NEXT_PUBLIC_CONTACT_FORM_ENDPOINT` | Contact form submission endpoint | No |

## Performance

- Lighthouse Performance Score: 90+
- Optimized images with Next.js Image component
- Automatic code splitting and lazy loading
- Service worker for offline functionality
- Compressed assets and optimized bundles

## SEO Features

- Comprehensive meta tags and Open Graph
- Structured data (JSON-LD) for financial services
- Automatic sitemap generation
- Robots.txt configuration
- Semantic HTML structure

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

For support, email info@sagarmathainvestments.com or call +977-9876543211.