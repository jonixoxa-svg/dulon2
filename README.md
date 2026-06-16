# Dulon Residence — sajt njëfaqësh

Sajt elegant njëfaqësh për **Dulon Residence** (Dulon Group Sh.p.k), zhvillues
rezidencial në **Prishtinë e Re, Kosovë**. Skedar i vetëm `index.html` me CSS + JS
të integruar (pa framework), foto reale të projekteve, dhe efekte: gradient mesh i
animuar në hero mbi foto, scroll-reveal, numërues, navbar frosted, parallax,
cursor glow — me respekt për `prefers-reduced-motion`.

- **Brand:** Dulon Residence — *“rehatia që e meritoni”*
- **Lokacioni:** Prishtina e Re, Prishtinë
- **Instagram:** [@dulonshpk](https://instagram.com/dulonshpk)

## Strukturë
```
dulon-website/
├── index.html        # i gjithë sajti (HTML + CSS + JS)
├── images/           # foto reale të Dulon (dulon-*.jpg)
└── render.yaml       # Render Blueprint (static site)
```

## Si ta shohësh lokalisht
```bash
npx serve . --listen 4173
# hap http://localhost:4173
```

## Deploy në Render
1. Krijo një repo në GitHub (p.sh. `dulon2`) dhe bëj push këtë dosje.
2. Në Render: **New → Blueprint**, zgjidh repo-n → `render.yaml` e konfiguron vetë
   shërbimin `dulon2` (static, pa build).
   - Ose: **New → Static Site**, Publish Directory `.`, Build Command bosh.
3. Sajti del live në `https://dulon2.onrender.com`.
