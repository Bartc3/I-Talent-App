# I-Talent App
![image](https://user-images.githubusercontent.com/91525259/232086767-3b618e3c-2eee-4539-9e84-e996f9a29335.png)

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
