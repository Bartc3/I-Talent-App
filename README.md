# I-Talent App

## frontend
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
3. Voer `docker-compose build` uit
4. Voer `docker-compose up` uit
5. De website is bereikbaar via `http://localhost` in de browser