# 🚀 Deployment Anleitung für "21 shots for niko"

## Option 1: GitHub Pages (Empfohlen - Kostenlos!)

### Schritt 1: Merge den Branch
1. Gehe zu: https://github.com/NikoCodeHub/lineup
2. Erstelle einen Pull Request vom Branch `claude/deploy-html-lineu-n8Gd6` zum `main` Branch
3. Merge den Pull Request

### Schritt 2: GitHub Pages aktivieren
1. Gehe zu deinem Repository: https://github.com/NikoCodeHub/lineup
2. Klicke auf **Settings** (Einstellungen)
3. Scrolle runter zu **Pages** im linken Menü
4. Unter **Source** wähle:
   - Branch: `main` (oder den Branch deiner Wahl)
   - Folder: `/ (root)`
5. Klicke auf **Save**

### Schritt 3: Deine Website ist live! 🎉
Nach ca. 1-2 Minuten ist deine Seite verfügbar unter:
```
https://nikocodehub.github.io/lineup
```

---

## Option 2: Netlify Drop (Super einfach!)

1. Gehe zu: https://app.netlify.com/drop
2. Ziehe die `index.html` Datei in das Upload-Feld
3. Fertig! Du bekommst sofort eine URL wie: `https://random-name.netlify.app`
4. Du kannst die URL später ändern in den Site Settings zu z.B. `lineup-21shots.netlify.app`

---

## Option 3: Vercel (Schnell & Professionell)

1. Gehe zu: https://vercel.com/new
2. Importiere dein GitHub Repository `NikoCodeHub/lineup`
3. Vercel erkennt automatisch das Projekt
4. Klicke auf **Deploy**
5. Deine Seite ist live unter: `https://lineup.vercel.app` (oder ähnlich)

---

## Option 4: Render.com (Kostenlos & Automatisch)

1. Gehe zu: https://render.com
2. Erstelle einen Account (kostenlos)
3. Klicke auf **New +** → **Static Site**
4. Verbinde dein GitHub Repository
5. Einstellungen:
   - Build Command: (leer lassen)
   - Publish Directory: `.`
6. Klicke auf **Create Static Site**
7. Deine Seite ist live!

---

## 🎯 Empfehlung

Für einen Link mit "lineup" empfehle ich **GitHub Pages**:
- URL wird sein: `https://nikocodehub.github.io/lineup`
- Kostenlos
- Automatische Updates bei jedem Push
- Professionell

---

## 📝 Notizen

- Die `index.html` ist bereits optimiert und bereit für Deployment
- Alle Styles sind inline, keine externen Abhängigkeiten
- Das Bild wird von imgur.com geladen
- Mobile-responsive Design ist bereits implementiert
