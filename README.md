🍝 Bella Italia – Bootstrap Restaurant Website
Willkommen bei Bella Italia – einem modernen, responsiven Restaurant-Projekt mit Bootstrap 5.
Diese Seite präsentiert ein fiktives italienisches Restaurant mit Fokus auf Benutzerfreundlichkeit, stilvollem Design und Dark Mode-Option.

📸 Vorschau

✨ Features
✅ Bootstrap 5 Grid-System

✅ Responsive Navigation mit Logo

✅ Hero-Image mit Button zur Speisekarte

✅ Bewertungs-Karten mit Sternen

✅ Speisekarte & Öffnungszeiten

✅ Kontaktformular

✅ Vollständiger Dark Mode (umschaltbar)

✅ Separate „Über uns“-Seite

✅ Mobile optimiert

🌙 Dark Mode Funktion
Der Dark Mode lässt sich über einen Button oben rechts ein- und ausschalten.
Er funktioniert über eine einfache dark-mode-CSS-Klasse, die über JavaScript dem <body> hinzugefügt oder entfernt wird.

🔧 Vorgehensweise:
CSS-Styling in style.css oder im <style>-Tag:

css
Kopieren
Bearbeiten
body.dark-mode {
  background-color: #121212;
  color: #f8f9fa;
}

.dark-mode .hero-section,
.dark-mode .card,
.dark-mode .table,
.dark-mode .form-control,
.dark-mode textarea {
  background-color: #1e1e1e;
  color: #f8f9fa;
}
Dark Mode Button (direkt unter <body> einfügen):

html
Kopieren
Bearbeiten
<div class="position-fixed top-0 end-0 m-3 z-3">
  <button class="btn btn-sm btn-outline-dark" onclick="document.body.classList.toggle('dark-mode')">
    <i class="bi bi-moon-stars"></i> Dark Mode
  </button>
</div>
📁 Projektstruktur
arduino
Kopieren
Bearbeiten
bella-italia/
├── Restaurant.html
├── Überuns.html
├── style.css
├── /images (optional)
└── README.md
🚀 Installation & Nutzung
Projekt-Repo klonen oder ZIP herunterladen

Mit Visual Studio Code oder Browser öffnen

Optional: auf GitHub Pages hosten oder lokal testen

📬 Kontakt
Erstellt mit 🍷 und ❤️ von Zito

„Trage die italienische Seele mit Stil.“
