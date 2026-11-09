<div align="center">

# 🌌 Nafis Fuad Barshan · 3D Portfolio

### Scroll to fly through my work

*Recent Computer Science & Engineering graduate from the University of Asia Pacific, Laboratorian batch 18 & DCIAN batch 20 alumni, passionate about making valuable moves.*

![Three.js](https://img.shields.io/badge/Three.js-r128-0b1220?style=for-the-badge&logo=threedotjs&logoColor=00e5ff)
![WebGL](https://img.shields.io/badge/WebGL-0b1220?style=for-the-badge&logo=webgl&logoColor=ff6b35)
![Tailwind](https://img.shields.io/badge/Tailwind-0b1220?style=for-the-badge&logo=tailwindcss&logoColor=00e5ff)
![Gold & Silver](https://img.shields.io/badge/Gold_%26_Silver_sections-e3b95a?style=for-the-badge&labelColor=0b1220)
![Dark & Light](https://img.shields.io/badge/Dark_%26_Light_theme-00e5ff?style=for-the-badge&labelColor=0b1220)

</div>

---

## 🎬 The experience

Scrolling moves a camera along a curved path through a neon 3D world. Each section is a **station** with its own object:

| Station | In the 3D scene | On the page |
|---|---|---|
| 🏠 **Hero** | Steel core with glowing rings and floating shapes | "Welcome to my portfolio", "Fresh Graduate", Generate CV |
| 🧑 **About** | Your **transparent cutout portrait** floating between rings | Education, CGPA 3.45, languages with IELTS & German timelines |
| 💼 **Experience** | Three logo tiles (Eutropia IT, eChithi, Scout) joined by a timeline thread | Eutropia IT, eChithi and Scout Member, each with an **auto-sliding gallery** (appointment letters, experience certificate, Ramna Park photo, Scout certificate) that opens full size on click |
| 🧠 **Skills** | Seven orbiting rings, one per skill group | Seven groups (design, programming, web, AI/data, IoT/networking, productivity & research, communication & teamwork). Hover a group and its orbit lights up |
| 🚀 **Projects** | Eight floating cards you can click | EduHelp, MIMO RoF, Topnoz, Hotel Management, MewWoof BD, **CM14 Robot** (driving-test video, photos, collapsible components & power check), RM22 (8 photos, supervisors, authors), Career Gap thesis (opens on the dashboard, then team photos, Pre-Defence video, bound thesis book, defence day) |
| 🥇 **Honors (gold)** | Six golden gems | Golden‑ratio list + preview. Open certificates, medal, photos and **videos** (World Cup Champion now includes the winner announcement) |
| 💠 **Leadership (platinum)** | Two platinum cards orbiting a knot | Founding Member at Mes Que Un Blancos and Former Player at PES Fighter BD, each with an auto-sliding gallery (player cards, logos, Facebook group page, Player of the Match card) |
| 🥈 **Participations (silver)** | A ring of 12 silver coins | Certificate gallery with filters, plus workshops & conferences (the Scout certificate now lives on the Scout Member experience card) |
| 📬 **Contact** | A glowing portal | Links and **Generate updated CV** |
| 🌗 **Dark / light mode** | Sun/moon button in the navigation bar, remembered between visits. The page uses a high-contrast light theme (white panels, firm borders, darker text) and the **3D world re-colours itself too**: background, fog, grid, stars, lights and wireframes switch to deeper tones that stay visible on light |
| ✨ **Gold & silver glow** | Honors (gold) glow the most and Participations (silver) a subtler amount, in both themes. Headings, panels, certificate frames, tabs and bullets glow, and in the scene the gems and coins have stronger emissive light plus a soft gold or silver point light |

## 🚀 Run it

WebGL textures can't load from `file://`, so serve the folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

> 🌐 Three.js loads from the cdnjs CDN, so you need an internet connection for the 3D scene.
> If it can't load, the page **falls back to a clean flat layout** automatically.

## 🗂️ What's inside

```
Nafis-3d-Portfolio/
├── index.html                 # page, styles (dark + light), theme toggle and 3D scene in one file (assets inlined as data URIs)
├── cv.html                    # print-ready CV  →  /cv.html?print=1
├── Nafis_Fuad_Barshan_CV.docx # Word CV
├── Bangladesh_Scouts_Logo.svg # logo on the Scout Member card
├── certs/                     # certificate images
├── media/                     # honor, thesis, CM14, RM22, leadership and Scout photos and videos
└── docs/                      # appointment letters & experience certificate (redacted)
```

## ✏️ Make it yours

Open `index.html` and search for:

- `const PROJECTS` for project cards and details (`parts`/`note` = CM14 components table, `people` = supervisors and authors)
- `SETS.exp` / `SETS.lead` for the Experience and Leadership galleries
- `const HONORS` / `const PARTS` for honors and participations (images go in `certs/` or `media/`)
- `STATIONS` for where the camera pauses for each section (now includes `leadership`)
- `v2 — theme toggle, VISIBLE LIGHT THEME` (CSS) for light colours and the glow strength: `#honors{--gl:42%}` and `#participations{--gl:24%}` (light mode has its own values)
- `setTheme3D` and `LIGHT_MAP` (JS) for how the 3D scene is coloured in light mode

## ♿ Good citizen

Keyboard‑navigable lists and dialogs, visible focus rings, `prefers-reduced-motion` respected, and a lighter scene on phones.

## 📬 Contact

📧 nafisfuadbarshan@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/nafis-fuad-barshan-46b5301a5/) · 🐙 [GitHub](https://github.com/NafisFuadBarshan/) · 📸 [Instagram](https://www.instagram.com/n.f.barshan/)

<div align="center">

*Made in Dhaka, Bangladesh 🇧🇩 · see also the 2D portfolio*

</div>
