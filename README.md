# Check In Together - Website

Official website for Check In Together emergency safety check-in service. This site is designed to meet Twilio toll-free verification requirements and provide clear information about SMS consent, privacy, and service policies.

## 📁 Files

- `index.html` - Main website (single-page with all required sections)
- `styles.css` - Professional styling with responsive design
- `script.js` - Smooth scrolling and animations
- `README.md` - This file

## 🚀 Quick Start

### View Locally

Simply open `index.html` in any web browser:

```bash
open index.html
```

Or use a local server for testing:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000`

## 🌐 Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. Push this repo to GitHub
2. Go to Settings > Pages
3. Select branch: `main`, folder: `/` (root)
4. Your site will be live at: `https://[username].github.io/[repo-name]`

### Option 2: Netlify (Drag & Drop)

1. Go to [netlify.com](https://netlify.com)
2. Drag the entire website folder onto Netlify
3. Get instant HTTPS URL
4. Optional: Add custom domain

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Import this Git repository
3. Deploy automatically
4. Get instant URL with HTTPS

### Option 4: Any Static Host

Upload these files to any web hosting:
- AWS S3 + CloudFront
- Google Cloud Storage
- Azure Static Web Apps
- Traditional web hosting

## 📋 Content Sections

### ✅ Homepage (#home)
- Service description
- Who sends messages (Check In Together LLC)
- Non-marketing statement
- Links to all policies

### ✅ How It Works (#how-it-works)
- Step-by-step user flow
- Emergency contact opt-in process
- Sample SMS messages
- Frequency information

### ✅ Consent & Opt-In (#consent)
**Critical for Twilio verification - Paste this URL in their form**
- Exact opt-in wording
- What "YES" means
- Consent record storage details
- Screenshot placeholders

### ✅ SMS Policy (#sms-policy)
- STOP instructions
- HELP information
- Support contact
- Message & data rates disclosure

### ✅ Privacy Policy (#privacy)
- Data collection details
- Information sharing (Twilio as processor)
- Retention periods
- User rights (access, deletion, etc.)

### ✅ Terms of Service (#terms)
- Emergency disclaimer (NOT 911 replacement)
- User responsibilities
- Abuse policy
- Limitation of liability

### ✅ Contact (#contact)
- Support email: support@checkintogetherapp.com
- Operator: Check In Together LLC
- Location: United States
- FAQ section

## 📝 For Twilio Toll-Free Verification

When submitting your Twilio toll-free verification form:

1. **Website URL**: `https://your-domain.com`
2. **Consent Page URL**: `https://your-domain.com#consent`
3. **Privacy Policy URL**: `https://your-domain.com#privacy`
4. **Terms of Service URL**: `https://your-domain.com#terms`

### Key Points to Highlight in Twilio Form:

- ✅ **Explicit opt-in required**: Emergency contacts must reply "YES" to consent
- ✅ **Non-marketing**: No promotional messages ever sent
- ✅ **Rare frequency**: Emergency alerts only (not regular notifications)
- ✅ **STOP honored**: Automatic opt-out processing
- ✅ **Clear purpose**: Safety monitoring for people living alone

### Sample Messages for Twilio Form:

**Opt-In Request:**
```
[John Smith] listed you as an emergency contact for Check In Together. Reply YES to receive emergency alerts if they miss safety check-ins. Reply STOP to opt out. Msg&data rates may apply. Help: support@checkintogetherapp.com
```

**Emergency Alert:**
```
🚨 Emergency alert from Check In Together: [John Smith] has missed 2 consecutive safety check-ins. Last check-in: Jan 15, 2026 9:00 AM. Please contact them immediately to ensure they are safe. Reply STOP to opt out.
```

## 🎨 Customization

### Update Contact Information

Edit `index.html` and search for:
- `support@checkintogetherapp.com` - Update to your support email
- `Check In Together LLC` - the operator's legal name (update if the entity changes)

### Update Colors

Edit `styles.css` at the top (`:root` section):
```css
--primary-color: #2563eb;  /* Main blue color */
--primary-dark: #1e40af;   /* Darker blue for hovers */
```

### Add Screenshots

Replace the screenshot placeholders in the Consent section (#consent) with actual screenshots:
1. Take screenshots of your opt-in flow
2. Save as `opt-in-screenshot.png` and `confirmation-screenshot.png`
3. Add images to the website folder
4. Update HTML with: `<img src="opt-in-screenshot.png" alt="Opt-in flow">`

## ✅ Pre-Launch Checklist

Before submitting to Twilio:

- [ ] Site is live (not "coming soon")
- [ ] All links work (test navigation)
- [ ] Support email is working and monitored
- [ ] Consent page clearly shows opt-in process
- [ ] STOP/HELP language is visible
- [ ] Privacy policy is complete
- [ ] Terms of Service includes emergency disclaimer
- [ ] Contact information is accurate
- [ ] Mobile-responsive (test on phone)
- [ ] HTTPS enabled (required for production)

## 🔒 HTTPS Requirement

For production, your site must use HTTPS. All deployment options above (GitHub Pages, Netlify, Vercel) provide free SSL certificates automatically.

## 📱 Mobile Responsive

This site is fully responsive and works on:
- Desktops
- Tablets
- Mobile phones

Test on multiple devices before going live.

## 🆘 Support

For questions about this website or Twilio verification:

Email: support@checkintogetherapp.com

## 📄 License

This website is part of the Check In Together project.

---

**Ready to deploy!** Upload to your hosting provider and submit the URL to Twilio for toll-free verification.
