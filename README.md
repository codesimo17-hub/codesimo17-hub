# Video Publisher 2311 - GitHub Pages Website

Complete professional website for TikTok API approval and platform credibility.

## 📂 Structure

```
github-pages/
├── index.html          # Landing page with features and platform info
├── privacy.html        # GDPR/CCPA compliant Privacy Policy
├── terms.html          # Comprehensive Terms of Service
├── contact.html        # Contact form and support information
├── css/
│   └── style.css      # Professional styling
├── js/                 # (Future: interactive features)
└── images/            # (Future: logos and screenshots)
```

## 🚀 Deployment Instructions

### Option 1: GitHub Pages (Recommended)

1. **Create a new GitHub repository**
   ```bash
   # Name it: video-publisher-2311 or your-username.github.io
   ```

2. **Upload files**
   ```bash
   cd github-pages
   git init
   git add .
   git commit -m "Initial commit: Video Publisher 2311 website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Source: Deploy from branch `main` / `root`
   - Save

4. **Your site will be live at:**
   ```
   https://YOUR-USERNAME.github.io/REPO-NAME/
   ```

### Option 2: Custom Domain (Optional)

1. Add `CNAME` file with your domain:
   ```
   videopublisher2311.com
   ```

2. Configure DNS records at your domain registrar:
   ```
   Type: CNAME
   Name: www
   Value: YOUR-USERNAME.github.io
   ```

## 📝 Required Updates

Before deploying, update these placeholders:

### 1. Contact Email Addresses
Replace placeholder emails in:
- `privacy.html` (lines with @videopublisher2311.com)
- `terms.html` (lines with @videopublisher2311.com)
- `contact.html` (lines with @videopublisher2311.com)

Use real email addresses or create forwarding rules.

### 2. Contact Form (contact.html)
Replace Formspree URL:
```html
<form action="https://formspree.io/f/YOUR-FORM-ID">
```

Options:
- **Formspree**: Sign up at https://formspree.io (free tier available)
- **Netlify Forms**: If deploying to Netlify
- **Google Forms**: Embed Google Form
- **Custom backend**: Your own email handling service

### 3. Legal Jurisdiction (terms.html)
Update line in Section 13.1:
```
[Your Jurisdiction] → Your actual jurisdiction (e.g., "Delaware, United States")
```

### 4. Arbitration Organization (terms.html)
Update line in Section 13.2:
```
[Arbitration Organization] → e.g., "American Arbitration Association (AAA)"
```

## 🎯 For TikTok API Application

When applying for TikTok Content Posting API, use:

**Website URL:**
```
https://YOUR-USERNAME.github.io/REPO-NAME/
```

**Privacy Policy URL:**
```
https://YOUR-USERNAME.github.io/REPO-NAME/privacy.html
```

**Terms of Service URL:**
```
https://YOUR-USERNAME.github.io/REPO-NAME/terms.html
```

**App Description:**
> Video Publisher 2311 is an automated content scheduling and publishing platform that helps creators manage and publish video content across multiple social media platforms including TikTok, YouTube, and Instagram. Our tool uses official platform APIs to enable scheduled posting, content queue management, and performance analytics.

**Use Case:**
> Content Posting API - Automated video scheduling and publishing

## ✅ Compliance Checklist

This website includes:

- ✅ **Privacy Policy** - GDPR, CCPA, and TikTok compliant
- ✅ **Terms of Service** - Comprehensive legal terms
- ✅ **Data Protection** - Clear data handling policies
- ✅ **User Rights** - Access, deletion, portability
- ✅ **Third-Party Integration** - OAuth and API usage explained
- ✅ **Contact Information** - Multiple contact methods
- ✅ **Professional Design** - Clean, responsive layout
- ✅ **Cookie Policy** - Explained in Privacy Policy
- ✅ **Children's Privacy** - COPPA compliance (13+ age requirement)
- ✅ **International Compliance** - GDPR for EU users

## 🎨 Customization

### Brand Colors
Edit `css/style.css`:
```css
:root {
    --primary-color: #2563eb;    /* Change to your brand color */
    --primary-dark: #1e40af;     /* Darker shade */
    --secondary-color: #10b981;  /* Accent color */
}
```

### Logo
Add your logo to `images/logo.png` and update:
```html
<div class="logo">
    <img src="images/logo.png" alt="Video Publisher 2311">
</div>
```

## 📱 Features

- **Responsive Design** - Works on all devices
- **Professional Layout** - Modern, clean interface
- **SEO Optimized** - Meta tags and structured content
- **Fast Loading** - Minimal CSS, no heavy frameworks
- **Accessible** - Semantic HTML, ARIA support

## 🔒 Security Notes

- Never commit real API keys or credentials
- Use environment variables for sensitive data
- Enable HTTPS (automatic with GitHub Pages)
- Keep dependencies updated

## 📞 Support

For questions about this website template:
- File an issue in the repository
- Contact: support@videopublisher2311.com (update with real email)

## 📄 License

This website template is provided as part of Video Publisher 2311.
Update legal documents to match your actual business practices and jurisdiction.

---

**Ready to deploy!** Follow the deployment instructions above.
