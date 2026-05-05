# Bhabana Kalita — Personal Portfolio Website

A modern, interactive 3D portfolio showcasing my skills, projects, and experience through immersive visuals, smooth animations, and clean, high-performance design.

## Live Preview

[![Live Preview](https://img.shields.io/badge/Live%20Preview-Portfolio-%23c8a96a?style=for-the-badge&logo=githubpages&logoColor=white)](https://bhabana2504.github.io/Portfolio/)

## Features

### 3D Effects (Three.js)
- **Hero section** — Rotating TorusKnot geometry with wireframe overlay, dual orbital rings, and a 300-particle floating field that responds to mouse movement in real time
- **Contact section** — Three intersecting animated torus rings with a 600-particle ambient cloud
- **Skill & achievement cards** — CSS 3D perspective tilt effect on hover (mouse-tracked)

### Design & Animations
- Editorial layout inspired by tajmirul.site — large Bebas Neue display type, outline text, numbered sections
- Warm dark palette (charcoal + gold/amber) with grain noise texture overlay
- Scroll-reveal animations using IntersectionObserver
- Custom ring cursor with hover expansion effect
- Animated gold sweep on project row hover
- Sticky nav with blur backdrop on scroll

### Sections
1. **Hero** — Name, role, CTA buttons, Three.js canvas background
2. **About** — Career objective + personal statement (no projects listed)
3. **Skills** — 12-card tilt grid covering languages, web, ML, cybersecurity, cloud, tools
4. **Experience** — Internships at Codec Technologies and Eduskills Foundation
5. **Projects** — Secure File Transfer System & AI Supply Chain Risk Predictor
6. **Certifications** — AWS, Oracle, Infosys, GUVI, CodeChef
7. **Achievements** — SIH 2025, SIH 2024, hackathon record
8. **Education** — B.Tech, Class XII, Class X
9. **Contact** — Email, GitHub, LinkedIn, phone with Three.js canvas

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Scripting | Vanilla JavaScript (ES6+) |
| 3D Graphics | Three.js r128 (CDN) |
| Fonts | Google Fonts — Bebas Neue, DM Serif Display, DM Sans |

No frameworks. No build tools. No dependencies to install.

---

## Customisation

All personal content is in the HTML body. Key areas to update:

| What | Where in the file |
|------|------------------|
| Name / title | `.hero-name` and `<title>` tag |
| Career objective | `.about-objective` paragraph |
| Skills | `.skills-grid` — edit `.skill-card` blocks |
| Experience | `#experience` — edit `.exp-item` blocks |
| Projects | `#projects` — edit `.project-item` blocks |
| Certifications | `#certifications` — edit `.cert-card` blocks |
| Social links | `#contact` `.contact-links` and `nav` |
| Color palette | `:root` CSS variables at the top of `<style>` |

### Color variables
```css
:root {
  --bg:      #080807;   /* Page background */
  --bg2:     #0f0f0d;   /* Alternate section background */
  --cream:   #ede8df;   /* Primary text */
  --cream2:  #c8c2b6;   /* Secondary text */
  --gold:    #c8a96a;   /* Accent color */
  --muted:   #5a5750;   /* Muted text */
}
```

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Three.js requires WebGL support, which is available in all current desktop and mobile browsers.

---

## Author

**Bhabana Kalita**
## Contact

<img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/gmail.svg" width="16"/> Email: <a href="bhabanakalita25@gmail.com">bhabanakalita25@gmail.com</a>  
<img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" width="16"/> GitHub: <a href="https://github.com/bhabana2504">bhabana2504</a>  
<img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg" width="16"/> LinkedIn: <a href="https://linkedin.com/in/bhabana-kalita-338640295">Profile</a>

---

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
