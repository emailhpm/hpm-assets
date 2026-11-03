# HPM Assets

Öffentliche Dateien (PDFs, Bilder, Kalenderdateien), ausgeliefert über jsDelivr:

`https://cdn.jsdelivr.net/gh/emailhpm/hpm-assets@main/<pfad>`

jsDelivr hält `@main` bis zu 12 Stunden im Cache. Nach einer Änderung einmal
`https://purge.jsdelivr.net/gh/emailhpm/hpm-assets@main/<pfad>` aufrufen, dann ist sie sofort live.

`kalender/`: Kalenderdateien (.ics) für Buttons in Mails. Ein Klick auf iPhone oder Mac trägt den
Termin samt Erinnerungen in Apple Kalender ein. Den Link immer mit https:// setzen: webcal:// legt
ein Kalender-Abo an, und dabei entfernt Apple Kalender die Erinnerungen standardmäßig.
