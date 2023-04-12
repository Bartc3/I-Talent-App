# PXL 3 tier web application sample app

## frontend
Angular 12

## API url
The API url is defined in the file `/frontend/environments/environment.prod.ts`. This value gets set by the `APIURL` argument in the `docker-compose.yml` file. The multistage dockerfile uses this value before the build process.

## Backend
NodeJS + express + mongoose

there is a `/health` endpoint for a healthcheck

image carrousel urls are located in `/backend/data/carrousel.json`

### Database
MongoDb

## Setup
* run `docker-compose build && docker-compose up` to boot
