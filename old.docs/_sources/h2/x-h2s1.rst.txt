H2S1
====

Functies en grafieken
---------------------

Spreadsheetprogramma's hebben vaak veel mogelijkheden om gegevens grafisch weer te geven.
Hierdoor kun je gemakkelijker inzicht in het gedrag van deze gegevens krijgen.

We gaan in dit gedeelte vooral in op het tekenen van (lijn)grafieken van functies en meetgegevens.
Later zullen we andere voorbeelden van grafische vormen zien, zoals histogrammen en taartdiagrammen.

Groei van functies
------------------

Met het volgende voorbeeld kun je experimenteren met de groei van functies.
Hoe gedraagt een functie zich voor steeds grotere waarden?

Deze kennen is onder meer relevant voor het gedrag van algoritmen:
hoe gedraagt een algoritme zich als we het probleem groter maken,
bijvoorbeeld als we in plaats van 100 elementen, 200 of 1000 elementen moeten sorteren?

We beginnen met de vergelijking tussen de functies :math:`f(x)=a*x` en :math:`g(x)=b*x^2`.

* voor de constanten :math:`a` en :math:`b` gebruiken we *benoemde cellen*,
  we hoeven dan niet met absolute verwijzingen als :code:`$H$3` te werken.
* voor de waarden van :math:`x` gebruiken we een formule: :code:`=A1+step`, enz.;
  hierin is `step` een benoemde cel.
  Door het gebruik van deze formule kunnen we eenvoudig het bereik aanpassen.

Dit voorbeeld is typisch voor het gebruik van spreadsheets:
je kunt experimenteren met berekeningen door de parameters aan te passen,
en na te gaan hoe de resultaten van de berekeningen dan veranderen.

Opdracht:

* voeg een derde functie toe: :math:`h(x)=d*x*log(x)`.
* vergelijk het gedrag van :math:`g(x)` en :math:`h(x)`, voor grote waarden van :math:`x`.
* als beide functies het gedrag (de rekentijd) van verschillende sorteeralgoritmes weergeven,
  welk algoritme geef je dan de voorkeur?
  Spelen de waarden van de constanten :math:`b` en :math:`d` daarbij nog een belangrijke rol?


Opmerkingen:

* het maakt niet uit welke basis je gebruikt voor de logaritme,
  bijvoorbeeld de natuurlijke logaritme, de 10-log, of de 2-log.
  Immers: :math:`^{2}log(x) = ^{2}log(10)*^{10}log(x)`.
  Met andere woorden: we kunnen het verschil in de basis van de logaritme verwerken in de constante :math:`d`.
