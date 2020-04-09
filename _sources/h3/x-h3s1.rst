Data: selecteren en samenvatten
===============================

Data in tabellen
----------------

Je kunt een spreadsheet gebruiken als eenvoudige database.
Je organiseert de data dan als een tabel in een relationele database:

* een rij is een *record*: gegevens die samen iets zeggen over een persoon,
  ding, gebeurtenis, enz.
* de kolommen vormen de afzonderlijk *velden* van de records:
  een kolom heeft een naam, en bevat gegevens van eenzelfde type;
* een rij wordt geïdentificeerd door een sleutel (*key*).

De eerste rij in het rekenvel bevat dan de namen van de kolommen.

Enkele voorbeelden van dergelijke tabellen:

* de transactiegegevens van je bankrekening: elke regel bevat een transactie,
  met een bedrag, een tegenrekening, een omschrijving, een datum, enz.;
* gegevens van de deelnemers aan een cursus: elke regel bevat de naam,
  telefoonnummer, maaltijdvoorkeur, e.d., van een deelnemer;
* de gegevens van een formulier (enquête): een rij per ingevuld formulier.

Je komt dergelijke gegevens ook vaak tegen in de vorm van comma-separated-values
in een CSV-bestand.
Elke regel in zo'n bestand bevat de gegevens van een rij,
waarbij de waarden gescheiden zijn door komma's.
Dit formaat wordt vaak gebruikt voor het uitwisselen van dergelijke gegevens
tussen verschillende databases of spreadsheets.

Importeren/exporteren van CSV-bestanden
---------------------------------------

* een CSV-bestand kan verschillende soorten scheidingstekens hebben,
  het hoeft niet altijd een komma te zijn;
* een CSV-bestand heeft soms -maar niet altijd- een eerste regel met de kolomnamen.

Formulieren
-----------

Met bijvoorbeeld Google Forms of xxx. (Microsoft) kun je eenvoudig een formulier aanmaken;
de ingevulde gegevens verschijnen dan in een spreadsheet.
Deze gegevens kun je dan weer op allerlei manieren zichtbaar maken.

Selecteren
----------

De meeste spreadsheetprogramma's hebben een *autofilter*-mogelijkheid:
je kunt dan per kolom een filtervoorwaarde (selectievoorwaarde) aangeven.
Bovendien kun je aangeven hoe de rijen gesorteerd moeten worden.

Zowel voor het filteren als voor het sorteren kun je meerdere voorwaarden opgeven.
In het geval van filteren maakt de volgorde niet uit,
maar bij sorteren is dat wel het geval.

Voorbeeld: je wilt


Punten van aandacht
-------------------

* zorg ervoor dat een rij een eigen *key* heeft voor de identificatie van die rij.
* deze key gebruik je meestal ook om de rij op een natuurlijke manier te sorteren.
* een key kan in principe uit meerdere kolomwaarden bestaan (bijv. naam en geboortedatum).
