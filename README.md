# KOSMO Landing Page

Production-ready landing page for KOSMO — your personal assistant on WhatsApp.

## ✨ Features

- **Single HTML file** — No build process, no dependencies
- **Mobile-first design** — Optimized for WhatsApp users on phones
- **Glass morphism effects** — Modern, Apple-inspired aesthetics
- **Smooth animations** — Subtle, performant transitions
- **SEO optimized** — Meta tags, semantic HTML, fast loading
- **Fully responsive** — Beautiful on all screen sizes

## 🎨 Design

- **Colors**: Deep Blue (#0A1F44), Electric Violet (#7B68EE), Warm Coral (#FF6B6B)
- **Font**: Inter from Google Fonts
- **Style**: Apple meets Italian craftsmanship

## 🚀 Deploy to Vercel (Recommended)

### Option 1: Vercel CLI (Fastest)

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy from this directory:
```bash
cd ~/clawd/kosmo-landing
vercel
```

3. Follow the prompts:
   - **Set up and deploy?** Y
   - **Which scope?** (Select your account)
   - **Link to existing project?** N
   - **Project name?** kosmo-landing (or your choice)
   - **Directory?** ./
   - **Override settings?** N

4. Done! Vercel will give you a live URL (e.g., `kosmo-landing.vercel.app`)

### Option 2: Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Click **Add New** → **Project**
3. Click **Continue with GitHub** (or drag & drop the `kosmo-landing` folder)
4. Import this directory
5. Click **Deploy**

That's it! No build configuration needed — it's a static HTML file.

## 🌐 Custom Domain

To add your domain (e.g., `kosmo.app`):

1. Go to your Vercel project dashboard
2. Click **Settings** → **Domains**
3. Add your domain (e.g., `kosmo.app`)
4. Update DNS records as instructed by Vercel:
   - For root domain (`kosmo.app`): Add A record to `76.76.21.21`
   - For `www`: Add CNAME to `cname.vercel-dns.com`

Vercel automatically provisions SSL certificates.

## 📝 Sections

1. **Hero** — Headline, subheadline, CTA, WhatsApp chat mockup
2. **Problem** — 3 pain points (fatture, email chaos, scadenze)
3. **Solution** — WhatsApp conversation demo + 6 capabilities
4. **How it works** — 3 simple steps
5. **Use cases** — 6 profession cards (musicisti, fotografi, designer, commercialisti, ristoratori, avvocati)
6. **Pricing** — 3 tiers with annual toggle (€99, €199, €399)
7. **Testimonials** — 3 quotes + stats bar
8. **FAQ** — 12 questions with accordion
9. **Final CTA** — Big conversion push
10. **Footer** — Links, legal, social

## 🛠 Customization

All styles are inline in the `<style>` tag. To modify:

- **Colors**: Change CSS variables in `:root`
- **Content**: Edit HTML directly (Italian text throughout)
- **Pricing**: Update in the `#pricing` section (already set to €99/€199/€399)
- **CTA links**: Replace `href="#"` with actual sign-up URLs

## 🔧 Local Development

No build tools needed! Just open the file:

```bash
open index.html
# or
python3 -m http.server 8000  # then visit localhost:8000
```

## 📊 Performance

- **No external dependencies** (except Google Fonts)
- **No images** — Uses CSS gradients and emoji
- **Inline CSS** — No render-blocking stylesheets
- **Minimal JS** — Only smooth scroll, accordion, pricing toggle
- **Fast loading** — Optimized for mobile networks

## 📱 Testing

Test on real devices (WhatsApp users = mobile):
- iOS Safari
- Android Chrome
- WhatsApp in-app browser

## 🎯 Next Steps

1. Replace placeholder CTAs (`href="#"`) with actual sign-up links
2. Add real social media URLs in footer
3. Set up analytics (Google Analytics, Plausible, etc.)
4. Create OG image (`og-image.png`) for social sharing
5. Configure domain and SSL

## 💡 Tips

- **First impression matters** — This page is clean, fast, and beautiful
- **Mobile-first** — Most traffic will come from WhatsApp (phones)
- **Clear CTAs** — Multiple conversion points throughout
- **Social proof** — Testimonials and stats build trust

---

**Made with ❤️ for KOSMO**  
Questions? Issues? Edit and redeploy — it's just one HTML file!
