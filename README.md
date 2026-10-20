# BodyWise

Tweetalige (ES/EN) website met educatieve gezondheidsgidsen voor kinderen, tieners, volwassenen, ouders en scholen.

## Structuur

```
public/index.html     de hele site (HTML, CSS, JS)
public/images/        infographics (10 JPG-bestanden, ES en EN)
public/favicon.svg    logo-icoon
server.js             kleine Node-server (geen packages nodig)
package.json          start-script: npm start
railway.json          Railway-instellingen (healthcheck /health)
```

## Lokaal starten

```
npm start
```
Open daarna http://localhost:3000

## Op GitHub zetten

```
git init
git add .
git commit -m "BodyWise eerste versie"
git branch -M main
git remote add origin https://github.com/JOUW-GEBRUIKERSNAAM/bodywise.git
git push -u origin main
```
Maak eerst een lege repository aan op github.com (zonder README). Kies "Private" zolang de site nog niet af is.

## Op Railway zetten

1. Ga naar railway.com en log in met GitHub.
2. New Project > Deploy from GitHub repo > kies `bodywise`.
3. Railway herkent Node automatisch en gebruikt `npm start`. Er zijn geen variabelen nodig (PORT zet Railway zelf).
4. Settings > Networking > Generate Domain voor een gratis link, of voeg een eigen domein toe.

Elke `git push` naar `main` zet daarna automatisch een nieuwe versie online.

## Let op voor de verkoop

- Laat de gidsen over geestelijke gezondheid en medicijnen nakijken door een professional.
- Vervang de infographics met tekstfouten (zie lijst in het gesprek) voordat je gaat verkopen.
- Controleer de commerciële licentie van de AI-afbeeldingen.
- Voeg per land crisisnummers toe.
