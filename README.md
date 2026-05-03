# Your Blog - Astro + Decap CMS

A beautiful, fast blog built with Astro and Decap CMS. Deploy in minutes, publish from a visual dashboard.

## Features

- ⚡ **Lightning fast** - Static HTML, zero client-side JavaScript overhead
- 📝 **Visual editing** - Decap CMS dashboard at `/admin`
- 🖼️ **Image optimization** - Automatic WebP conversion, lazy loading, responsive sizes
- 🎨 **Beautiful design** - Clean white theme with thoughtful interactions
- 📱 **Responsive** - Works perfectly on mobile, tablet, and desktop
- 🚀 **Easy deployment** - One-click deploy to Netlify

## Quick Start

### 1. Fork this repository

Click the "Fork" button on GitHub to create your own copy.

### 2. Create a Netlify account (free)

Go to [netlify.com](https://netlify.com) and sign up with GitHub.

### 3. Deploy to Netlify

1. Click "New site from Git"
2. Select your forked repository
3. Click "Deploy"

Netlify will build and deploy your site automatically. You'll get a live URL like `https://your-site.netlify.app`

### 4. Set up Git Gateway (enables the CMS)

1. In Netlify dashboard, go to Site Settings → Access Control
2. Scroll to "OAuth" section
3. Click "Install the Netlify app on GitHub"
4. Authorize and complete the setup

### 5. Access your CMS

Visit `yoursite.netlify.app/admin` and log in with GitHub.

### 6. Create your first post

Click "New Blog Post" and start writing. When you hit "Publish", it:
- Commits to your GitHub repository
- Triggers a Netlify rebuild
- Deploys your new post live

## Customization

### Update site title and description

Edit `src/pages/index.astro`:
```astro
const title = "Your Name";
const description = "Your bio here...";
```

### Connect your domain

In Netlify Site Settings → Domain Management:
1. Add your domain (aandrewkeller.com)
2. Update DNS records in Namecheap to point to Netlify

See [Netlify docs](https://docs.netlify.com/domains-https/custom-domains/) for detailed instructions.

### Add images

In the Decap CMS editor, drag and drop images directly into the post. Images are automatically:
- Optimized (converted to WebP)
- Lazy loaded
- Served at the right resolution for each device

## Local Development

Want to develop locally? (Requires Node.js 18+)

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

Visit `http://localhost:3000` to preview.

## Migrating from Publii

1. Export your posts from Publii (Posts → Export)
2. In Decap CMS, create new posts and paste your content
3. The editor will format everything beautifully

## Need help?

- [Astro docs](https://docs.astro.build)
- [Decap CMS docs](https://decapcms.org/docs)
- [Netlify docs](https://docs.netlify.com)

---

Built with ❤️ using Astro, Decap CMS, and Netlify.
