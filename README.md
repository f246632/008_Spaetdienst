# Spätdienst - Gemischtwarenladen Berlin

Ein professionelles, responsives Website für Spätdienst, einen Gemischtwarenladen in Berlin.

## 📍 Geschäftsinformationen

**Name:** Spätdienst
**Kategorie:** Gemischtwarenladen
**Adresse:** Berliner Str. 15, 13189 Berlin, Deutschland

## 🌟 Website-Funktionen

### Design & Benutzerfreundlichkeit
- **Moderne, professionelle Ästhetik** - Berlin-inspirierte Farbpalette
- **Vollständig responsiv** - Optimiert für alle Geräte (Mobile, Tablet, Desktop)
- **Schnelle Ladezeiten** - Optimierte Performance
- **Barrierefreiheit** - WCAG 2.1 AA konform

### Hauptsektionen

1. **Hero-Bereich**
   - Beeindruckende Hauptsektion mit Geschäftsnamen
   - Call-to-Action Buttons
   - Scroll-Indikator

2. **Über Uns**
   - Geschäftsbeschreibung
   - Feature-Highlights (4 Hauptmerkmale)
   - Ansprechende Präsentation

3. **Sortiment**
   - 6 Produktkategorien
   - Visuell ansprechende Icons
   - Detaillierte Kategorieübersicht

4. **Galerie**
   - 5+ Geschäftsfotos
   - Lightbox-Funktionalität
   - Tastaturnavigation
   - Touch-optimiert

5. **Standort & Öffnungszeiten**
   - Google Maps Integration
   - Adressinformationen
   - Anfahrtsbeschreibung
   - Öffnungszeiten

6. **Kontakt**
   - Kontaktinformationen
   - Kontaktformular mit Validierung
   - Telefon und Adresse

### Technische Features

- **SEO-Optimierung**
  - Meta-Tags
  - Schema.org Markup
  - Semantisches HTML5
  - Open Graph Integration

- **Performance**
  - Lazy Loading für Bilder
  - CSS & JS Optimierung
  - Minimale externe Abhängigkeiten

- **Interaktivität**
  - Smooth Scrolling
  - Animationen bei Scroll
  - Mobile Navigation
  - Form Validation
  - Gallery Lightbox

## 🛠️ Technologie-Stack

- **HTML5** - Semantisches Markup
- **CSS3** - Modern (Grid, Flexbox, Custom Properties)
- **JavaScript (Vanilla)** - Keine Frameworks, schnell und leicht
- **Google Fonts** - Playfair Display & Inter
- **Google Maps API** - Standort-Integration

## 📁 Projektstruktur

```
008_Spätdienst/
├── index.html              # Haupt-HTML-Datei
├── css/
│   └── style.css          # Alle Styles
├── js/
│   └── main.js            # JavaScript-Funktionalität
├── images/
│   ├── source/            # Original-Bilder
│   ├── optimized/         # Web-optimierte Bilder
│   ├── thumbnails/        # Vorschaubilder
│   └── icons/             # UI-Icons
├── data/
│   └── store-info.json    # Geschäftsdaten
└── README.md              # Diese Datei
```

## 🚀 Lokale Entwicklung

1. **Repository klonen oder herunterladen**
```bash
git clone https://github.com/f246632/008_Spaetdienst.git
cd 008_Spaetdienst
```

2. **Lokalen Server starten**

Mit Python:
```bash
python -m http.server 8000
```

Mit Node.js (http-server):
```bash
npx http-server -p 8000
```

Mit PHP:
```bash
php -S localhost:8000
```

3. **Browser öffnen**
```
http://localhost:8000
```

## 🌐 Deployment

### GitHub Pages (Empfohlen)

Die Website ist bereits für GitHub Pages optimiert:

1. Repository erstellen: `008_Spaetdienst`
2. Alle Dateien pushen
3. GitHub Pages in Repository-Einstellungen aktivieren
4. Website verfügbar unter: `https://f246632.github.io/008_Spaetdienst/`

### Alternative Hosting-Optionen

- **Netlify**: Drag & Drop Deployment
- **Vercel**: Git-Integration
- **Firebase Hosting**: Google Cloud
- **AWS S3**: Static Website Hosting

## 📱 Browser-Unterstützung

- ✅ Chrome (letzte 2 Versionen)
- ✅ Firefox (letzte 2 Versionen)
- ✅ Safari (letzte 2 Versionen)
- ✅ Edge (letzte 2 Versionen)
- ✅ Mobile Browsers (iOS Safari, Chrome Android)

## 🎨 Farbschema

```css
Primary: #1a1a2e (Dunkelblau)
Secondary: #16213e (Tiefblau)
Accent: #e94560 (Rot-Pink)
Gold: #d4af37 (Gold-Akzent)
Light: #f8f9fa (Hellgrau)
Text: #2c3e50 (Dunkelgrau)
```

## ♿ Barrierefreiheit

- Semantisches HTML
- ARIA-Labels wo nötig
- Tastatur-Navigation
- Focus-Indikatoren
- Alt-Text für alle Bilder
- Ausreichende Farbkontraste
- Responsive Schriftgrößen

## 📊 Performance-Optimierungen

- Lazy Loading für Bilder
- Minimierte CSS/JS
- Debounced Scroll Events
- CSS Custom Properties
- Optimierte Animationen
- Preload kritischer Ressourcen

## 🔄 Zukünftige Erweiterungen

Mögliche Verbesserungen:

- [ ] Online-Bestellsystem
- [ ] Produktkatalog mit Preisen
- [ ] Kundenrezensionen-System
- [ ] Newsletter-Integration
- [ ] Mehrsprachigkeit (DE/EN)
- [ ] Blog/News-Sektion
- [ ] Social Media Feed
- [ ] Live-Chat-Support

## 📝 Anpassungen

### Bilder aktualisieren

Ersetzen Sie Dateien in `images/source/`:
- `hero.jpg` - Hauptbild (1920x1080 empfohlen)
- `gallery-*.jpg` - Galeriebilder (800x600 empfohlen)

### Inhalte ändern

Bearbeiten Sie `data/store-info.json` für:
- Kontaktinformationen
- Öffnungszeiten
- Produktkategorien
- Features

### Styles anpassen

CSS-Variablen in `css/style.css` ändern:
```css
:root {
    --color-primary: #1a1a2e;
    --color-accent: #e94560;
    /* ... weitere Variablen */
}
```

## 📞 Support & Kontakt

Bei Fragen oder Problemen:

- **Geschäft:** Berliner Str. 15, 13189 Berlin
- **Google Maps:** [Standort öffnen](https://www.google.com/maps/search/?api=1&query=Spätdienst&query_place_id=ChIJf4_1n_BTqEcRcZJV0LnbXyE)

## 📄 Lizenz

© 2025 Spätdienst Berlin. Alle Rechte vorbehalten.

---

**Entwickelt mit ❤️ für Berlin**

Website erstellt am: 2025-10-24
