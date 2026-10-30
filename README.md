<div align="center">

# ⚡ Cyber Swiss Army Knife

**Das Cybersecurity- & Dev-Schweizer-Taschenmesser für Smartphone und Desktop.**
Eine einzige HTML-Datei. Keine Server. Keine Tracker. Alles läuft lokal in deinem Browser.

[![License: MIT](https://img.shields.io/badge/License-MIT-00ffa3.svg?style=for-the-badge)](LICENSE)
[![Made with HTML/CSS/JS](https://img.shields.io/badge/Made%20with-HTML%20%7C%20CSS%20%7C%20JS-00d4ff?style=for-the-badge)](#)
[![No Dependencies](https://img.shields.io/badge/Dependencies-0-ff2e93?style=for-the-badge)](#)
[![Buy Me A Coffee](https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/3rr0r303YT)

</div>

---

## 📸 Screenshots

| Passwort-Generator | Hash & Text | System-Info | Notizen |
|:---:|:---:|:---:|:---:|
| ![Passwort](docs/screenshot-password.png) | ![Hash](docs/screenshot-hash.png) | ![System](docs/screenshot-system.png) | ![Notizen](docs/screenshot-notes.png) |

> 📱 Mobile-Ansicht: `docs/screenshot-mobile.png`
> *(Platzhalter – Screenshots in den Ordner `docs/` legen.)*

---

## ✨ Features

| Tool | Beschreibung |
|---|---|
| 🔑 **Passwort-Generator** | Kryptografisch sicher (`crypto.getRandomValues`), Länge 6–128, Klein-/Großbuchstaben, Zahlen, Sonderzeichen, Ausschluss ähnlicher Zeichen, Entropie-Anzeige, Copy-to-Clipboard |
| #️⃣ **Hash- & Text-Converter** | MD5, SHA-1, SHA-256, SHA-512 live während der Eingabe, Base64 Encode/Decode (UTF-8-sicher), URL Encode/Decode |
| 🖥️ **System-Info-Checker** | User-Agent, Bildschirm & Viewport, CPU-Kerne, RAM, Sprache, Zeitzone, Online-Status, Verbindungstyp, öffentliche IP |
| 📝 **Quick-Notizblock** | Mehrere Notizen, Auto-Save via `localStorage`, JSON-Export |
| 🎨 **Cyberpunk-Design** | Dark Theme, Neon-Akzente, voll responsive (Android, iOS, Desktop) |

### 🔒 Datenschutz

- **Keine Telemetrie, keine Cookies, keine externen Bibliotheken.**
- Passwörter, Hashes und Notizen verlassen **nie** dein Gerät.
- Einzige Netzwerkanfrage: die Abfrage der öffentlichen IP bei `api.ipify.org` – nur im Tab *System-Info*. Zum Entfernen die Funktion `fetchIP()` in `index.html` löschen.

---

## 🛠️ Installation

### Variante 1: GitHub Pages (empfohlen)

1. Repository **forken** oder neues Repo `cyber-swiss-army-knife` anlegen.
2. `index.html`, `README.md` und `LICENSE` ins Repo hochladen.
3. **Settings → Pages → Build and deployment**
   - Source: `Deploy from a branch`
   - Branch: `main` · Ordner: `/ (root)`
4. Speichern. Nach ca. 1 Minute erreichbar unter:
   ```
   https://<dein-username>.github.io/cyber-swiss-army-knife/
   ```

### Variante 2: Lokal

```bash
cd /pfad/zum/projektordner
xdg-open index.html        # Linux
# open index.html          # macOS
# start index.html         # Windows
```

Oder mit lokalem Server:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

### Variante 3: Als App auf dem Smartphone

Seite öffnen → Browser-Menü → **„Zum Startbildschirm hinzufügen"**.

> ℹ️ SHA-Hashes nutzen die Web-Crypto-API und brauchen einen sicheren Kontext (**HTTPS** oder `localhost`). GitHub Pages erfüllt das automatisch.

---

## 🗂️ Projektstruktur

```
cyber-swiss-army-knife/
├── index.html     # Die komplette App (HTML + CSS + JS)
├── README.md
├── LICENSE
└── docs/          # Screenshots
```

---

## 🧭 Roadmap

- [ ] PWA / Offline-Support (Service Worker)
- [ ] JWT-Decoder
- [ ] Hex- / Binär-Converter
- [ ] QR-Code-Generator
- [ ] Passphrasen-Generator (Diceware)
- [ ] Hell/Dunkel-Umschalter

---

## 🤝 Contributing

1. Fork erstellen
2. Branch anlegen: `git checkout -b feature/mein-feature`
3. Committen: `git commit -m "Add: mein Feature"`
4. Pushen: `git push origin feature/mein-feature`
5. Pull Request öffnen

Bitte keine externen Abhängigkeiten hinzufügen – das Projekt bleibt eine einzige Datei.

---

## ❤️ Unterstützen

Wenn dir das Projekt gefällt, freue ich mich über einen Stern ⭐ und einen Kaffee ☕

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/3rr0r303YT)

---

## 📄 Lizenz

Veröffentlicht unter der **MIT-Lizenz** – siehe [LICENSE](LICENSE).

```
MIT License © 2026 3rr0r
```

---

<div align="center">

**Made with ❤️ by [Real3rr0r303YT](https://github.com/Real3rr0r303YT)**

</div>
