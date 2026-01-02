# Installatie Front-end

## Les 1

Check of node en npm de juiste versie hebben:

`node -v` versie 22 of 24

`npm -v` versie 10

- Installeer node/npm indien nodig: https://nodejs.org/en/download (Scroll naar beneden voor installer van een prebuilt
  versie)

<!--
* vite project met react aanmaken
  https://vite.dev/guide/
  `npm create vite@latest`
  React - Javascript
* npm install -->

Maak een nieuw React project aan:

Via onderstaande link vind je de installatiehandleiding om een project met Vite en Tailwind te installeren.

Stap 1 creëert het project. Dit kan daarom **NIET** vanuit een project in PHPStorm, maar moet via de 'gewone' terminal.

Kies tijdens de installatie voor React, Javascript en no rolldown-vite.

Na stap 1 kan je het project openen in PHPStorm en de andere stappen via de terminal van PHPStorm uitvoeren.

Let op dat je bij stap 3 niet de hele config overneemt, maar alleen de aanpassing maakt om tailwind in de plugins array
toe te voegen.

Bij stap 4 vervang je de inhoud van `index.css` door `@import "tailwindcss";`

- https://tailwindcss.com/docs/installation/using-vite.

- Als je klaar bent, is App.css niet meer nodig en kun je deze verwijderen ( evenals de import ervan), en kan je meteen
  alle andere default code verwijderen uit `App.jsx`.

- Disable warnings over prop types in `eslint.config.js`:

```
"rules": {
    "react/prop-types": 0
  }
```

## Les 3

React Router

- Voeg React router toe aan je project: `npm install react-router`

## Les 8/9

JSON web tokens

- Voeg een JWT decoder toe aan je project: `npm install jwt-decode`
