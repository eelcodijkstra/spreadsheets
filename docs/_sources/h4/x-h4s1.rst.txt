Samenvatting
============

Dit hoofdstuk is bedoeld als naslagwerk om snel bepaalde begripppen te kunnen vinden.
Je kunt dit ook gebruiken om na te gaan welke onderdelen je wel en niet kent.

* een rekenvel (spreadsheet) bestaat uit cellen georganiseerd in (horizontale) rijen en (verticale) kolommen.
* de rijen zijn genummerd vanaf 1; de kolommen zijn geletterd: A, B, ... Z, AA, AB, ...
* een cel bevat (ten hoogste) één waarde: een getal, een tekst, een logische waarde, of een formule.
* een waarde kan op verschillende manieren opgemaakt (geformatteerd) zijn;
  je kunt een getal bijvoorbeeld weergeven als geheel getal, valuta, of datum.
* voor drijvende-kommagetallen kun je een komma of een punt gebruiken;
  dit moet je instellen op het niveau van de toepassing of van het operating system.
* een formule bestaat uit constanten (waarden), verwijzingen naar cellen,
  operatoren en functies.
* een verwijzing naar een cel ("adres") kan *absoluut* zijn of *relatief*.
  Een absolute verwijzing verandert niet als je deze naar een andere cel verplaatst of kopieert.
  Bij een relatieve verwijzing blijft de afstand tot de cel waarnaar verwezen wordt gelijk.
* een absolute verwijzing kan ook door middel van een naam: je geeft de cel een naam,
  en kunt dan in de formules deze naam gebruiken.

.. glossary::

  rekenvel (spreadsheet)
    Een rekenvel bestaat uit *cellen* georganiseerd in horizontale *rijen* en verticale *kolommen*.
    De rijen zijn genummerd vanaf 1; de kolommen zijn geletterd: A, B, ..., Z, AA, AB, ...

  cel
    Een cel van een rekenvel bevat ten hoogste één waarde: een getal, tekst, logische waarde of formule.
    Vanuit een *formule* kun je verwijzen naar een cel of een reeks cellen. (zie celverwijzing)

  waarde
    Een waarde is een getal, een tekst, een logische waarde.

  adres
  celverwijzing (adres)
    Het adres van een cel bestaat uit de kolomletter gevolgd door het rijnummer, bijvoorbeeld ``C3``.
    Deze vorm beschrijft een relatief adres:
    bij het kopiëren van een formule met dit adres blijft de afstand tot de input-cel gelijk.
    Door een ``$`` voor de kolom en/of rij te plaatsen kun je aangeven dat dit een absolute verwijzing is,
    die niet verandert bij het kopiëren van de formule.

    Een reeks (array) cellen geef je aan door de begincel (link boven) en de eindcel (rechts onder),
    gescheiden door een ':', bijvoorbeeld ``A1:D5``.
    Ook hier kun je weer relatieve en absolute verwijzingen gebruiken.

  formule
    Een formule bestaat uit waarden (constanten), verwijzingen naar cellen, operatoren en functies.

  absolute verwijzing
    zie celverwijzing.

  relatieve verwijzing
    zie celverwijzing.
