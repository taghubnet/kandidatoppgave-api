# Kandidatoppgave API TagHub

Vi ønsker at dere lager et Restful API i python.

Dere kan benytte hvilke verktøy/bibliotek/rammeverk dere vil, men vi ønsker at det skal være enkelt for oss å teste.

## Spec

Lag et API som kan opprette brukere i en PostgreSQL database.

```
POST    /users       - opprette bruker
GET     /users       - list alle brukere
GET     /users/<id>  - returner den spesifikke brukeren
DELETE  /users/<id>  - slett den spesifikke brukeren
```

### POST /users

Opprett bruker i databasen med følgende felter;

```
id, brukernavn, epost, passord
```

Vi ønsker at brukernavn og epost skal være unike. Returner en feilmelding dersom noen forsøker å opprette en som finnes.

## GET /users

Returner alle brukerne i database.


## GET /users/<id>

Returner den spesifikke brukeren med id=<id>. Dersome den ikke finnes returner passende status kode.

## DELETE /users/<id>

Slett den spesifikke brukeren med id=<id> fra databasen. Dersome den ikke finnes returner passende status kode.

## Leveranse

Vi ønsker at dere oppretter en github bruker (om dere ikke allerede har dette), oppretter et public repo der, og benytter dette til å arbeide mot.
Når dere er i mål så er det bare å sende oss link til dette repo på GitHub.

## Hint

Ting vi ser etter;

* Godt strukturert kode
* Enkelt for oss å kjøre/teste koden deres
* Riktig bruk av http status koder og metoder (REST)
* Bruk av verktøy som forenkler prosessen (virtualenv, requirements.txt, etc.)

NB! Der er lov å spørre dersom man lurer på noe! Send spm. til `asbjorn@smartm.no`
