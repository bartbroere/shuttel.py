# shuttel.py - *werkt geautomatiseerd je Shuttelportaal bij*

Dit script is bedoeld om automatisch je ritten in Shuttel te categoriseren als dienstreis of woon-werkverkeer.
Je roept het aan met drie argumenten, namelijk je gebruikersnaam, wachtwoord en standplaats.
Als je op een dag naar je standplaats reist worden alle ritten van die dag gecategoriseerd als woon-werkverkeer.
Als je op een dag niet naar je standplaats reist worden alle ritten van die dag gecategoriseerd als dienstreis.
Die regels zijn natuurlijk aan te passen in de code als je situatie anders is.

```bash
python3 shuttel.py login@organisatie.nl wachtwoord standplaats
```

Lees het script goed door en pas het indien nodig aan naar je eigen situatie.
Hoe je standplaats precies geschreven moet worden kun je vinden door in het Shuttel portaal te kijken.

Issues en pull requests zijn welkom. 
Bijdragen aan openstaande issues al helemaal.

## Draaien als Github Action
Deze repository is een template.
Als je hem gebruikt om een nieuwe repository te maken kun je hem direct draaien als Github Action.
Dit gebeurt standaard iedere zaterdag, en op 31 december als je 's avonds aan de oliebollen zit zodat het jaar netjes wordt afgesloten.
Hiervoor moet je drie secrets toevoegen aan je repository, namelijk `USERNAME`, `PASSWORD` en `STANDPLAATS`.

## CO2 rapportageplicht
Elke werkgever met meer dan 100 werknemers is verplicht om een CO2 rapportage te maken.
Van reizen moet bijvoorbeeld worden bijgehouden of het woon-werkverkeer of dienstreizen zijn, welke brandstof er wordt gebruikt en hoeveel kilometers er worden gemaakt.

De hele CO2 rapportageplicht is natuurlijk een ontzettende papieren tijger, in het bijzonder voor verplaatsingen in het openbaar vervoer.
Een dienstreis in de trein stoot evenveel CO2 uit als woon-werkverkeer in de trein.
Tegelijkertijd kunnen werkgevers met personeel met lease-auto's een willekeurige gok gebruiken om de verhouding privé en zakelijk gebruik te rapporteren:
["U kunt dit doen op basis van een forfaitair aantal kilometers per voertuig. 
‘Forfaitair’ wil zeggen: een fictief, vastgesteld aantal. 
Dit aantal kilometers is gebaseerd op wat gemiddeld in Nederland privé met een vervoermiddel wordt gereden."](https://www.rvo.nl/sites/default/files/2024-01/Handreiking-Gegevensverzameling-werkgebonden-personenmobiliteit_december2023.pdf)

## Disclaimer
Dit script is een hulpmiddel, dus gebruik het niet als je hem niet begrijpt.
Je blijft zelf verantwoordelijk voor je administratie.
