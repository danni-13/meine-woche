# 📱 Meine Woche – App-Installation Schritt für Schritt

## Was du brauchst
- Einen **kostenlosen GitHub-Account** (github.com)
- Diese 5 Dateien (alle im gleichen Ordner):
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`

---

## Schritt 1 – GitHub-Account erstellen
1. Gehe zu **github.com**
2. Klicke auf **Sign up**
3. E-Mail, Passwort, Benutzername eingeben → bestätigen
4. Gratis-Plan wählen

---

## Schritt 2 – Neues Repository erstellen
1. Nach dem Einloggen oben rechts auf **+** → **New repository**
2. Name: `meine-woche` (genau so, ohne Leerzeichen)
3. Auf **Public** stellen ✅
4. Ganz unten: **Create repository** klicken

---

## Schritt 3 – Dateien hochladen
1. Im neuen Repository: **uploading an existing file** klicken
   (oder den Button "Add file" → "Upload files")
2. Alle 5 Dateien per Drag & Drop ins Fenster ziehen:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Unten auf **Commit changes** klicken

---

## Schritt 4 – GitHub Pages aktivieren
1. Im Repository oben auf **Settings** klicken
2. Links im Menü: **Pages** klicken
3. Unter "Source": **Deploy from a branch** wählen
4. Branch: **main** · Ordner: **/ (root)** → **Save**
5. Nach 1–2 Minuten erscheint oben ein grüner Link:
   `https://DEIN-NAME.github.io/meine-woche`

---

## Schritt 5 – App auf dem Handy installieren

### iPhone (Safari):
1. Den Link `https://DEIN-NAME.github.io/meine-woche` in **Safari** öffnen
2. Unten auf das **Teilen-Symbol** tippen (Quadrat mit Pfeil nach oben)
3. **"Zum Home-Bildschirm"** antippen
4. Name lassen wie er ist → **Hinzufügen**
5. ✅ Fertig! Das App-Icon erscheint auf deinem Homescreen

### Android (Chrome):
1. Den Link in **Chrome** öffnen
2. Oben rechts auf die **drei Punkte** tippen
3. **"Zum Startbildschirm hinzufügen"** oder **"App installieren"**
4. ✅ Fertig!

---

## 🔒 Deine Daten bleiben privat
- Alle Daten werden nur lokal auf deinem Handy gespeichert (localStorage)
- Nichts wird an GitHub oder irgendwo anders gesendet
- Die App funktioniert auch **offline** nach der ersten Nutzung

---

## 🔄 App aktualisieren (wenn du Änderungen bekommst)
Einfach die neue `index.html` erneut bei GitHub hochladen (Upload files → Commit).
Nach 1–2 Minuten ist die App automatisch aktuell.
