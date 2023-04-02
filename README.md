# Architecture overview
![UP-HRH-Auth](https://user-images.githubusercontent.com/30565750/210239617-c51801e5-73d4-49b9-a473-2426bd2b5d82.jpg)

### This service is the `BFF` service from the Architecture Diagram

[Postman Collection](https://api.postman.com/collections/17248210-81d16297-21ec-4100-96c2-a8375d30230f?access_key=PMAT-01GR22Q4K663YDVJ19N84NY2QA)

Steps to run the application

1. `npm i`
2. `npm i -g pm2`
3. `cp sample.env .env`
4. Edit the .env files according to your configuration of keycloak etc. 
```
This will run the service in background on the server. Allow ports accordingly if you want it to be accessible on internet.
```
3. `pm2 start npm --name "lr-service" -- start`

