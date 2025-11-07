# Claim Tools AI - Deployment Checklist

## ✅ Completed

### Pages Created
- ✅ `/index.html` - Main landing page with all 20+ products
- ✅ `/get-claim-navigator.html` - Upsell page for Claim Navigator
- ✅ `/about.html` - About/SEO page

### Styling
- ✅ `/css/styles.css` - Custom CSS with TailwindCSS integration
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Navy-to-emerald gradient theme
- ✅ Smooth animations and hover effects

### Configuration
- ✅ `/netlify.toml` - Netlify deployment configuration
- ✅ SEO meta tags on all pages
- ✅ Open Graph tags for social sharing
- ✅ Google Analytics 4 placeholder
- ✅ Meta Pixel placeholder

### Features Implemented
- ✅ Sticky value banner ($2,156 total)
- ✅ Product grid with 6 categories (20 products total)
- ✅ Pricing totals correctly sum to $2,156
- ✅ FAQ accordion with JavaScript
- ✅ Testimonial strip
- ✅ Sticky footer CTA
- ✅ All Stripe buy button placeholders

## 🔧 Before Going Live

### Required Updates

1. **Google Analytics**
   - Replace `G-XXXXXXXXXX` with your actual GA4 tracking ID
   - Location: All HTML files, line ~39

2. **Meta Pixel**
   - Replace `YOUR_PIXEL_ID` with your actual Facebook Pixel ID
   - Location: All HTML files, line ~48

3. **Stripe Buy Buttons**
   - Replace all `https://buy.stripe.com/price_*` links with actual Stripe payment links
   - Location: `index.html` - all product cards

4. **Assets**
   - Create and add `/assets/favicon.ico` (32x32 or 48x48 ICO file)
   - Create and add `/assets/og-image.jpg` (1200x630px JPG)
   - See `/assets/ASSETS_README.txt` for details

5. **Email Integration** (Optional)
   - Uncomment and configure email capture modal in `index.html`
   - Integrate with Mailchimp or Beehiiv API

6. **Affiliate Tracking** (Optional)
   - Add Refersion or Tapfiliate script to `<head>` section

### Domain Configuration

- Update canonical URLs from `https://claimtools.ai/` to your actual domain
- Update all internal links if domain differs
- Update email addresses if needed (`support@claimtools.ai`)

### Testing Checklist

- [ ] Test all Stripe buy button links
- [ ] Verify Claim Navigator link points to correct external URL
- [ ] Test responsive design on mobile/tablet/desktop
- [ ] Verify FAQ accordion functionality
- [ ] Check all internal navigation links
- [ ] Test sticky banner and footer CTA visibility
- [ ] Verify Google Analytics tracking
- [ ] Test Meta Pixel events
- [ ] Validate HTML/CSS (no console errors)
- [ ] Test page load speed
- [ ] Verify SEO meta tags with social media preview tools

### Netlify Deployment

1. Push code to GitHub/GitLab
2. Connect repository to Netlify
3. Netlify will auto-detect `netlify.toml`
4. Site will deploy automatically
5. Configure custom domain in Netlify settings

### Post-Deployment

- [ ] Submit sitemap to Google Search Console
- [ ] Verify SSL certificate is active
- [ ] Test all forms and payment flows
- [ ] Monitor analytics for first 24-48 hours
- [ ] Set up error tracking (optional: Sentry, etc.)

## 📊 Pricing Verification

Total of all individual products: **$2,156**
- Category 1 (Documentation): $538
- Category 2 (Policy): $273
- Category 3 (Communication): $423
- Category 4 (Tracking): $225
- Category 5 (Expert/Financial): $541
- Category 6 (Education): $156

Claim Navigator price: **$997**
Savings: **$1,159** ✅

## 🎨 Design Notes

- Color scheme: Navy (#0a1a2f) to Emerald (#00c896)
- Font: Inter (Google Fonts)
- All buttons use gradient hover effects
- Product cards have elevation on hover
- Smooth scroll behavior enabled
- Sticky elements: value banner (top) and CTA footer (bottom)

## 📁 File Structure

```
insuranceclaimtoolsai/
├── index.html
├── get-claim-navigator.html
├── about.html
├── netlify.toml
├── css/
│   └── styles.css
└── assets/
    ├── favicon.ico (TO BE CREATED)
    ├── og-image.jpg (TO BE CREATED)
    ├── favicon.svg (placeholder)
    └── icons/ (optional)
```

## 🚀 Ready to Deploy!

Once you've updated the placeholders (GA, Pixel, Stripe links, assets), the site is production-ready!

