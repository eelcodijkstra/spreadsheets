Data en visualisatie
====================

In deze les (hoofdstuk?) behandelen we het gebruik van spreadsheets
voor het analyseren van gegevens.
Deze gegevens zijn meestal afkomstig van een externe bron.
Als het om weinig gegevens gaat kun je deze met de hand invoeren.
Maar vaak gaat het om zoveel gegevens dat je deze invoer wilt automatiseren.
Dat kan op verschillende manieren:

* gebruik van formulieren (bijv. Google Forms)
* importeren van CSV-bestanden
* (verbinding met een database)

De mogelijkheden om data aan te passen en te analyseren in een spreadsheetprogramma
zijn beperkt.
Voor meer mogelijkheden kun je beter een programmeertaal zoals Python gebruiken.

Importeren van een CSV-bestand
------------------------------

Een dataformaat dat je veel tegenkomt is het CSV-bestand ("comma separated values").
Dit is een tekstbestand waarin elke regel een *record* voorstelt;
de *velden* van het record zijn daarin gescheiden door een komma of een ander scheidingsteken.
De eerste regel van zo'n bestand bevat vaak de namen van de velden (kolommen).

Bij het importeren van zo'n bestand in een rekenvel kun je aangeven of er een eerste regel met kolomlabels is,
welk scheidingsteken gebruikt wordt, en wat de types zijn van de kolommen.


Het formaat dat we voor het analyseren van de gegeven willen gebruiken is "data records met kolomtitels":

* elke regel is een record
* alle records hebben dezelfde structuur (velden);
* de eerste regel bevat de kolomnamen (veldnamen);
* alle waarden in een kolom zijn van hetzelfde type en gebruiken hetzelfde format.

Het analyseren van deze data doen we niet in het rekenvel met de data,
maar in een afzonderlijk rekenvel.
We kunnen dan de data aanpassen en eventueel opniew importeren
zonder onze analyse-formules te overschrijven.

(Dit afzonderlijke rekenvel kun je ook als een dashboard van de data beschouwen.
In een dashboard-rekenvel kun je ook meerdere data-rekenvellen analyseren.)

Soms voegen we aan de kolommen van de ingelezen data nog extra kolommen toe
om te rekenen met de data in deze kolommen.

Tijdreeksen
-----------

In sommige gevallen zijn de data gerelateerd aan tijd,
denk bijvoorbeeld aan de logbestanden van een website.
We willen dan vaak de ontwikkeling van bepaalde parameters als functie van de tijd weten.

* wat is daarvoor nodig?
* in welk opzicht is dit anders dan andere data?



Formulieren en de verwerking daarvan
------------------------------------
