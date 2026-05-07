# Resilience Atlas Website

## Overview

This is the production-ready landing page for Resilience Atlas. It's a static HTML site designed for easy deployment and fast loading.

## Features

- ✅ Mobile-responsive design
- ✅ PAS framework copy structure
- ✅ Newsletter signup form (Beehiiv-ready)
- ✅ Pricing table with 3 tiers
- ✅ FAQ section
- ✅ Testimonials
- ✅ SEO optimized
- ✅ Fast loading (no heavy frameworks)

## File Structure

```
05-website/
├── index.html          # Main landing page
├── package.json        # Project metadata
├── README.md          # This file
└── assets/            # (Optional) Images, fonts, etc.
```

## Setup Instructions

### 1. Configure Newsletter Signup

Replace `YOUR_BEEHIIV_FORM_URL` in the signup form with your actual Beehiiv signup URL:

```html
<form action="https://your-beehiiv-form-url" method="post" target="_blank">
```

To get your Beehiiv form URL:
1. Go to Beehiiv dashboard
2. Navigate to Settings > Subscribe Form
3. Copy the form action URL

### 2. Update Contact Information

Replace placeholder contact info:
- Email: `hello@resilienceatlas.co` → Your actual email
- Social links in footer
- Any other contact details

### 3. Add Testimonials (Optional)

Replace the sample testimonials with real ones as you collect them.

### 4. Customize Branding (Optional)

Update in the CSS `:root` section:
- `--primary`: Main brand color (currently forest green)
- `--accent`: Accent color (currently gold)
- Fonts: Currently Inter + Merriweather

## Deployment

### Option 1: Vercel (Recommended)

1. Push to GitHub
2. Connect Vercel to your repo
3. Deploy automatically

```bash
# Using Vercel CLI
npm i -g vercel
vercel --prod
```

### Option 2: Netlify

1. Drag and drop the `05-website` folder to Netlify
2. Or connect GitHub repo for auto-deploy

### Option 3: Any Static Host

Upload `index.html` to any web host:
- GitHub Pages
- Cloudflare Pages
- AWS S3
- Traditional hosting

## Post-Deployment Checklist

- [ ] Test signup form works
- [ ] Test on mobile device
- [ ] Verify all links work
- [ ] Check page load speed
- [ ] Set up Google Analytics
- [ ] Set up custom domain
- [ ] Test social sharing (Open Graph)

## Integration Points

### Beehiiv Integration
The signup form is ready for Beehiiv. Just update the form action URL.

### Stripe Integration (Future)
When ready to add payments:
1. Create Stripe account
2. Add Stripe payment links or embed
3. Update pricing buttons to point to Stripe checkout

### Custom Report Inquiries
The "Learn More" button for custom reports should link to:
- Typeform/Google Forms questionnaire
- Or a contact page with intake form

## Performance

- No JavaScript frameworks (fast loading)
- Minimal CSS (inline for critical styles)
- Responsive images (when added)
- Mobile-first design

Expected Lighthouse scores:
- Performance: 95+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 95+

## Maintenance

### Regular Updates
- Update testimonials as you collect them
- Refresh social proof numbers (subscriber count)
- A/B test headline variations
- Update FAQ based on common questions

### Seasonal Updates
- Refresh hero messaging for current events
- Update examples to stay relevant
- Add seasonal preparedness content

## A/B Testing Ideas

Test these elements to improve conversion:
1. Hero headline (4 variations provided)
2. CTA button text
3. Pricing presentation order
4. Testimonial placement
5. Social proof placement

## Support

For questions about the website, contact: hello@resilienceatlas.co

---

*Website Version: 1.0*
*Created: 2026-05-07*
*Status: Production Ready*
