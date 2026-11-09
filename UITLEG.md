# Uitleg van mijn portfolio

## HTML

Mijn website heeft twaalf losse HTML-pagina’s. De homepage heet `index.html`. De andere pagina’s staan in `pages`.

Elke pagina heeft dezelfde basis:

- `header`: mijn naam en de tekst Mijn portfolio.
- `nav`: het menu met links naar alle pagina’s.
- `main`: de inhoud van de pagina.
- `footer`: de afsluiting onderaan.

Met `h1` maak ik de hoofdtitel en met `h2` maak ik tussenkoppen. Tekst staat in `p`. Een link maak ik met `a` en een afbeelding met `img`. De afbeelding heeft een `alt`-tekst voor bezoekers die hem niet kunnen zien.

## CSS

De opmaak staat in `css/styles.css`. Alle pagina’s gebruiken dat bestand. Ik gebruik Arial als lettertype, een grijze achtergrond en een wit vlak voor de inhoud. De bovenkant en knoppen zijn blauw.

`max-width: 900px` voorkomt dat de inhoud te breed wordt. Met `margin: 25px auto` staat het inhoudsvlak in het midden. `padding` geeft ruimte binnen een onderdeel.

Het menu gebruikt `display: flex` en `flex-wrap: wrap`. Als er te weinig ruimte is, gaan links verder op de volgende regel. Bij schermen smaller dan 600 pixels maakt een media query de marges en tekst wat kleiner.

## Links

Op de homepage link ik bijvoorbeeld naar `pages/over-mij.html`. Vanuit die pagina link ik met `../index.html` terug. De twee punten betekenen één map omhoog.

## Andere onderdelen

De werkervaring staat in een tabel met kolomkoppen. Opleidingen en ambities staan in lijsten. De FAQ gebruikt `details` en `summary` om antwoorden open te klappen.

Het contactformulier heeft labels en invoervelden. Het is een oefenformulier zonder verzending. Daarom is de verzendknop uitgeschakeld. De resetknop maakt de velden leeg.

Op de downloadpagina staat een link met `download`. Daarmee kan iemand mijn cv als tekstbestand downloaden.

## Zelf veranderen

Teksten pas ik aan in de HTML-pagina’s. Kleuren en afstanden pas ik aan in het CSS-bestand. Als ik een menulink verander, moet ik dit op alle pagina’s doen.
