# 📦 Darius Rey - CV Komplettpaket

**Für GitHub Username:** Xrey167
**Ziel-URL:** https://xrey167.github.io/cv/

---

## 📂 Paketinhalt

```
cv-complete-package/
├── 📄 index.html                      # Dein kompletter CV
├── 📋 README.md                       # Diese Datei
├── 🚀 DEPLOY.md                       # Detaillierte Deployment-Anleitung
├── ⚡ SCHNELLSTART.md                 # Quick-Start (5 Minuten)
├── 👤 SETUP-XREY167.md                # Personalisierte Anleitung für dich
├── 🔧 deploy.sh                       # Auto-Deploy Script (vorbefüllt)
├── 📁 certificates/                   # Ordner für Zeugnisse
│   ├── PDFS-HINZUFUEGEN.md           # ⚠️ WICHTIG: PDF Anleitung
│   ├── Florapharm_Zeugnis.pdf        # ⬅️ HIER PDFs ablegen
│   ├── IFS_Arbeitszeugnis.pdf        # ⬅️ HIER PDFs ablegen
│   ├── IHK_Pruefungszeugnis.pdf      # ⬅️ HIER PDFs ablegen
│   └── Schulabschlusszeugnis.pdf     # ⬅️ HIER PDFs ablegen
└── .gitignore                         # Git-Konfiguration
```

---

## 🚀 SCHNELLSTART (5 Minuten)

### Schritt 1: PDFs hinzufügen ⚠️

**WICHTIG:** Kopiere deine 4 PDF-Zeugnisse in den `certificates/` Ordner!

Benötigte Dateien (EXAKTE Namen):
- `Florapharm_Zeugnis.pdf`
- `IFS_Arbeitszeugnis.pdf`
- `IHK_Pruefungszeugnis.pdf`
- `Schulabschlusszeugnis.pdf`

📖 Siehe `certificates/PDFS-HINZUFUEGEN.md` für Details

### Schritt 2: Zu GitHub hochladen

**Option A - Web (Einfacher):**
1. Gehe zu: https://github.com/new
2. Name: `cv` | Public ✓ | Create
3. "uploading an existing file"
4. Ziehe ALLE Dateien aus diesem Ordner rein
5. Commit: "🎉 Initial CV" → Commit changes

**Option B - Terminal:**
```bash
cd /pfad/zu/cv-complete-package
./deploy.sh
```

### Schritt 3: GitHub Pages aktivieren

1. https://github.com/Xrey167/cv/settings/pages
2. Source: "Deploy from a branch"
3. Branch: "main" | Folder: "/ (root)"
4. Save

**Warte 1-2 Minuten** → Fertig!

🎉 **Dein CV:** https://xrey167.github.io/cv/

---

## 📖 Dokumentation

### Für Anfänger:
1. **SCHNELLSTART.md** - 5-Minuten Setup
2. **certificates/PDFS-HINZUFUEGEN.md** - PDF-Anleitung

### Für Erfahrene:
1. **DEPLOY.md** - Vollständige Anleitung
2. **SETUP-XREY167.md** - Personalisiert für dich

### Automatisch:
```bash
./deploy.sh  # Alles automatisch deployen
```

---

## ✅ Pre-Deployment Checkliste

- [ ] ⚠️ 4 PDFs in `certificates/` Ordner kopiert
- [ ] Dateinamen geprüft (siehe PDFS-HINZUFUEGEN.md)
- [ ] Lokal getestet (`python3 -m http.server 8000`)
- [ ] GitHub Repository erstellt
- [ ] Dateien hochgeladen
- [ ] GitHub Pages aktiviert
- [ ] Online getestet

---

## 🎯 Was funktioniert SOFORT:

✅ Kompletter CV (alle Tabs)
✅ Responsive Design (Mobile/Desktop)
✅ Timeline mit Berufserfahrung
✅ Tech Stack Visualisierung
✅ Projekte & Algo Trading Dashboard
✅ Skills & Qualifikationen

⚠️ Was du noch tun musst:

❗ PDFs in `certificates/` kopieren → Dann funktionieren Downloads

---

## 🆘 Probleme?

### Downloads funktionieren nicht:
→ Prüfe: Sind die PDFs im `certificates/` Ordner?
→ Prüfe: Sind die Dateinamen EXAKT wie in PDFS-HINZUFUEGEN.md?

### Seite lädt nicht:
→ GitHub Pages aktiviert?
→ 1-2 Minuten gewartet?
→ Cache geleert? (Strg+F5)

### Weitere Hilfe:
- 📖 Lies DEPLOY.md (Troubleshooting Sektion)
- 💬 GitHub Issue erstellen
- 🔍 Google: "github pages [dein problem]"

---

## 🎨 Personalisierung (Optional)

### Kontaktdaten hinzufügen:
Siehe `SETUP-XREY167.md` → Abschnitt "Personalisierung"

### Farben ändern:
Öffne `index.html`, suche `:root` (Zeile ~30)

### Eigene Domain:
Siehe `DEPLOY.md` → Abschnitt "Domain verbinden"

---

## 📊 Features

- 📱 Vollständig responsive
- 🎨 Modernes Dark Theme
- 📈 Interaktive Charts
- 🏆 Download-Links für Zeugnisse
- ⚡ Keine Abhängigkeiten
- 🔒 Datenschutzfreundlich (keine Cookies/Analytics)

---

## 🌟 Nach dem Deployment

**Deine URLs:**
- Hauptseite: https://xrey167.github.io/cv/
- Timeline: https://xrey167.github.io/cv/#timeline
- Zeugnisse: https://xrey167.github.io/cv/#certificates
- Repository: https://github.com/Xrey167/cv

**Teilen:**
- LinkedIn: Link zum CV teilen
- Bewerbungen: URL angeben
- E-Mail Signatur: CV-Link einfügen

---

## 🔄 Updates

```bash
# Änderungen machen
# Dann:
git add .
git commit -m "✨ Update: [Beschreibung]"
git push

# Oder einfach:
./deploy.sh
```

---

## 💡 Tipps

1. **Backup:** Behalte dieses ZIP als Backup
2. **Testing:** Teste lokal vor jedem Push
3. **Mobile:** Teste auf echten Mobilgeräten
4. **PDFs:** Halte PDFs aktuell (neue Zeugnisse)
5. **Privacy:** Keine persönlichen Daten wenn öffentlich

---

**Geschätzte Setup-Zeit:** 5-10 Minuten
**Technisches Level:** ⭐⭐☆☆☆ (Einfach)
**Kosten:** Kostenlos

Viel Erfolg mit deinem CV! 🚀

---

**Support:**
- 📖 Lies die Dokumentation
- 💬 GitHub Issues
- 🔍 Google ist dein Freund

**Zuletzt aktualisiert:** November 2024
**Version:** 1.0
