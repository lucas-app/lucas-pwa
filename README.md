# LUCAS Inspector PWA 🏠

Property verification app for LUCAS inspectors in the Dubai pilot.

## Features

- ✅ Inspector login (ID + PIN)
- ✅ Job queue with pending/scheduled inspections
- ✅ 4-step inspection flow:
  1. **Verify** - GPS-locked checklist
  2. **Photos** - Capture required photos
  3. **Score** - Condition assessment (0-100)
  4. **Submit** - Signature + proof hash
- ✅ Issue reporting with severity levels
- ✅ Real-time sync with Supabase
- ✅ PWA installable on iOS & Android
- ✅ Offline-capable (service worker)

## Tech Stack

- Vanilla JS (no framework)
- Supabase (database + auth)
- PWA (manifest + service worker)
- Geolocation API
- Camera API

## Files

```
├── index.html      # Main app
├── manifest.json   # PWA configuration
├── sw.js          # Service worker
├── icon-192.png   # App icon (192x192)
└── icon-512.png   # App icon (512x512)
```

## Database

Uses Supabase with tables:
- `inspectors` - Inspector profiles
- `properties` - Property details
- `inspections` - Inspection records
- `inspection_photos` - Photo metadata
- `inspection_issues` - Reported issues

## Test Credentials

| Inspector ID | PIN  | Name              |
|--------------|------|-------------------|
| INS-7721     | 1234 | Fazza Al Maktoum  |
| INS-8832     | 5678 | Ahmed Hassan      |
| INS-9943     | 0000 | Sara Khan         |

## Deployment

### Vercel (Recommended)
1. Push to GitHub
2. Connect repo to Vercel
3. Deploy automatically

### GitHub Pages
1. Go to Settings → Pages
2. Enable from main branch
3. Access at `username.github.io/lucas-pwa`

## Local Development

Just open `index.html` in a browser. For full PWA features, serve via:

```bash
npx serve .
```

## Supabase Setup

Run the SQL schema in your Supabase SQL Editor:
- Project: https://supabase.com/dashboard/project/irztntmenxchzicfegid

---

Built for LUCAS Dubai Pilot 🇦🇪
