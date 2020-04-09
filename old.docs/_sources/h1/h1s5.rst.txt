H1S5
====

Volgende stappen
----------------

De volgende hoofdstukken bevatten voorbeelden van het gebruik van spreadsheets,
toegespitst op de verschillende vakken op school.

In deze voorbeelden worden ook nieuwe concepten ingevoerd.
Een overzicht van deze concepten volgt hieronder, samen met een beschrijving van deze voorbeelden.




* groei van functies

  * voor grotere N, factoren en lagere-orde termen irrelevant -> big-O notatie
  * verschil tussen lineair en kwadratisch
  * verschil tussen O(N log N) en O(N^2)
  * exponentiële groei

* modelleren en simuleren

  * begrip toestand; begintoestand
  * model in 1 regel spreadsheet, uitrekenen volgende toestand uit de vorige.
  * inputs in aparte kolommen

* richtlijnen voor simuleren:

  * tijd is verticaal, van boven naar beneden
  * gebruik 1 regel per toestand, voor het uitrekenen van de volgende uit de vorige.
  * inputs in de eerste kolommen
  * constanten, parameters in een apart blok, zo mogelijk benoemd. (voor groot model, op apart vel)
  * NB: als je benoemde parameters gebruikt dan kun je dit blok ook eenvoudig verplaatsen,
    je hoeft evt. alleen de definities van de namen aan te passen.
  * grafieken e.d. voor groot model ook op apart rekenvel

* meetgegevens en formulieren; statistiek

  * ook weer: 1 record/meting per regel
  * samenvatten/grafieken op een apart vel
    (tenzij het om weinig gegevens gaat, die je niet hoeft uit te breiden)
  * interpolatie? in een grafiek?

* data en databases

  * data in tabellen; tabel als relatie (relationele database)
  * spreadsheet-tabel als relatie
  * importeren van CSV-bestanden (en exporteren)
  * autofilter
  * filteren/selectie; groeperen en samenvatten; queries (?)
  * gebruik van aparte sheet voor samenvatten e.d.; draaitabellen.
    (Kun je draaitabellen ook in formules uitdrukken? Ik heb altijd problemen met het interface...)
  * redundantie in tabellen; beperkingen van spreadsheets;
    (Hoe geef je meerdere waarden in een kolom/cel aan?)
  * voorbeelden: (i) giro, waar blijft mijn zakgeld? (ii) ledenadministratie van een vereniging;
  * gebruik van spreadsheet in combinatie met "mail-merge" of ander programma om documenten aan te maken.

* richtlijnen voor data in tabellen:

  * record per rij, kolommen met vaste betekenis (type)
  * samenvatten op apart vel(len): je kunt dan gemakkelijker de data uitbreiden,
    en het werkt handiger als je veel rijen hebt (je hoeft dan niet steeds naar onder te scrollen).
  * je kunt op verschillende elementen sorteren, maar zorg dat je een natuurlijke key hebt om
    weer de "normale" situatie te herstellen.
    (Dit kan een volgnummer zijn, een naam, of een datum, bijv.)

* (lineaire) cellulaire automaten

  * toestand per rij

* algoritmen

  * uitschrijven van algoritme; stap per regel (of per 2 regels, soms)
  * lin. search (flauw)
  * bin. search
  * sorteren

* Enkele voorbeelden en oefeningen

Soorten rekenvellen
-------------------

Je kunt een rekenvel op verschillende manieren gebruiken.
Elke vorm heeft zijn eigen regels en toepassingen.

* data in tabellen

  * elke rij is een record
  * eerste rij bevat de kolomheaders
  * gegevens afkomstig uit een externe bron, met misschien enkele berekeningen
  * vaak geïmporteerd uit een CSV-bestand
  * gebruik van autofilter
  * functies voor het filteren en samenvatten van de data op een apart rekenvel.

* dashboard

  * mogelijk meerdere tabellen in één rekenvel
  * vaak gecombineerd met figuren
  * de tabellen groeien niet of nauwelijks
  * de tabellen vatten gegevens uit andere rekenvellen samen

* factuur(?)

  *

* functie

* simulatie (proces)

  * tijd is verticaal: elke volgende regel beschrijft de (een?) volgende toestand.
  * één regel beschrijft één toestand;
  * begin van rekenvel bevat initiële toestand (invoerdata)
  * (en soms de eerste kolom(men))
  * de rest van het rekenvel bestaat uit formules

..



Dit zijn

* groei van functies

  * voor grotere N, factoren en lagere-orde termen irrelevant -> big-O notatie
  * verschil tussen lineair en kwadratisch
  * verschil tussen O(N log N) en O(N^2)
  * exponentiële groei

* modelleren en simuleren

  * begrip toestand; begintoestand
  * model in 1 regel spreadsheet, uitrekenen volgende toestand uit de vorige.
  * inputs in aparte kolommen

* richtlijnen voor simuleren:

  * tijd is verticaal, van boven naar beneden
  * gebruik 1 regel per toestand, voor het uitrekenen van de volgende uit de vorige.
  * inputs in de eerste kolommen
  * constanten, parameters in een apart blok, zo mogelijk benoemd. (voor groot model, op apart vel)
  * NB: als je benoemde parameters gebruikt dan kun je dit blok ook eenvoudig verplaatsen,
    je hoeft evt. alleen de definities van de namen aan te passen.
  * grafieken e.d. voor groot model ook op apart rekenvel

* meetgegevens en formulieren; statistiek

  * ook weer: 1 record/meting per regel
  * samenvatten/grafieken op een apart vel
    (tenzij het om weinig gegevens gaat, die je niet hoeft uit te breiden)
  * interpolatie? in een grafiek?
  * https://www.engineerexcel.com/linear-interpolation-in-excel/; o.a. gebruik van MATCH
  * https://www.wallstreetmojo.com/linear-interpolation-in-excel/
  * https://exceloffthegrid.com/interpolate-values-using-the-forecast-function/
  * http://www.colby.edu/chemistry/PChem/notes/linest.pdf
  * opmerking over grafieken: alle programma's kunnen trendlijnen tekenen,
    maar in (i) Excel en OfficeLibre kun je het snijpunt voor x=0 ("intercept") afdwingen,
    in Google Sheets en in Apple Numbers niet. Dit laatste maakt het voor natuurkundige toepassingen
    minder geschikt (met de hand uitrekenen???).

* data en databases

  * data in tabellen; tabel als relatie (relationele database)
  * spreadsheet-tabel als relatie
  * importeren van CSV-bestanden (en exporteren)
  * autofilter
  * filteren/selectie; groeperen en samenvatten; queries (?)
  * gebruik van aparte sheet voor samenvatten e.d.; draaitabellen.
    (Kun je draaitabellen ook in formules uitdrukken? Ik heb altijd problemen met het interface...)
  * redundantie in tabellen; beperkingen van spreadsheets;
    (Hoe geef je meerdere waarden in een kolom/cel aan?)
  * voorbeelden: (i) giro, waar blijft mijn zakgeld? (ii) ledenadministratie van een vereniging;

* richtlijnen voor data in tabellen:

  * record per rij, kolommen met vaste betekenis (type)
  * samenvatten op apart vel(len): je kunt dan gemakkelijker de data uitbreiden,
    en het werkt handiger als je veel rijen hebt (je hoeft dan niet steeds naar onder te scrollen).
  * je kunt op verschillende elementen sorteren, maar zorg dat je een natuurlijke key hebt om
    weer de "normale" situatie te herstellen.
    (Dit kan een volgnummer zijn, een naam, of een datum, bijv.)


* Enkele voorbeelden en oefeningen
  

Nog toevoegen
-------------

Figuur met belangrijkste onderdelen van een rekenvel-UI.

* vgl. ch.1 Excel Bible.

Gebruik van Enter en Tab bij invoer.

Opdrachten
----------

Maak een tabel met de tafel van 7, waarbij je één formule gebruikt die je in alle cellen kopieert.
Je moet dit eenvoudig kunnen aanpassen tot de tafel van 3: gebruik de waarde 7 niet in de formule.


a. als kolomkop de waarde 7, en als rijlabels de waarden 1..10
b. alleen als kolomkop de waarde 7.

Maak een tabel met alle tafels van 1..10, waarbij je één formule gebruikt die je in alle cellen kopieert.
Gebruik als kolomkoppen de waarden 1..10, en als rijlabels ook de waarden 1..10.

a. gebruik een formule van de vorm: ``X*Y``
b. gebruik een formule van de vorm: ``X+Y``
