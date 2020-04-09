H3S3
====

(overbodig?)
------------




Als grafiek willen we een puntgrafiek gebruiken:
elk meetpunt geven we met een kruisje in de grafiek weer.

We kunnen ook "error bars" toevoegen om de foutgrenzen aan te geven.
In de meeste gevallen hebben we

Dit doe je als volgt (Google Sheets)

* selecteer de data: de rijen en kolommen met de meetgegevens,
  inclusief de eerste rij met kolomtitels.
* klik op menu-item: "Insert->Chart"
  je krijgt nu een grafiek die je nog aan kunt passen met de "Chart editor".

  * je kunt de data kiezen voor de x-as
  * je kunt de data kiezen voor de y-as (series); dit kunnen meerdere kolommen zijn.

Om de grafiek goed af te kunnen lezen is het belangrijk dat de grafiek een voldoende fijn raster heeft.
Dit kun je instellen met de "gridlines".

* stel eerste de minimale en maximale waarden in voor de x- en y-assen.

  * deze staan meestal op "auto", wat vaak goed genoeg is.
    Omdat je de hele data kent kun je deze eenvoudig zelf instellen,
    onder "horizontal axis" en "vertical axis".

* stel vervolgens de "gridlines" in. Deze zijn verdeeld in de major en minor gridlines.

  * hoeveel major gridlines in de totale grafiek? - in ons geval, 5
  * hoeveel minor gridlines tussen twee major gridlines? - in ons geval, 4

* vaak is het plezierig als de hokjes ongeveer vierkant zijn.
  Dat kun je aanpassen door de hele figuur smaller of breder te maken.

(Een alternatief is om de gemeten waarden bij de punten zelf weer te geven.)

Rechte lijn door de meetpunten
------------------------------

Een volgende stap is dat we een rechte lijn willen trekken die zo goed mogelijk aansluit bij de meetpunten.
"Zo goed mogelijk aansluiten" betekent dat we de lijn willen hebben met de kleinst mogelijke totale afwijking van de punten.
Dit wordt wel aangeduid als de "kleinste kwadraten" benadering:

In de meeste spreadsheetprogramma's is hiervoor een functie aanwezig,
zowel voor het tekenen van de lijn als voor het uitrekenen van de parameters van deze lijn.

In Google Sheets heet zo'n lijn een "trendline".
Als onderdeel van de "Series" kun je opgeven of je deze getekend wilt hebben.

Naast rechte lijnen zijn er nog andere benaderende functies mogelijk.


Een lineaire functie (rechte lijn) kun je beschrijven met 2 parameters :math:`a` en :math:`b`:
:math:`f(x) = a \cdot x + b`. De parameter :math:`b` heet ook wel de *intercept*:
het snijpunt met de y-as (de lijn :math:`x=0`).
De parameter :math:`a` geeft de helling ofwel de *slope* van de lijn aan.

In Google sheets heb je functies voor het uitrekenen van de *slope* en de intercept*,
zie de voorbeeld-spreadsheet.
