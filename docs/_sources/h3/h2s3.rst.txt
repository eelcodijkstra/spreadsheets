Weerstandsmeting(?)
===================

In deze les leer je een grafiek te tekenen van meetgegevens,
bijvoorbeeld van een natuurkunde-experiment.
Als voorbeeld gebruiken we de gegevens van de spannings- en stroommetingen aan twee weerstanden.

De stappen hierbij zijn:

1. invoeren van de gegevens in een tabel
2. eventueel toevoegen van berekeningen aan de tabel
3. maken van de grafiek
4. toevoegen van een trendlijn

Invoeren van de  meetgegevens
-----------------------------

Voor de meetgegevens gebruik je een tabel met kolomtitels en rij-gegevens.
Elke rij bevat:

* in de eerste kolom, de waarden die je voor de x-as (horizontale as) wilt gebruiken.
* in de volgende kolom(men), de waarden die je voor de y-as (verticale as) wilt gebruiken.


In ons voorbeeld gebruiken we de ingestelde spanning in de eerste kolom voor de x-as,
en de gemeten stromen voor beide weerstanden in afzonderlijke kolommen voor de y-as.

Vraag: hoe gaan de tekenfuncties om met ontbrekende waarden,
bijvoorbeeld als je voor een bepaald punt alleen voor weerstand R1 gemeten hebt?

Toevoegen van berekeningen aan de tabel
---------------------------------------

Soms is het handig om uit de gemeten waarden een afgeleide waarde te berekenen,
die bijvoorbeeld gemakkelijker grafisch weer te geven is.
Deze berekeningen kun je als aparte kolom(men) toevoegen.

In ons voorbeeld is het niet nodig om aan de gemeten waarden te rekenen.

Maken van de grafiek
--------------------

In de onderstaande figuur zie je de verschillende elementen van een grafiek (in Excel):

.. figure:: excel-grafiek-elementen.gif
  :width: 600px
  :align: center

Uitleg hierbij:

1. Grafiek-titel (Chart title)
2. Plotgedeelte (Plot area)
3. Legenda (Legend)
4. As-titels (Axis titles)
5. As-labels
6. Tick marks
7. Rasterlijnen (Gridlines)

Soort grafiek
^^^^^^^^^^^^^
Als eerste stap selecteer je de data, inclusief de kolomttitels,
en maak je de grafiek aan.
Hierbij kies je als type voor de grafiek: "scatter chart" (puntenwolk).

Hierbij wordt de eerste kolom gebruikt voor de x-as (horizontaal),
en de volgende kolommen voor de y-as (verticaal).
Dit kun je eventueel later nog veranderen:

* de reeks waarden (kolom) voor de x-as heet "X-axis"; dit is altijd maar 1 kolom.
* de reeks(en) waarden voor de y-as heet "Series". Dit kunnen er meerdere zijn.

Belangrijke instellingen hierbij zijn:

* "use row 1 as headers" - de kolomkoppen worden gebruikt in de titel(s) en in de legenda;
* "use column A as labels" - de waarden in kolom A worden gebruikt als labels bij de x-as.

Titels
^^^^^^
De titels voor de grafiek en voor de assen worden in eerste instantie gemaakt uit de kolomkoppen.
Je kunt deze eventueel aanpassen, door in de grafiek op een titel te klikken,
of door deze in de grafiekinstellingen te veranderen.

Plotgedeelte
^^^^^^^^^^^^

Je kunt kiezen op welke manier de punten in de grafiek weergegeven worden.
Dit is onderdeel van de instellingen voor de datareeksen ("Series").
Je kunt de vorm, grootte en kleur instellen.

Kies hier een kruisje (x) voor de meetpunten.
Dit maakt het aflezen van de waarden in de grafiek eenvoudiger.

Assen en rasterlijnen
^^^^^^^^^^^^^^^^^^^^^

Voor de assen kun je verschillende zaken instellen, onder andere:

* de minimum- en maximumwaarden

Om de gemeten waarden ook uit de grafiek af te kunnen lezen,
werken we met een fijnmazig rasten ("millimeterpapier").

Bij de "gridlines" instellingen kun je het aantal lijnen instellen:

* voor de "major gridlines", het totale aantal lijnen langs de as;
* voor de "minor gridline", het aantal lijnen tussen twee "major gridlines".

Dit kun je voor de x-as en voor de y-as afzonderlijk doen.
