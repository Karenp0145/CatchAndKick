# 👟 Catch & Kick

This is our very first coding project, made at Hetic. An interactive web interface featuring an instant win game, designed to collect and personalize user data in an engaging way. Currently in progress. 🚧

## Overview

The project covers a variety of essential topics such as :

* Multi-page user flow (form → preferences → game → result)
* User data collection and personalization
* Interactive mini-game built in JavaScript
* Random prize logic with a rare golden sticker
* Responsive layout and UI design

## Pages

### Formulaire
* Collects user information
* First step of the flow

### Préférences
* Users share their preferences
* Answers influence the final prize

### Jeu
* A shoebox slides horizontally across the screen
* Stickers fall randomly from the top
* The goal is to catch them in the basket
* Rarely, a golden sticker appears — catching it wins the jackpot (€50)
* Regular stickers result in a personalized discount based on preferences

### Résultat
* Displays a personalized discount based on preferences
* Or a €50 prize for the lucky golden sticker winners

### Règlement
* Terms and conditions. Currently in progress. 🚧
* Available as a separate page

## Built With

* HTML5
* CSS3
* JavaScript (game logic & interactions)

## Structure

```
catch-and-kick/
├── index.html          # Formulaire
├── preferences.html
├── jeu.html
├── resultat.html
├── reglement.html
├── assets/
│   ├── styles/
│   └── js/
```
