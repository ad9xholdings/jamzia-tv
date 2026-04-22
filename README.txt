# JamZia — The Everything App
## v1.0 — Network Solutions Deployment Package

## Upload Instructions

### Step 1: Extract to /htdocs
Upload ALL files in this package to your Network Solutions hosting root:
```
/htdocs/
├── index.html              ← Main landing page (SORME™ + Layer 1/2)
├── .htaccess              ← Apache routing rules
├── css/
│   └── jamzia.css         ← Stylesheet
├── js/
│   └── jamzia.js          ← JavaScript
├── jamvideo/
│   └── index.html         ← JamVideo™ Universe
├── jamaudio/
│   └── index.html         ← JamAudio™ Universe
├── jamplay/
│   └── index.html         ← JamPlay™ Universe
├── jamlearn/
│   └── index.html         ← JamLearn™ Universe
├── jamsocial/
│   └── index.html         ← JamSocial™ Universe
├── jamads/
│   └── index.html         ← JamAds™ Universe
├── jampay/
│   └── index.html         ← JamPay™ Universe
├── jamshop/
│   └── index.html         ← JamShop™ Universe
└── jamcloud/
    └── index.html         ← JamCloud™ Universe
```

### Step 2: File Permissions
Set permissions via FTP or File Manager:
- HTML files: 644
- CSS/JS files: 644
- Directories: 755
- .htaccess: 644

### Step 3: Test All Links
After upload, verify these URLs resolve:
- https://jamzia.tv/ ← Main page (SORME™ first)
- https://jamzia.tv/jamvideo/ ← Layer 1 Primary
- https://jamzia.tv/jamaudio/ ← Layer 1 Primary
- https://jamzia.tv/jamplay/ ← Layer 2
- https://jamzia.tv/jamlearn/ ← Layer 2
- https://jamzia.tv/jamsocial/ ← Layer 2
- https://jamzia.tv/jamads/ ← Layer 2
- https://jamzia.tv/jampay/ ← Layer 2
- https://jamzia.tv/jamshop/ ← Layer 2
- https://jamzia.tv/jamcloud/ ← Layer 2

### Step 4: DNS (if needed)
If using a subdomain or new domain:
- Point A record to Network Solutions IP
- Allow 24-48 hours for propagation

## What's in v1.0

| Feature | Status |
|---------|--------|
| SORME™ Search Engine | ✅ Front-and-center |
| Offer/Request/Match/Engine | ✅ Mantra with icons |
| Stats Banner | ✅ 11+ Platforms / 100M+ Songs / 10K+ Movies / Global |
| Pricing | ✅ $299/mo • $2,990/year • White-label |
| Layer 1 Primary | ✅ JamVideo™ + JamAudio™ (featured cards) |
| Layer 2 Ecosystem | ✅ 7 additional MFCs (compact) |
| Java State Management | ✅ HERO→MFC→UNIVERSE→PLATFORM |
| Grayscale Logos | ✅ CSS-based, hover-to-color |
| Header CTAs | ✅ Login + Get Access Now |
| Black Diamond Design | ✅ #000000, #081F5C, #7096D1, #F7F2EB |
| Mobile Responsive | ✅ Menu toggle + stacked layouts |

## Links Reference

### Internal Navigation
- Platforms → `/` (scroll to grid)
- Pricing → `#pricing-section`
- About → Modal popup
- Login → `stateManager.login()`
- Get Access Now → `stateManager.toggleAccess()`

### Universe Entry Points
- JamVideo™ → `/jamvideo/`
- JamAudio™ → `/jamaudio/`
- JamPlay™ → `/jamplay/`
- JamLearn™ → `/jamlearn/`
- JamSocial™ → `/jamsocial/`
- JamAds™ → `/jamads/`
- JamPay™ → `/jampay/`
- JamShop™ → `/jamshop/`
- JamCloud™ → `/jamcloud/`

### External (Footer)
- Ad9x Holdings, LLC (payment processor)
- United Series of America Master, LLC (IP holder)

## Support

If any links 404 after upload:
1. Check .htaccess is present (enables pretty URLs)
2. Verify directory names are lowercase
3. Ensure trailing slashes are consistent
4. Check File Manager shows all files uploaded

## Version
JamZia — The Everything App | v1.0 — April 16, 2026
Total Size: ~52 KB (compressed: ~20 KB)
