# I-Talent App
De webapplicatie biedt een dynamische verzameling van I-Talent foto's, voorzien van korte uitleg in het onderschrift. Deze afbeeldingen zijn zorgvuldig verzameld uit alle uitgevoerde POP-sessies en seminaries, waarbij een breed scala aan talenten en vaardigheden in verschillende situaties is vastgelegd. Via deze webapplicatie kun je op een handige manier een beter inzicht krijgen in de uiteenlopende activiteiten die tijdens I-talent gevolgd kunnen worden.

https://user-images.githubusercontent.com/91525259/232122300-0b8b910e-3578-47e0-832f-cb3900a42d2b.mp4

## Frontend
Gebruikte technologie: Angular 12

De API url is gedefinieerd in het bestand `/frontend/environments/environment.prod.ts`. Deze waarde wordt ingesteld door het argument `APIURL` in het bestand `docker-compose.yml`.

## Backend
Gebruikte technologie: NodeJS + express + mongoose

De afbeeldingscarrousel-URL's bevinden zich in het bestand `/backend/data/carrousel.json`

## Requirements
* Docker geïnstalleerd op host
* Git command line tool

## Setup
1. Clone de repository via `git clone https://github.com/Bartc3/I-Talent-App.git` 
2. Navigeer naar de plaats waar deze directory zich bevind
3. Voer `docker-compose build` uit en vervolgens `docker-compose up`
5. De website is bereikbaar via `http://localhost` in de browser
