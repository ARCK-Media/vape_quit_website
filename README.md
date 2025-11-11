# Vape Quit Website

A dark-themed, professional static website for the Vape Quit mobile app.

## 🎨 Features

- **Modern Dark Theme** - Professional blue-gray color scheme with accent colors
- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **Clinical Focus** - Health-focused messaging with medical accuracy
- **Premium Features Showcase** - Highlights advanced analytics and tracking
- **Waitlist Form** - Email collection for launch notifications
- **Legal Pages** - Complete Privacy Policy and Terms of Service

## 📁 File Structure

```
vapequit-website/
├── index.html          # Main landing page
├── privacy.html        # Privacy Policy page
├── terms.html          # Terms of Service page
├── styles.css          # All styling (dark theme)
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

### Option 1: Local Testing
1. Download all files to a folder
2. Open `index.html` in your web browser
3. That's it! No server needed for local testing

### Option 2: Deploy to Hosting
Upload all files to your web hosting provider:
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect to Git repository
- **GitHub Pages**: Push to GitHub and enable Pages
- **Traditional Hosting**: Upload via FTP/cPanel

## ⚙️ Configuration

### Email Form Setup
The waitlist form currently simulates submissions. To connect it to a real backend:

1. Open `script.js`
2. Find the `waitlist-form` event listener
3. Replace the simulated API call with your actual endpoint:

```javascript
const response = await fetch('YOUR_API_ENDPOINT', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify({ email: email })
});
```

### Recommended Email Services
- **Mailchimp**: Great for waitlists
- **ConvertKit**: Built for creators
- **Supabase**: If you're already using it for your app
- **Custom Backend**: Connect to your own API

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --bg-primary: #0a0e1a;        /* Main background */
    --bg-secondary: #151b2e;      /* Card backgrounds */
    --accent-primary: #6366f1;     /* Buttons, links */
    --text-primary: #ffffff;       /* Main text */
    --text-secondary: #94a3b8;     /* Secondary text */
}
```

### Content
- Edit text directly in `index.html`
- Update company info in `privacy.html` and `terms.html`
- Modify pricing in the pricing section

### Images
To add app screenshots:
1. Create an `images/` folder
2. Add your images
3. Update the relevant HTML sections with `<img>` tags

## 📱 Testing Checklist

- [ ] All internal links work (navigation, footer)
- [ ] Email form validates and shows success/error messages
- [ ] Smooth scrolling works on all anchor links
- [ ] Responsive design looks good on mobile
- [ ] Legal pages display correctly
- [ ] Colors match your brand

## 🔧 Browser Compatibility

Tested and working on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Legal Pages

### Privacy Policy (`privacy.html`)
- Covers data collection, usage, and security
- GDPR and CCPA compliant
- Includes sections on health data and third-party services

### Terms of Service (`terms.html`)
- Subscription terms and refund policy
- Medical disclaimers
- User responsibilities and limitations of liability

**Important**: Review and customize these legal documents with your lawyer before launch. The templates are a starting point, not legal advice.

## 🌐 Deployment Tips

### Before Launch
1. Replace placeholder emails with real ones
2. Add your analytics code (Google Analytics, etc.)
3. Set up email form backend
4. Review and update legal pages
5. Test on multiple devices
6. Check page load speed

### SEO Optimization
1. Update meta descriptions in HTML `<head>`
2. Add relevant keywords
3. Create a `sitemap.xml`
4. Add `robots.txt`
5. Submit to Google Search Console

### Performance
- Images are not yet optimized (add WebP format when you add images)
- Consider using a CDN for fonts
- Minify CSS and JS for production

## 🎯 Next Steps

1. **Connect Email Backend**
   - Set up Mailchimp or similar service
   - Configure API endpoint in `script.js`

2. **Add Analytics**
   - Google Analytics
   - Facebook Pixel (for ads)
   - Hotjar (for user behavior)

3. **Add App Store Links**
   - Replace waitlist with download buttons when app is live
   - Add App Store and Play Store badges

4. **Custom Domain**
   - Purchase domain (vapequit.app or similar)
   - Point DNS to your hosting

5. **SSL Certificate**
   - Most hosting providers offer free SSL
   - Essential for collecting emails

## 📧 Support

For questions about this website template:
- Create an issue in your repository
- Contact: support@vapequit.app

## 📄 License

This website template is provided as-is for FUTNext LTD's use with the Vape Quit app.

---

**Built with ❤️ for FUTNext LTD**

*Last Updated: November 11, 2025*