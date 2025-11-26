# LUCAS Agent PWA

A minimal Progressive Web App for LUCAS agents to complete verification tasks and earn USDT.

## Files

- `index.html` - Main app (React-based, single file)
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline support

## Quick Deploy

### Option 1: Vercel (Recommended - Free)
1. Create account at vercel.com
2. Drag & drop this folder
3. Done! You get a URL like `lucas-pwa.vercel.app`

### Option 2: Netlify (Free)
1. Create account at netlify.com
2. Drag & drop this folder
3. Done! You get a URL like `lucas-pwa.netlify.app`

### Option 3: GitHub Pages (Free)
1. Create a GitHub repo
2. Upload these files
3. Go to Settings → Pages → Enable
4. Access at `username.github.io/repo-name`

## Missing Assets

You'll need to add these icon files for the PWA to be installable:
- `icon-192.png` (192x192px) - App icon
- `icon-512.png` (512x512px) - App icon

Use your LUCAS logo on a dark background (#050505).

## Features

✅ Task list with distance sorting  
✅ Task detail with instructions  
✅ Camera capture with GPS overlay  
✅ Photo review before submit  
✅ Success confirmation  
✅ Wallet balance & transactions  
✅ Profile screen  
✅ PWA installable  
✅ Works on iOS & Android  
✅ Spanish UI  

## For Pilot Testing

1. Deploy to Vercel/Netlify
2. Open on phone browser
3. "Add to Home Screen" to install as app
4. Share link with test agents via WhatsApp

## Next Steps (Post-Pilot)

- [ ] Real backend (Supabase recommended)
- [ ] Phone number auth (SMS OTP)
- [ ] Real task assignment
- [ ] USDT wallet integration
- [ ] Push notifications
- [ ] Admin dashboard

## Tech Stack

- React 18 (via CDN)
- Vanilla CSS (no Tailwind needed)
- Geolocation API
- Camera API (MediaDevices)
- Service Worker

---

Built for LUCAS Pilot in CDMX 🇲🇽
