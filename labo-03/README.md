# Labo 3 - reflecties

Naam: (jouw naam)

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?
`list-style: none; en padding-left: 0;´ ik zag dit in Chrome, DevTools bij de user agent stylesheet.
- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?
De banden worden hoger, maar de tekstgrootte verandert niet.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
`text-align: center´ centreet de tekst.
`margin-left: auto; en margin-right: auto;´ centreren de kolom.
- Waarom werkte de padding op de knop pas na `display: inline-block`?
Omdat <a> standaard inline is. Met `display: inline-block` werkt het als een box en accepteerd het padding.

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?
De visuele breedte is 15rem, omdat `box-sizing: border-box´ in reset.css wordt gebruikt. Daardoor zitten de padding en border al in die 15rem.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?
Omdat `height: 70%` hier afhangt van zijn ouder main, en main zelf een vaste hoogte heeft.
- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
`margin: 15%` word berekend op basis van de breedte van main die 90vh is.


## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?
ik gaf `main`een `min-height`, omdat de hero minstens 80% van de vensterhoogte moet zijn.En met `min-height` kan de box va de `main` groter worden als de inhoud meer ruimte nodig heeft. 
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?
De tweede helft komt onder de eerste.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
