<div align="center">

<!-- Typing header -->
[![Typing](https://readme-typing-svg.demolab.com?font=Fraunces&weight=500&size=32&duration=2800&pause=700&color=F3D437&center=true&vCenter=true&width=940&height=60&lines=Personas+%C3%97+Datos+%C3%97+Sistemas;Yoga+%C3%97+Presencia;Customer+Success+%C2%B7+Data+%C2%B7+AI;Graci%C3%A1n+Baena+%C2%B7+2026)](https://gracianb.github.io/GracianB/)

# **GRACIÁN BAENA**

### Hub · Customer Success Systems × Data Strategy × AI Operations × Yoga

**Dos sistemas, un mismo operador.** Este repo es el lanzador — no duplica portfolios: los abre.

</div>

---

<!-- Badges row -->
<div align="center">

[![Live](https://img.shields.io/badge/%F0%9F%9A%80_HUB-GracianB-f3d437?style=for-the-badge&labelColor=06070a)](https://gracianb.github.io/GracianB/)
[![Corporate](https://img.shields.io/badge/01-PROFESSIONAL--DECK-12%20slides-f4f3ee?style=for-the-badge&labelColor=06070a)](https://gracianb.github.io/professional-deck/)
[![Yoga](https://img.shields.io/badge/02-YOGA--INSTRUCTOR-zen-7dcaa5?style=for-the-badge&labelColor=06070a)](https://gracianb.github.io/yoga-instructor/)
[![GitHub](https://img.shields.io/badge/GitHub-GracianB-f4f3ee?style=for-the-badge&labelColor=06070a&logo=github)](https://github.com/GracianB)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gracianbaena-0A66C2?style=for-the-badge&labelColor=06070a&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gracianbaena)
[![Agenda](https://img.shields.io/badge/Agenda-30_min-f4f3ee?style=for-the-badge&labelColor=06070a)](https://calendar.app.google/n99psBFktwYyoAWi9)

</div>

<br/>

<div align="center">

![16+](https://img.shields.io/badge/16%2B-a%C3%B1os-f3d437?style=for-the-badge&labelColor=06070a)
![200+](https://img.shields.io/badge/200%2B-reglas-f3d437?style=for-the-badge&labelColor=06070a)
![4](https://img.shields.io/badge/4-pa%C3%ADses-f4f3ee?style=for-the-badge&labelColor=06070a)
![2](https://img.shields.io/badge/2-portfolios-7dcaa5?style=for-the-badge&labelColor=06070a)
![ES/EN](https://img.shields.io/badge/i18n-ES_%2F_EN-0A66C2?style=for-the-badge&labelColor=06070a)

</div>

---

## Arquitectura del ecosistema

```
                    ┌─────────────────────┐
                    │    GRACIANB (HUB)    │
                    │  lanzador · ES / EN  │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                                 ▼
  ┌───────────────────────┐         ┌───────────────────────┐
  │   PROFESSIONAL-DECK   │         │   YOGA-INSTRUCTOR     │
  │   Corporate · CS ×    │         │   Yoga · Wellness ·   │
  │   Data × AI · 12 sl.  │         │   Presence · zen      │
  └───────────────────────┘         └───────────────────────┘
         │  CVs ES / EN                    │  CVs ES / EN
         │  Cartas ES / EN                  │
         └──────────────┬───────────────────┘
                        ▼
              ┌─────────────────┐
              │  CVs · Cartas   │
              │  PDF canónicos  │
              └─────────────────┘
```

| Sistema | Live | Repo | Descripción |
|:--------|:-----|:-----|:------------|
| **01 Corporate** | [gracianb.github.io/professional-deck](https://gracianb.github.io/professional-deck/) | [GracianB/professional-deck](https://github.com/GracianB/professional-deck) | Deck interactivo 12 slides · CS × Data × AI · ES/EN |
| **02 Yoga** | [gracianb.github.io/yoga-instructor](https://gracianb.github.io/yoga-instructor/) | [GracianB/yoga-instructor](https://github.com/GracianB/yoga-instructor) | Portfolio zen · instructor certificado · ES/EN |
| **Hub** | [gracianb.github.io/GracianB](https://gracianb.github.io/GracianB/) | [GracianB/GracianB](https://github.com/GracianB/GracianB) | Lanzador dual · modo claro/oscuro · ES/EN |

---

## Qué hace el hub

No es un portfolio — es la **puerta de entrada**. En 5 segundos sabes:

- Quién es Gracián (CS × Data × AI + Yoga)
- Qué sistemas ha construido (Bodytone live + 3 demos)
- Dónde están los CVs y cartas (PDF canónicos)
- Cómo contactar (agenda · email · LinkedIn · GitHub)

### Features del hub

| Feature | Detalle |
|:--------|:--------|
| **Dual-track** | Dos modos: Corporate (amarillo) + Yoga (verde sage) |
| **Stack** | 4 cards: Apps internas · Chatbots LLM · Data & BI · Customer Success |
| **Timeline** | 2 tracks paralelos (sistemas + wellness) · Kung Fu Shaolin incluido |
| **i18n** | ES / EN · persistencia en localStorage · switch en URL `?lang=en` |
| **Tema** | Claro / oscuro · persistencia · `?theme=light` |
| **Method bar** | Escuchar → Decidir → Construir → Activar |
| **Stats animados** | Contador animado al entrar en viewport |
| **CV cards** | 4 PDFs con barra de acento que crece al hover |
| **Cartas** | Cover letter ES + EN |
| **Diseño** | Fraunces (editorial serif) + Inter + JetBrains Mono |
| **FX** | 3 orbes ambientales con drift · noise grain · glassmorphism |
| **Responsive** | Mobile-first · breakpoints 960px / 640px / 400px |
| **Accesible** | Skip link · focus-visible · prefers-reduced-motion · ARIA |

---

## Estructura del repo

```
GracianB/
├── index.html          # Hub · 1 página · dual-track
├── styles.css          # Design system · tokens · glass · FX
├── main.js             # i18n · theme · scroll-spy · counters
├── i18n.js             # ES / EN strings
├── favicon.svg         # Gradiente amarillo → sage · italic GB
├── 404.html            # Redirect
├── .nojekyll           # GitHub Pages sin Jekyll
├── robots.txt          # SEO
├── sitemap.xml         # SEO
└── README.md           # Este archivo
```

---

## Deploy

```bash
# 1. Crear repo
gh repo create GracianB/GracianB --public

# 2. Subir contenido (raíz limpia, sin carpeta extra)
git add . && git commit -m "Hub GracianB — extreme edition" && git push

# 3. Activar GitHub Pages
# Settings → Pages → branch: main → / (root)
```

Live: **https://gracianb.github.io/GracianB/**

> No subas copias con `(1)`, `(2)` en el nombre. Un archivo = un nombre.

---

## Design system unificado

Los tres repos comparten el mismo lenguaje visual:

| Token | Valor | Uso |
|:------|:------|:----|
| `--black` | `#06070a` | Fondo oscuro |
| `--paper` | `#f3f0e7` | Fondo claro (yoga) |
| `--yellow` | `#f3d437` | Acento corporate |
| `--sage` | `#7dcaa5` | Acento yoga |
| `--display` | Fraunces | Headings editorial |
| `--sans` | Inter | Body |
| `--mono` | JetBrains Mono | Labels · kickers |
| `--ease` | `cubic-bezier(.22,1,.36,1)` | Transiciones |
| `--r-lg` | `12px` | Radii panels |

---

## Contacto

<div align="center">

[![Agenda](https://img.shields.io/badge/Agenda-30_min-f4f3ee?style=for-the-badge&labelColor=06070a)](https://calendar.app.google/n99psBFktwYyoAWi9)
[![Email](https://img.shields.io/badge/Email-gracianbaenagonzalez-ea4335?style=for-the-badge&labelColor=06070a&logo=gmail&logoColor=white)](mailto:gracianbaenagonzalez@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gracianbaena-0A66C2?style=for-the-badge&labelColor=06070a&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gracianbaena)
[![GitHub](https://img.shields.io/badge/GitHub-GracianB-f4f3ee?style=for-the-badge&labelColor=06070a&logo=github)](https://github.com/GracianB)

</div>

---

<div align="center">

**Personas × Datos × Sistemas · Yoga × Presencia**

<sub>Gracián Baena · 2026 · España</sub>

</div>
