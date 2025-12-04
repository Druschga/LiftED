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
root
├── assets/
│ └──css/
│ │ └──styles.css
├── components/
│ └──header.html
├── img/
│ └── blocks/
│ │ └── README.md
│ └── meals/
│ │ └── *.html                # mehrere meals
│ └── logos*.webp
├── muscle/
│ └── *body/
│ │ └── muscle*/              # 2 Unterordner
│ │ │ └── machines*.html      # Erklärungsseiten für die verschiedenen Maschinen
│ │ │ └── muscle.html
│ │ │ └── muscle.gif
├── pages/
│└── general/
│ │ └── *.html                # landingpage etc
│ └── learning/
│ │ └── learning.html
│ │ └── modules/
│ │ │ └── modules*.html      # Die Lermodula
│ └── meals/
│ │ └── meals.html
│ │ └── recepies/
│ │ │ └── recepes*.html      # Verschiedene Rezepte
│ └── training/
│ │ └── plans/
│ │ │ └── plans*.html        # 3 verschiedene Trainingspläne
│ │ └── training_plan-html
│ │ └── uebungen.html
