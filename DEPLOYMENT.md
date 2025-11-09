# Deploying developingbaseball.com

This is a **static website** - a professional marketing site that explains your services. It's ready to deploy to any static hosting service.

## Quick Deploy Options

### Option 1: Netlify (Recommended - Easiest)
1. Go to [netlify.com](https://netlify.com) and sign up/login (free)
2. Drag and drop your `developingbaseball` folder onto the Netlify dashboard
3. Your site will be live immediately with a temporary URL
4. Go to **Site settings → Domain management → Add custom domain**
5. Enter: `developingbaseball.com`
6. Netlify will show you DNS instructions

### Option 2: Vercel (Also Great)
1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "Add New Project"
3. Drag and drop your folder or connect GitHub
4. After deployment, go to **Settings → Domains**
5. Add: `developingbaseball.com`

### Option 3: Cloudflare Pages (Free)
1. Sign up at [cloudflare.com](https://cloudflare.com)
2. Go to **Pages → Create a project**
3. Upload your files or connect GitHub
4. Add custom domain in project settings

## DNS Setup

After adding your domain on your hosting platform, you'll need to update DNS records at your domain registrar (where you bought developingbaseball.com).

### For Netlify:
- **A Record**: `@` → `75.2.60.5`
- **CNAME Record**: `www` → `[your-site].netlify.app` (or use Netlify's provided value)

### For Vercel:
- **A Record**: `@` → `76.76.21.21`
- **CNAME Record**: `www` → `cname.vercel-dns.com`

The hosting platform will give you exact DNS values when you add your domain - just copy and paste them at your registrar.

## Steps to Deploy Now:

1. **Choose Netlify** (easiest option)
2. **Drag and drop** your folder onto netlify.com
3. **Add your domain** in Netlify settings
4. **Update DNS** at your domain registrar
5. **Wait 5-30 minutes** for DNS to propagate

Your site will be live at developingbaseball.com!

