# Mobile Apps Showcase

A beautiful, fast, and SEO-optimized landing page for showcasing your mobile apps built with Astro and Tailwind CSS.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The site will be available at `http://localhost:4321`

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── AppCard.astro
│   │   └── Footer.astro
│   ├── data/
│   │   └── apps.json          # Edit this to update your apps
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       └── privacy.astro
├── astro.config.mjs
├── tailwind.config.cjs
└── package.json
```

## ✏️ Customization

### Adding/Editing Apps

Edit `src/data/apps.json`:

```json
{
  "name": "Your App Name",
  "tagline": "Short tagline",
  "description": "Longer description",
  "icon": "📱",
  "appStoreUrl": "https://apps.apple.com/...",
  "playStoreUrl": "https://play.google.com/...",
  "features": ["Feature 1", "Feature 2", "Feature 3"]
}
```

### Updating Personal Info

1. **Header**: Edit `src/components/Header.astro` - change "Your Name"
2. **Footer**: Edit `src/components/Footer.astro` - update social links and email
3. **Hero**: Edit `src/components/Hero.astro` - customize headline and description
4. **Colors**: Edit `tailwind.config.cjs` to change primary/secondary colors

### SEO

Update in `astro.config.mjs`:
- Set your domain in `site` field

Update in `src/layouts/Layout.astro`:
- Meta descriptions
- Open Graph tags

## 🌐 Deployment

### Deploy to Netlify (Recommended - Free)

1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Connect your GitHub repo
5. Build settings are auto-detected
6. Deploy!

### Deploy to Vercel (Also Free)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your repository
5. Deploy!

Both platforms offer:
- Free SSL certificates
- Automatic deployments on git push
- CDN distribution
- Custom domains

## 📱 Features

- ✅ Fully responsive design
- ✅ SEO optimized
- ✅ Fast loading (< 1 second)
- ✅ Easy to update (just edit JSON file)
- ✅ Privacy policy page
- ✅ Smooth animations
- ✅ App Store & Play Store links
- ✅ Modern design

## 🎨 Customization Tips

**Change colors**: Edit `tailwind.config.cjs`
**Change fonts**: Import in `src/layouts/Layout.astro`
**Add analytics**: Add script in `src/layouts/Layout.astro`
**Add more pages**: Create new `.astro` files in `src/pages/`

## 📄 License

Free to use for your personal projects!
