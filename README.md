# NP-Bricks-Architect

![NP Bricks Buildcon](assets/banner.svg)

<img width="300" height="80" alt="banner" src="https://github.com/user-attachments/assets/8005939d-7d80-43b4-90db-e958662a45c6" />
<svg viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0B0B0D"/>
      <stop offset="100%" stop-color="#141416"/>
    </linearGradient>
    <linearGradient id="gold" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#C9A24B"/>
      <stop offset="100%" stop-color="#E08A2C"/>
    </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#C9A24B" stroke-opacity="0.08" stroke-width="1"/>
    </pattern>
  </defs>

  <rect width="1200" height="320" fill="url(#bg)"/>
  <rect width="1200" height="320" fill="url(#grid)"/>

  <!-- construction linework accent -->
  <g stroke="#C9A24B" stroke-opacity="0.25" stroke-width="2" fill="none">
    <path d="M950 260 L950 90 L1010 60 L1010 260"/>
    <path d="M1010 130 L1070 130"/>
    <path d="M1010 180 L1070 180"/>
    <path d="M1070 260 L1070 40 L1140 20 L1140 260"/>
  </g>

  <!-- roof mark -->
  <path d="M60 120 L120 80 L180 120" stroke="url(#gold)" stroke-width="6" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
  <rect x="100" y="112" width="18" height="18" fill="#C9A24B" opacity="0.9"/>

  <text x="60" y="190" font-family="Sora, Arial, sans-serif" font-weight="800" font-size="56" fill="#F5F3EF">NP <tspan fill="#C9A24B">BRICKS BUILDCON</tspan></text>
  <text x="60" y="222" font-family="Georgia, serif" font-style="italic" font-size="26" fill="#E7CE8C">We Build Your Dream</text>
  <text x="60" y="256" font-family="Arial, sans-serif" font-size="15" letter-spacing="4" fill="#A8A6A1">PLAN   ·   DESIGN   ·   BUILD   ·   INSPIRE</text>

  <line x1="60" y1="272" x2="1140" y2="272" stroke="#C9A24B" stroke-opacity="0.3" stroke-width="1"/>
  <text x="60" y="298" font-family="Arial, sans-serif" font-size="13" letter-spacing="1" fill="#A8A6A1">SINGLE-PAGE WEBSITE  ·  HTML / CSS / JS  ·  RESPONSIVE</text>
</svg>


![HTML5](https://img.shields.io/badge/HTML5-0B0B0D?style=for-the-badge&logo=html5&logoColor=C9A24B)
![CSS3](https://img.shields.io/badge/CSS3-0B0B0D?style=for-the-badge&logo=css3&logoColor=C9A24B)
![JavaScript](https://img.shields.io/badge/Vanilla%20JS-0B0B0D?style=for-the-badge&logo=javascript&logoColor=C9A24B)
![Responsive](https://img.shields.io/badge/Responsive-320px→4K-C9A24B?style=for-the-badge)
![No Build Step](https://img.shields.io/badge/Build%20Step-None-4CAF7D?style=for-the-badge)

---

## 📁 Files

| File | Purpose |
|---|---|
| `npbricksbuildcon.html` | The entire website — HTML + CSS + JS in one file |
| `founder.jpg` | Founder's photo — **you add this** |
| `assets/` | README visuals only, not required by the site itself |

---

## 🚀 Run It

```bash
# Option A — just open it
double-click npbricksbuildcon.html

# Option B — any static host
drag the folder into Netlify / Vercel / GitHub Pages
```

No npm install, no build command, no server needed.

---

## 🗺️ Page Structure

![Site Map](assets/sitemap.svg)


<img width="290" height="150" alt="sitemap" src="https://github.com/user-attachments/assets/4bf7d37c-1ce7-46a2-a2de-e15531601175" />

<svg viewBox="0 0 1200 620" xmlns="http://www.w3.org/2000/svg">
  <rect width="1200" height="620" fill="#0B0B0D"/>
  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto">
      <path d="M0,0 L8,3 L0,6 Z" fill="#C9A24B"/>
    </marker>
  </defs>

  <text x="30" y="40" font-family="Sora, Arial, sans-serif" font-weight="700" font-size="20" fill="#F5F3EF">Page Structure — top to bottom scroll</text>

  <!-- vertical spine -->
  <line x1="70" y1="70" x2="70" y2="580" stroke="#C9A24B" stroke-opacity="0.35" stroke-width="2" stroke-dasharray="2 8"/>

  <!-- node template -->
  <g font-family="Arial, sans-serif">
    <!-- 1 Nav -->
    <circle cx="70" cy="80" r="8" fill="#C9A24B"/>
    <rect x="100" y="60" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="87" font-size="15" fill="#F5F3EF" font-weight="700">Sticky Navigation</text>
    <text x="330" y="87" font-size="13" fill="#A8A6A1">Logo · Home / About / Services / Portfolio / Quote / Contact · WhatsApp + Call icons</text>

    <!-- 2 Hero -->
    <circle cx="70" cy="140" r="8" fill="#C9A24B"/>
    <rect x="100" y="120" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="147" font-size="15" fill="#F5F3EF" font-weight="700">Hero</text>
    <text x="330" y="147" font-size="13" fill="#A8A6A1">Headline · CTAs (Free Consultation / View Work) · Trust strip</text>

    <!-- 3 About -->
    <circle cx="70" cy="200" r="8" fill="#C9A24B"/>
    <rect x="100" y="180" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="207" font-size="15" fill="#F5F3EF" font-weight="700">About the Founder</text>
    <text x="330" y="207" font-size="13" fill="#A8A6A1">Photo · Bio · Credential stats (years, plans delivered)</text>

    <!-- 4 Services -->
    <circle cx="70" cy="260" r="8" fill="#C9A24B"/>
    <rect x="100" y="240" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="267" font-size="15" fill="#F5F3EF" font-weight="700">Core Services</text>
    <text x="330" y="267" font-size="13" fill="#A8A6A1">Architectural Planning · Interior · Exterior · Construction — 4-card grid</text>

    <!-- 5 Timeline -->
    <circle cx="70" cy="320" r="8" fill="#C9A24B"/>
    <rect x="100" y="300" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="327" font-size="15" fill="#F5F3EF" font-weight="700">Process Timeline</text>
    <text x="330" y="327" font-size="13" fill="#A8A6A1">Consult → Design → Approve → Build</text>

    <!-- 6 Portfolio -->
    <circle cx="70" cy="380" r="8" fill="#C9A24B"/>
    <rect x="100" y="360" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="387" font-size="15" fill="#F5F3EF" font-weight="700">Portfolio Gallery</text>
    <text x="330" y="387" font-size="13" fill="#A8A6A1">Filterable masonry grid — All / Residential / Commercial / Interiors</text>

    <!-- 7 Quote -->
    <circle cx="70" cy="440" r="8" fill="#E08A2C"/>
    <rect x="100" y="420" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#E08A2C" stroke-opacity="0.4"/>
    <text x="120" y="447" font-size="15" fill="#F5F3EF" font-weight="700">Get a Quote (3-step form)</text>
    <text x="380" y="447" font-size="13" fill="#A8A6A1">Basic Info → Project Details → Requirements → Success</text>

    <!-- 8 Testimonials -->
    <circle cx="70" cy="500" r="8" fill="#C9A24B"/>
    <rect x="100" y="480" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="507" font-size="15" fill="#F5F3EF" font-weight="700">Testimonials</text>
    <text x="330" y="507" font-size="13" fill="#A8A6A1">Scrollable client quote cards with star ratings</text>

    <!-- 9 Contact + Footer -->
    <circle cx="70" cy="560" r="8" fill="#C9A24B"/>
    <rect x="100" y="540" width="1060" height="42" rx="8" fill="#1E1E22" stroke="#C9A24B" stroke-opacity="0.25"/>
    <text x="120" y="567" font-size="15" fill="#F5F3EF" font-weight="700">Contact + Footer</text>
    <text x="330" y="567" font-size="13" fill="#A8A6A1">Map · Phone / Email / Address / WhatsApp cards · Site links</text>
  </g>

  <!-- floating whatsapp note -->
  <circle cx="1150" cy="600" r="18" fill="url(#none)" stroke="#C9A24B" stroke-width="2" fill-opacity="0"/>
</svg>

---

## 🎨 Color System

![Color Palette](assets/palette.svg)

<img width="300" height="65" alt="palette" src="https://github.com/user-attachments/assets/6f8efab5-bb19-4e8b-8936-27f69365cba5" />

<svg viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg">
  <rect width="1200" height="260" fill="#0B0B0D"/>
  <text x="30" y="36" font-family="Sora, Arial, sans-serif" font-weight="700" font-size="20" fill="#F5F3EF">Color System</text>

  <!-- swatch template: x, hex, name, textcolor -->
  <g font-family="Arial, sans-serif">
    <!-- 1 -->
    <rect x="30" y="60" width="150" height="90" rx="10" fill="#0B0B0D" stroke="#C9A24B" stroke-opacity="0.3"/>
    <text x="45" y="130" font-size="13" fill="#A8A6A1">#0B0B0D</text>
    <text x="45" y="148" font-size="12" fill="#A8A6A1">Charcoal 950</text>

    <!-- 2 -->
    <rect x="195" y="60" width="150" height="90" rx="10" fill="#141416"/>
    <text x="210" y="130" font-size="13" fill="#A8A6A1">#141416</text>
    <text x="210" y="148" font-size="12" fill="#A8A6A1">Charcoal 900</text>

    <!-- 3 -->
    <rect x="360" y="60" width="150" height="90" rx="10" fill="#1E1E22"/>
    <text x="375" y="130" font-size="13" fill="#A8A6A1">#1E1E22</text>
    <text x="375" y="148" font-size="12" fill="#A8A6A1">Charcoal 800</text>

    <!-- 4 -->
    <rect x="525" y="60" width="150" height="90" rx="10" fill="#C9A24B"/>
    <text x="540" y="130" font-size="13" fill="#0B0B0D">#C9A24B</text>
    <text x="540" y="148" font-size="12" fill="#0B0B0D">Gold 500</text>

    <!-- 5 -->
    <rect x="690" y="60" width="150" height="90" rx="10" fill="#E08A2C"/>
    <text x="705" y="130" font-size="13" fill="#0B0B0D">#E08A2C</text>
    <text x="705" y="148" font-size="12" fill="#0B0B0D">Amber 500</text>

    <!-- 6 -->
    <rect x="855" y="60" width="150" height="90" rx="10" fill="#E7CE8C"/>
    <text x="870" y="130" font-size="13" fill="#0B0B0D">#E7CE8C</text>
    <text x="870" y="148" font-size="12" fill="#0B0B0D">Gold 300</text>

    <!-- 7 -->
    <rect x="1020" y="60" width="150" height="90" rx="10" fill="#F5F3EF"/>
    <text x="1035" y="130" font-size="13" fill="#0B0B0D">#F5F3EF</text>
    <text x="1035" y="148" font-size="12" fill="#0B0B0D">Off-White 100</text>

    <!-- row 2 -->
    <rect x="30" y="170" width="150" height="70" rx="10" fill="#A8A6A1"/>
    <text x="45" y="205" font-size="13" fill="#0B0B0D">#A8A6A1</text>
    <text x="45" y="222" font-size="12" fill="#0B0B0D">Stone 400</text>

    <rect x="195" y="170" width="150" height="70" rx="10" fill="#4CAF7D"/>
    <text x="210" y="205" font-size="13" fill="#0B0B0D">#4CAF7D</text>
    <text x="210" y="222" font-size="12" fill="#0B0B0D">Emerald 500</text>
  </g>
</svg>


**Type pairing:** `Sora` (headings) · `Cormorant Garamond italic` (script accent) · `Inter` (body) — all loaded from Google Fonts, no local font files needed.

---

## 📝 Quote Form Flow

![Quote Form Flow](assets/formflow.svg)


<img width="300" height="65" alt="formflow" src="https://github.com/user-attachments/assets/8a201f20-d11d-4070-a788-cf1ca2920c08" />
<svg viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg">
  <rect width="1200" height="260" fill="#141416"/>
  <defs>
    <linearGradient id="gold2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#C9A24B"/>
      <stop offset="100%" stop-color="#E08A2C"/>
    </linearGradient>
  </defs>

  <text x="30" y="36" font-family="Sora, Arial, sans-serif" font-weight="700" font-size="20" fill="#F5F3EF">Quote Form Flow</text>

  <!-- progress bar -->
  <rect x="30" y="55" width="1140" height="6" rx="3" fill="#C9A24B" fill-opacity="0.15"/>
  <rect x="30" y="55" width="1140" height="6" rx="3" fill="url(#gold2)"/>

  <!-- step 1 -->
  <circle cx="180" cy="130" r="34" fill="#0B0B0D" stroke="#C9A24B" stroke-width="3"/>
  <text x="180" y="138" font-family="Sora, Arial, sans-serif" font-size="24" font-weight="700" fill="#C9A24B" text-anchor="middle">1</text>
  <text x="180" y="190" font-family="Arial, sans-serif" font-size="14" fill="#F5F3EF" text-anchor="middle" font-weight="700">Basic Info</text>
  <text x="180" y="210" font-family="Arial, sans-serif" font-size="11" fill="#A8A6A1" text-anchor="middle">Name · Phone · Email · City</text>

  <!-- arrow -->
  <path d="M230 130 L370 130" stroke="#C9A24B" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>

  <!-- step 2 -->
  <circle cx="420" cy="130" r="34" fill="#0B0B0D" stroke="#C9A24B" stroke-width="3"/>
  <text x="420" y="138" font-family="Sora, Arial, sans-serif" font-size="24" font-weight="700" fill="#C9A24B" text-anchor="middle">2</text>
  <text x="420" y="190" font-family="Arial, sans-serif" font-size="14" fill="#F5F3EF" text-anchor="middle" font-weight="700">Project Details</text>
  <text x="420" y="210" font-family="Arial, sans-serif" font-size="11" fill="#A8A6A1" text-anchor="middle">Service · Plot Size · Floors · Budget</text>

  <path d="M470 130 L610 130" stroke="#C9A24B" stroke-width="2" fill="none"/>

  <!-- step 3 -->
  <circle cx="660" cy="130" r="34" fill="#0B0B0D" stroke="#C9A24B" stroke-width="3"/>
  <text x="660" y="138" font-family="Sora, Arial, sans-serif" font-size="24" font-weight="700" fill="#C9A24B" text-anchor="middle">3</text>
  <text x="660" y="190" font-family="Arial, sans-serif" font-size="14" fill="#F5F3EF" text-anchor="middle" font-weight="700">Requirements</text>
  <text x="660" y="210" font-family="Arial, sans-serif" font-size="11" fill="#A8A6A1" text-anchor="middle">Description · Contact Time · Upload</text>

  <path d="M710 130 L850 130" stroke="#4CAF7D" stroke-width="2" fill="none"/>

  <!-- success -->
  <circle cx="920" cy="130" r="34" fill="#0B0B0D" stroke="#4CAF7D" stroke-width="3"/>
  <path d="M905 130 L916 142 L938 116" stroke="#4CAF7D" stroke-width="4" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
  <text x="920" y="190" font-family="Arial, sans-serif" font-size="14" fill="#F5F3EF" text-anchor="middle" font-weight="700">Success</text>
  <text x="920" y="210" font-family="Arial, sans-serif" font-size="11" fill="#A8A6A1" text-anchor="middle">"We'll contact you within 24 hrs"</text>

  <!-- whatsapp cta -->
  <rect x="1010" y="105" width="150" height="50" rx="10" fill="url(#gold2)"/>
  <text x="1085" y="135" font-family="Arial, sans-serif" font-size="13" font-weight="700" fill="#0B0B0D" text-anchor="middle">Chat on WhatsApp</text>
  <path d="M965 130 L1005 130" stroke="#C9A24B" stroke-width="2" fill="none"/>
</svg>


---

## ✏️ Common Edits — Find & Replace Cheatsheet

| Want to change... | Search for this in the file |
|---|---|
| 📞 Phone / WhatsApp number | `916306395347` |
| 📧 Email address | `abhivashu831@gmail.com` |
| 📍 Address / map | the `<iframe>` inside `<section id="contact">` |
| 🖼️ Portfolio photos | `src=` inside `.gallery-item` blocks |
| 🎨 Any color | the `:root { }` variables at the top of `<style>` |

---

## ⚠️ Not Wired Up Yet

| Status | Item |
|---|---|
| 🟡 | Quote form validates + shows success screen, but doesn't email/message anyone yet — needs a backend endpoint |
| 🟡 | Portfolio images & testimonials are placeholders — swap before launch |
| 🟡 | Map is a plain query embed, not the full Maps JS API |
| 🔴 | No CMS — content is hardcoded HTML |

---

## 📱 Tested Across

`320px` phones → tablets → `1440px+` desktops, no framework dependencies.
