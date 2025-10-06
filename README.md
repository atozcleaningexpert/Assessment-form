
A TO Z CLEANING EXPERT LTD.
Comprehensive Walkthrough & Internal Assessment Tool (Pro Version)
======================================================================

VERSION: 2025.10 - Professional Build
FILE: index.html
AUTHOR: A TO Z Cleaning Expert Ltd. | Developed with ChatGPT

----------------------------------------------------------------------
📋 OVERVIEW
----------------------------------------------------------------------
This Walkthrough & Internal Assessment Tool is designed for 
commercial cleaning professionals to collect comprehensive 
site information during facility assessments, walkthroughs, 
and proposal preparations.

It combines a professional interface with a dynamic pricing 
estimator, photo uploads, and built-in local data saving.

----------------------------------------------------------------------
🌐 MAIN FEATURES
----------------------------------------------------------------------
✅ Modern, responsive layout with light/dark mode toggle
✅ Progress bar with step indicator
✅ Multi-step form navigation (Next / Previous)
✅ LocalStorage autosave and restore (browser-based)
✅ Dynamic Pricing Estimator (Base + Overhead + Profit)
✅ Signature Pad for digital sign-off
✅ Facility data, operational details, and compliance capture
✅ Photo upload support for each zone
✅ Fully offline — no external dependencies except FontAwesome

----------------------------------------------------------------------
🏗️ FORM STRUCTURE (10 STEPS)
----------------------------------------------------------------------
1️⃣ CLIENT & SITE INFORMATION
   - Company details, contact info, facility type, and hours

2️⃣ FACILITY OVERVIEW
   - Square footage, floors, flooring grid, cleaning frequency

3️⃣ AREA-BY-AREA INSPECTION
   - Offices, restrooms, kitchens, windows, floors (+ photo upload)

4️⃣ SPECIALTY & ADD-ON SERVICES
   - Post-construction, disinfection, carpet care, etc.

5️⃣ FACILITY COMPOSITION
   - Restrooms, kitchens, ceilings, entrances, allowed hours

6️⃣ OCCUPANCY & USAGE
   - Daily occupancy, peak hours, special events

7️⃣ CLEANING SCOPE & OPERATIONS
   - Trash handling, consumables, disinfection, storage, water access

8️⃣ COMPLIANCE & SUSTAINABILITY
   - Insurance, supervision, standards, eco-friendly preferences

9️⃣ DYNAMIC MONTHLY PRICING ESTIMATOR
   - Interactive calculator for pricing with base rate, overhead %, profit %

🔟 SIGNATURE & SUMMARY
   - Digital signature + submission confirmation

----------------------------------------------------------------------
🧮 PRICING ESTIMATOR DETAILS
----------------------------------------------------------------------
Formula:
   Base = (SquareFootage / 1000) × BaseRate × (CleaningsPerWeek × 4)
   Overhead = Base × (Overhead% / 100)
   Profit = (Base + Overhead) × (Profit% / 100)
   Final Price = Base + Overhead + Profit

All values update automatically when you click “Calculate Estimate”.

----------------------------------------------------------------------
💾 DATA STORAGE
----------------------------------------------------------------------
- All form data, selected options, and signature are saved in 
  the browser’s LocalStorage automatically.
- When reopened, the tool restores your last session automatically.
- Click “Reset Form” to clear all saved data.

----------------------------------------------------------------------
🌗 DARK MODE
----------------------------------------------------------------------
Click the moon icon in the header to toggle between Light and Dark mode.
Your preference is remembered automatically.

----------------------------------------------------------------------
✍️ SIGNATURE PAD
----------------------------------------------------------------------
- Click and drag your mouse (or use your finger on touchscreen).
- “Clear Signature” removes your current drawing.
- Signature image is stored locally in your browser.

----------------------------------------------------------------------
📤 DEPLOYMENT / HOSTING
----------------------------------------------------------------------
To host this tool online:
1. Upload all files (index.html + images folder) to your web host
   or GitHub Pages repository.
2. Ensure that `images/a-to-z-logo.png` exists and uses a 
   transparent background for best results.
3. Visit your hosted URL to verify all images and icons load correctly.

For GitHub Pages:
- Place `index.html` in the root of your repo.
- Go to Repository Settings → Pages → “Deploy from Branch”.
- Choose `main` branch → `/root` directory → Save.
- Your walkthrough tool will be live at: https://username.github.io/repository/

----------------------------------------------------------------------
🧱 RECOMMENDED IMPROVEMENTS
----------------------------------------------------------------------
- Add PDF export of the completed walkthrough summary.
- Enable email integration for proposal submission.
- Link estimator output to an automated proposal generator.
- Add multi-user mode for team walkthrough assignments.
- Optionally connect to Google Sheets for data sync.

----------------------------------------------------------------------
📞 SUPPORT
----------------------------------------------------------------------
For customization or internal deployment:
A TO Z Cleaning Expert Ltd.
info@atozcleaningexpert.com
Ottawa / Montreal Division

----------------------------------------------------------------------
© 2025 A TO Z CLEANING EXPERT LTD. All Rights Reserved.
----------------------------------------------------------------------

