# Plan – Min Portfolio

En statisk portfolio i ren HTML och CSS, byggd efter Figma-filen "Min Portfolio" (frame "Portfolio", node 49-302).

## Förutsättningar
- Ren HTML och CSS, inga ramverk och inget byggsteg.
- Desktop följer Figma exakt: mått, färger och typsnitt läses från Figmas inspect-läge.
- Det finns bara en desktop-design, så mobil och surfplatta tolkas från den.
- Ytor som är tomma i Figma lämnas tomma.
- Git-repo med en commit när planen är klar och sedan en commit efter varje steg.

## Filstruktur
```
min-portfolio/
├── index.html
├── css/
│   ├── reset.css      # enkel normalisering
│   └── style.css      # variabler, layout, komponenter, media queries
├── images/            # exporterade bilder från Figma (t.ex. molnbilden)
└── PLAN.md
```

## Steg

### Steg 0 – Förberedelser
- [ ] Installera git (görs av användaren)
- [ ] Logga in på Figma i webbläsarpanelen (görs av användaren)
- [ ] `git init` och commit av planen

### Steg 1 – Designtokens och grundstruktur
- [ ] Läs av färger, typsnitt, textstorlekar, ramar, hörnradier och avstånd från Figma
- [ ] Skapa `index.html` med semantiskt skelett (`header`, `main`, `section`, `footer`)
- [ ] Skapa `reset.css` och `style.css` med CSS-variabler för tokens
- [ ] Länka in typsnitt (Google Fonts eller lokala filer)
- [ ] Commit

### Steg 2 – Header och navigation
- [ ] Logotyp-pill "Min Portfolio" till vänster
- [ ] Tre gröna pill-knappar till höger (Start, About, Contact)
- [ ] Commit

### Steg 3 – Hero
- [ ] Exportera molnbilden från Figma till `images/`
- [ ] Hero med bakgrundsbild och vit rubrikruta "Digital designer based in Gothenburg"
- [ ] Namn-pill "Valeria Mikkola - Digital Designer" under hero
- [ ] Commit

### Steg 4 – Mittsektionerna
- [ ] Gula avdelarband och tomma vita sektioner med svarta linjer, exakt som i Figma
- [ ] Rubrik-pill ovanför korten
- [ ] Commit

### Steg 5 – Kortraden och footer
- [ ] Rad med fyra färgade kort (lila, rosa, orange, ljusblå) med samma bredder och gradienter som i Figma
- [ ] Ljusblått band och svart footer
- [ ] Commit

### Steg 6 – Responsivitet
- [ ] Brytpunkter: surfplatta (≤ 1024px) och mobil (≤ 640px)
- [ ] Navigationen bryts om eller staplas, rubrikstorlekar skalas med `clamp()`
- [ ] Korten går över till 2 kolumner och sedan 1 kolumn
- [ ] Ingen horisontell scroll vid 320px
- [ ] Commit

### Steg 7 – Kontroll mot Figma
- [ ] Jämför sida vid sida med Figma på desktop och justera avvikelser
- [ ] Testa på 375px, 768px, 1024px och 1440px
- [ ] Kontrollera tillgänglighet: alt-texter, kontrast, fokusmarkeringar
- [ ] Slutlig commit
