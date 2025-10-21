# 🌍 World Uncertainty Index – Interaktive Karte

Ein interaktives Visualisierungstool des **World Uncertainty Index (WUI)**, das globale wirtschaftliche Unsicherheiten zwischen **2015 und 2025** auf einer modernen Weltkarte darstellt.  
Die Anwendung basiert auf **HTML, CSS und JavaScript** (Leaflet.js) und bietet vielfältige Analysefunktionen.

<img width="1871" height="923" alt="image" src="https://github.com/user-attachments/assets/c6b0753b-842b-4dc3-9a4c-9f9592e3c591" />

---

## 🚀 Features

- 🗺️ **Interaktive Weltkarte** mit farbcodierten Ländern nach Unsicherheitswert  
- 📅 **Zeitstrahl (2015–2025)** mit Schieberegler und animierter Wiedergabe  
- 📊 **Statistik-Dashboard** mit:
  - globalem Durchschnitt & Median  
  - Top-5- und Bottom-5-Ländern je Jahr  
- 🌙 **Dark Mode** & ☀️ **Light Mode**  
- 🔍 **Ländersuche** mit Zoom und Detailansicht  
- 📈 **Länderprofile** mit historischem Verlauf und Ranking  
- 💡 **Tastatursteuerung:**  
  - ← / → Jahr wechseln  
  - Leertaste = Abspielen / Pause  
- ⛶ **Vollbildmodus**  
- 🧠 **Zwei Ansichten:**
  - *Absolutwerte* (WUI-Level)  
  - *Änderungen* (Differenz zum Vorjahr)

---

## 🧰 Technologien

- **Leaflet.js** – für interaktive Karten  
- **HTML5 / CSS3 / Vanilla JavaScript**  
- **GeoJSON** – Datenstruktur für WUI-Werte  
- **OpenStreetMap & CartoDB Tiles** – als Kartenbasis

---

## 📂 Projektstruktur
└── index.html # Hauptanwendung  
└── wui_data.geojson # Datendatei mit Länderdaten  
└── README.md # Diese Datei  

> ⚠️ Stelle sicher, dass sich die Datei **`wui_data.geojson`** im selben Verzeichnis wie `index.html` befindet.

---

## 🧮 Datenquelle

Die Daten stammen vom offiziellen **[World Uncertainty Index](https://worlduncertaintyindex.com)** (The Economist / Stanford University).

---

## ▶️ Lokale Ausführung

Da Leaflet lokale Daten (GeoJSON) lädt, muss die Seite über einen Webserver ausgeführt werden.

---

## 🧑‍💻 Autor

**Philipp Watzke**  
📧 p.watzke@prospega.de  
📅 Erstellt: Oktober 2025
