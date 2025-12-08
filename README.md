# LiftED

LiftED ist eine Projektwebseite in der wir Körperlichen als auch geistigen Fortschritt kombinieren wollen. Das Ziel ist es, Komilitonen, die keine Zeit haben sich stundenlang in die Trainingslehre 
einzulesen und neben her noch zu studieren, eine Möglichkeit zu bieten beide Elemente mit einander zu verbinden. Einerseits stellen wir Trainings- und Essenspläne bereit. Andererseits bieten wir Lern-
Inhalte für das erste Semester aus dem Wirtschaftsinformatik Studium.

## Features
- ansprechende Landing page - schneller Überblick über die Webseite
- 3 verschiedene Trainingspläne mit dem Fokus auf unterschiedliche Freizeit
- 3 verschiedene Essenskategorien für jeden Körpertypen
- E-learnings für jedes unserer Prüfungsfächer im 1. Semester
- Responsive Layouts und interaktive Karten/Boxen
- wiederverwendbare (und animierter) Header und Footer
- zentrales globales Stylesheet

## Projektstruktur
root/
├── assets/
│   └── css/
│       └── styles.css
├── components/
│   └── header.html
├── img/
│   ├── blocks/
│   │   └── README.md
│   ├── meals/
│   │   └── *.(png|jpg|webp)             # Bilder zu einzelnen Gerichten
│   └── logos/
│       └── *.webp                       # Bilder wie Logo etc.
├── pages/
│   ├── general/
│   │   └── index.html
│   │   └── service.html
│   │   └── sofunktionierts.html
│   ├── learning/
│   │   ├── learning.html
│   │   └── modules/
│   │       └── module-*.html            # einzelne Lernmodule
│   ├── meals/
│   │   ├── meals.html           
│   │   └── recipes/             
│   │       └── recipe-*.html            # einzelne Rezeptseiten
│   └── training/
│       ├── plans/
│       │   └── plan-*.html      # z. B. plan1.html, plan2.html ...
│       └── training_plan.html   # ggf. allgemeine Übersichts-/Detailseite
└── README.md

## Barierefreiheit
Wir orientieren uns an WCAG 2.1 AA in teilen AAA:
- Skip-Link für Screenreader
- ausreichende Kontraste
- ARIA-Labels für Navigationsmenüs
- Fokuszustände sichtbar
- semantische HTML-Struktur

## Komponenten
- Nutzung von Vektorgrafik für Logo -> für besseres Skaling
- Nutzung von WebP-Bildern für schnellere Ladezeiten
- Einsatz kleiner GIFs für leichte Animationen
- wiederverwendbare Strukturen (header.html/footer.html)
Diese Dateien werden in jede Seite integriert und enthalten Navigation, Logo und Barrierefreiheits-Elemente wie Skip-Links. 

## Bekannte Einschränkungen
- Videos & hochauflösende Bilder können Ladezeit beeinflussen
- Noch keine serverseitige Logik

## To-Do / Weiterentwicklung
- Benutzeraccounts + Login
- Fortschrittsanalyse (Tracking)
- Dynamische Rezeptfilter & Trainingsplan-Generator
- Search-Funktion
