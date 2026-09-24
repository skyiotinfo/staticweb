# SkyIoT-Tech - Enterprise IoT Solutions Website

## 🚀 Overview
Professional corporate website for SkyIoT-Tech, showcasing enterprise-grade IoT platforms, edge solutions, and consulting services.

## 📋 Website Structure

### Main Pages
- **Home** (`index.html`) - Hero, features, testimonials, industry solutions
- **Services** (`services.html`) - Detailed service offerings and process
- **Products** (`products.html`) - IoT products and solutions catalog
- **Case Studies** (`case-studies.html`) - Customer success stories
- **About Us** (`about.html`) - Company mission, values, team, timeline
- **Contact** (`contact.html`) - Contact form, info, FAQ
- **Privacy** (`privacy.html`) - Privacy policy

### Key Features
✅ Modern, professional design with dark theme  
✅ Fully responsive (mobile, tablet, desktop)  
✅ Customer testimonials and case studies  
✅ Interactive FAQ section  
✅ Professional SVG graphics and logos  
✅ Clear call-to-actions throughout  
✅ Industry-specific solutions showcase  
✅ Team and company timeline  
✅ Comprehensive service descriptions  

## 🎨 Design
- **Framework:** Tailwind CSS (CDN)
- **Fonts:** DM Sans, JetBrains Mono (Google Fonts)
- **Color Scheme:** Dark slate with sky blue accents
- **Graphics:** SVG for scalability

## 📊 Key Metrics Showcased
- 500+ Deployments
- 99.9% Uptime SLA
- 50M+ Connected Devices
- 24/7 Support

## 🗂️ Directory Structure
```
staticweb/
├── index.html              # Homepage
├── about.html              # About Us
├── services.html           # Services
├── products.html           # Products
├── case-studies.html       # Case Studies (NEW)
├── contact.html            # Contact & FAQ
├── privacy.html            # Privacy Policy
├── public/                 # Images & Assets
│   ├── logo.svg           # Company logo
│   ├── hero-background.svg
│   ├── logo-abc.svg
│   ├── logo-greenenergy.svg
│   ├── logo-smartcity.svg
│   ├── icon-iot.svg
│   └── illustration-network.svg
├── images/                 # Product images (SVG)
└── ENHANCEMENTS.md        # Detailed improvement log
```

## 🌐 Deployment

### Local Testing
Simply open `index.html` in a web browser. All resources are CDN-based or local.

### Nginx Configuration (Ubuntu)
1. Copy files to web root:
   ```bash
   sudo cp -r * /var/www/html/
   ```

2. Configure Nginx:
   ```nginx
   server {
       listen 80;
       server_name yourdomain.com;
       root /var/www/html;
       index index.html;
       
       location / {
           try_files $uri $uri/ =404;
       }
   }
   ```

3. Test and reload:
   ```bash
   sudo nginx -t
   sudo systemctl reload nginx
   ```

### HTTPS Setup (Let's Encrypt)
```bash
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx -d yourdomain.com
```

## 🎯 Target Industries
- Manufacturing
- Energy & Utilities
- Logistics
- Agriculture
- Smart Buildings
- Water Management
- Smart Cities
- Healthcare

## 🔗 External Dependencies
- Tailwind CSS: `https://cdn.tailwindcss.com`
- Google Fonts: DM Sans & JetBrains Mono

## 📱 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Recent Enhancements
See `ENHANCEMENTS.md` for a detailed list of all improvements including:
- Complete homepage redesign
- New case studies page
- Enhanced about us with team section
- Comprehensive FAQ
- Professional visual assets
- Improved navigation
- Better CTAs and user flow

## 📧 Contact Information
- **Email:** info@skyiottech.com
- **Phone:** +91-8338459147
- **Business Hours:** Mon-Fri, 9:00 AM - 6:00 PM IST
- **Support:** 24/7 Emergency Support Available

## 📄 License
© 2025 SkyIoT-Tech. All rights reserved.

---

**Status:** Production Ready ✅  
**Last Updated:** September 2026  
**Version:** 2.0