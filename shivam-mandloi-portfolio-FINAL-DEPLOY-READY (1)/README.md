# Shivam Mandloi — Personal Portfolio

## 1. Portfolio Overview
Interactive developer portfolio for **Shivam Mandloi**, 3rd Year B.Tech Computer Science Engineering student (Section A4) at **INDORE INSTITUTE OF SCIENCE OF TECHNOLOGY** (2024 – 2028), featuring a warm cream, forest-green, and emerald design system, repeatable bidirectional scroll animations, visible 4-card Skills & Toolkit, **Kapda Bazaar**, **BIS360**, **Internal Hackathon-2026** participation, **Cricket & Volleyball** interests, and visible Email/GitHub/LinkedIn contact cards.

## 2. Technology Stack
- **HTML5 & CSS3** (zero-build static architecture — no Vite or `npm` build required)
- **Tailwind CSS v3.4.17** (CDN)
- **GSAP 3.12.5 + ScrollTrigger 3.12.5** (CDN, repeatable bidirectional scroll choreography)
- **Optimized Local WebP Visuals** (`assets/shivam-kapda-bazaar.webp`, `assets/shivam-bis360.webp`)

## 3. Project Structure
```text
├── index.html                           # Complete portfolio application & editable data configs
├── vercel.json                          # Explicit static Vercel deployment configuration (framework: null)
├── README.md                            # Setup, editing & deployment guide
└── assets/
    ├── shivam-kapda-bazaar.webp         # Original Kapda Bazaar B2B textile illustration
    └── shivam-bis360.webp               # Original BIS360 AI standards illustration
```

## 4. Local Installation Instructions
No `npm install` is required. Simply extract `shivam-mandloi-portfolio-FINAL-DEPLOY-READY.zip`.

## 5. Run Locally
Double-click `index.html`, or start a local static server inside the extracted folder:
```bash
python -m http.server 8000
```
Open `http://localhost:8000`.

## 6. Production Build
This is a zero-build static web bundle—`index.html` and `assets/` are already production-ready without running `vite build`.

## 7. Upload to GitHub (Browser Method)
1. Extract `shivam-mandloi-portfolio-FINAL-DEPLOY-READY.zip` on your laptop.
2. Open `https://github.com/shivammandloi7/shivam-mandloi-portfolio`.
3. If any old `package.json` or `vite.config.ts` exists in the repo from an earlier attempt, delete it so Vercel does not treat the repo as Vite.
4. Click **Add file** → **Upload files**, drag in `index.html`, `vercel.json`, `README.md`, and the `assets/` folder, and click **Commit changes**.

## 8. Import into Vercel
1. Visit `https://vercel.com/new` and sign in with GitHub.
2. Click **Import** next to `shivammandloi7/shivam-mandloi-portfolio`.

## 9. Correct Vercel Build Settings
`vercel.json` is preconfigured with `"framework": null`, `"buildCommand": null`, `"installCommand": null`, and `"outputDirectory": "."`.
In **Vercel → Project Settings → Build & Development Settings**, confirm:
- **Framework Preset**: `Other`
- **Build Command**: *(empty / override OFF)*
- **Output Directory**: `.` *(or override OFF)*
- **Install Command**: *(empty / override OFF)*

## 10. Update Skills
Edit the `SHIVAM_SKILLS` array in `index.html`.

## 11. Update Projects
Edit the `SHIVAM_PROJECTS` array in `index.html`.

## 12. Replace Project Images
Replace `assets/shivam-kapda-bazaar.webp` or `assets/shivam-bis360.webp` with your new images.

## 13. Update Personal Information
Edit `SHIVAM_PROFILE` and the corresponding text sections in `index.html`.
