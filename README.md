# 🌐 LingoChat Website

Official website for LingoChat - AI-powered translation messaging app.

## 🚀 Quick Deploy to Netlify

### Step 1: Push to GitHub
```bash
git add .
git commit -m "Initial website setup"
git push origin main
```

### Step 2: Deploy on Netlify
1. Go to https://www.netlify.com
2. Click "Add new site" → "Import an existing project"
3. Select GitHub → Choose `lingo-chat.com` repository
4. Build settings:
   - **Base directory**: (leave empty)
   - **Build command**: (leave empty)
   - **Publish directory**: `.` (just a dot)
5. Click "Deploy site"

### Step 3: Add Custom Domain
1. After deployment, go to "Domain settings"
2. Click "Add custom domain"
3. Enter: `www.lingo-chat.com`
4. Netlify will show you DNS records

### Step 4: Configure DNS
Go to your domain provider (where you bought lingo-chat.com):

**Add CNAME Record:**
```
Type: CNAME
Name: www
Value: [your-site-name].netlify.app
TTL: 3600
```

**Add A Record (for root domain):**
```
Type: A
Name: @
Value: 75.2.60.5
TTL: 3600
```

### Step 5: Wait for DNS Propagation
- DNS changes take 15-30 minutes
- Netlify will automatically provision SSL certificate
- HTTPS will be enabled automatically

### Step 6: Verify
After DNS propagates, test:
- https://www.lingo-chat.com
- https://www.lingo-chat.com/privacy.html
- https://www.lingo-chat.com/terms.html

## 📁 Files

- `index.html` - Homepage
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `netlify.toml` - Netlify configuration

## 🔗 URLs

- **Website**: https://www.lingo-chat.com
- **Privacy Policy**: https://www.lingo-chat.com/privacy.html
- **Terms of Service**: https://www.lingo-chat.com/terms.html

## 📧 Contact

- **Email**: info@trairx.com
- **Company**: TrairX Technology O.Ü
- **Location**: Estonia

## 📱 App Repositories

- **Main App**: https://github.com/Trair-Teknoloji-Yatirimilari/lingochat
- **Website**: https://github.com/Trair-Teknoloji-Yatirimilari/lingo-chat.com

---

**Last Updated**: February 21, 2026
