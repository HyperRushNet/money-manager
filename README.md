# Money Manager - Oneindige Datum Scroll

Een eenvoudige en moderne money management webapp waarmee je inkomsten en uitgaven kunt bijhouden.  
De app toont een balkgrafiek met het netto resultaat per maand, waarbij je oneindig kunt scrollen door de tijd (verleden en toekomst).

---

## Features

- Toevoegen van inkomsten en uitgaven met omschrijving en bedrag  
- Automatisch maandelijks inkomen van €10 vanaf 1 december 2024  
- Overzicht van alle transacties met mogelijkheid tot verwijderen (behalve automatische maandinkomsten)  
- Dynamische balkgrafiek met netto saldo per maand:  
  - Groen = positief  
  - Oranje = 0  
  - Rood = negatief  
- Oneindige tijdlijn: blader naar vorige en volgende maanden, ook buiten het huidige jaar  
- Responsief ontwerp met Tailwind CSS  
- Data wordt lokaal opgeslagen in `localStorage` zodat je je gegevens behoudt  

---

## Hoe te gebruiken

1. Open het bestand `index.html` in een moderne browser.  
2. Voeg een transactie toe via het formulier (omschrijving, bedrag, type).  
3. Bekijk je actuele saldo bovenaan.  
4. Blader met de pijltjestoetsen onder de grafiek door de maanden heen.  
5. Verwijder handmatige transacties met het prullenbakje naast de transactie.  
6. Reset alles met de "Reset alles" knop.

---

## Technische details

- Startdatum van het maandelijks inkomen: **1 december 2024**  
- Maandelijks automatisch inkomen: €10  
- Chart: [Chart.js](https://www.chartjs.org/) voor de grafiek  
- Styling: [Tailwind CSS](https://tailwindcss.com/)  
- Dataopslag: `localStorage`  

---

## Toekomstige verbeteringen

- Synchronisatie met backend/database  
- Meer gedetailleerde categorieën  
- Exporteren/importeren van data  
- Grafiek animaties en tooltips verbeteren  

---

## Licentie

MIT © 2025

---

## Auteur

Gemaakt door ChatGPT (OpenAI)
