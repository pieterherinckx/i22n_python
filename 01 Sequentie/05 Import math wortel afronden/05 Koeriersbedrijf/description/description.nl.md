## Gegeven

Een koeriersbedrijf hanteert volgende regels voor het bepalen van de prijs van een pakje:

- een vaste `basisprijs` van € 2,00
- `massa`: extra per **begonnen** 20 gram: € 0,40  
Dit betekent dat voor een massa van 25 gram er € 0,80 betaald moet worden
- `afstand`: extra per **begonnen** 10 km: € 0,30  
Dit betekent dat voor een afstand van 13 km er € 0,60 betaald moet worden

## Gevraagd
- Schrijf een programma dat vraagt naar de **massa** van het pakje en de **afstand**;
- Bereken de prijs van het pakje volgens de gegeven formule;
- Geef de prijs op het scherm weer via een verzorgde volzin en **rond af op één decimaal**.


#### Voorbeeld

Indien een pakje van `68` gram over een afstand van `102` km vervoerd moet worden, dan verschijnt er:

```
De prijs om het pakje te versturen is 6.9 euro.
```

{: .callout.callout-info}
>#### Tips
> - Bereken het aantal extra kosten voor de massa en de afstand met behulp van de formule en `math.ceil()`.
> - Bereken de totale prijs door de basisprijs op te tellen bij de extra kosten voor massa en afstand.
