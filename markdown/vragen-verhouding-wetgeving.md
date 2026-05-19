# Verhouding tot wetgeving en andere standaarden

## Wat is de relatie met archiefwetgeving?
[Artikel 19 van de Archiefregeling](https://wetten.overheid.nl/jci1.3:c:BWBR0027041&hoofdstuk=3&paragraaf=1&artikel=19&z=2014-01-01&g=2014-01-01) verplicht een overheidsorganisatie voor hun blijvend te bewaren informatie een metagegevensschema vast te stellen zoals bedoeld in NEN-ISO 23081. Het MDTO-metagegevensschema kan daarvoor als basis dienen, aangevuld met de domein- en/of organisatiespecifieke metagegevens die niet in het MDTO-metagegevensschema opgenomen zijn.

## Is er een verband met de Wet open overheid (Woo)?
De Woo kent een aantal gronden waarop de openbaarheid van informatie beperkt kan worden. Aan de hand van MDTO kunnen gegevens over beperkingen worden vastgelegd en/of uitgewisseld. De Woo kan vanuit het oogpunt van MDTO gezien worden als een (externe) begrippenlijst voor beperkingen aan het gebruik van informatieobjecten.

## Wat is de relatie met NEN-ISO 23081?
MDTO is gebaseerd op de internationale standaard NEN-ISO 23081. Hierin is beschreven wat metagegevens zijn, welke soorten metagegevens er zijn en waarvoor ze gebruikt worden. MDTO voegt daaraan toe de specifieke keuze van metagegevens gebruikt binnen de Nederlandse overheid (het metagegevensschema), plus afspraken voor het uitwisselen van deze metagegevens (de koppelvlakspecificatie). MDTO kan zonder voorafgaande kennis van NEN-ISO 23081 gelezen worden.

Het MDTO-objectenmodel is gebaseerd op het entiteitenmodel van NEN-ISO 23081, met de volgende verschillen (uitgaande van de Nederlandstalige versie NEN-ISO 23081-1):

* Informatieobject in plaats van archiefstuk. 
* Bestand is toegevoegd als apart object.
* Locatie is toegevoegd als contextobject.
* Mandaat wordt niet gebruikt (hangt samen met contextobject Actor, dat geen eigen attributen kent in MDTO).
* Informatie en –archiefbeheer wordt niet gebruikt als apart object (valt als proces onder Activiteit). 

MDTO specificeert in tegenstelling tot NEN-ISO 23081 niet de metagegevens voor activiteiten, actoren en mandaten. Dit was ook geen onderdeel van TMLO en TMR. Metagegevens voor informatieobjecten en bestanden kunnen gespecificeerd worden zonder ook de metagegevens voor de andere objecten te specificeren. De specificatie van deze objecten levert ook een extra hoeveelheid werk op waardoor de ontwikkeling van MDTO langer zou gaan duren. Het is nog niet duidelijk of er een overheidsbrede behoefte is om metagegevens voor de andere objecten te specificeren. Dat moet eerst vastgesteld worden.

## Wat is de relatie met NEN-ISO 15489-1?
NEN-ISO 15489 is de internationale standaard die de algemene concepten en principes van informatiebeheer beschrijft. Het concept metagegevens wordt hier globaal beschreven. De metagegevens die door middel van MDTO worden vastgelegd en uitgewisseld dragen bij aan wat in deze standaard ‘gezaghebbendheid’ van archiefbescheiden wordt genoemd: archiefbescheiden (in MDTO informatieobjecten genoemd) die de kenmerken authenticiteit, betrouwbaarheid, integriteit, en bruikbaarheid bezitten. 

## Wat is de relatie met TOOI?
[TOOI](https://standaarden.overheid.nl/tooi) (Thesauri en Ontologieën voor Overheidsinformatie) is een kennismodel voor officiële overheidsinformatie. MDTO en TOOI zijn complementaire standaarden. MDTO specificeert een syntax, TOOI specificeert semantiek en biedt identificatie van overheidsorganisaties en begrippen. Om die reden hebben het Nationaal Archief en KOOP MDTO en TOOI op 1 maart 2024 gelijktijdig aangemeld voor opname op de “Pas toe of leg uit”-lijst van het Forum Standaardisatie. Bij de aanmelding is de relatie tussen MDTO en TOOI uitgebreid toegelicht in een bijlage 'Relatie MDTO en TOOI v1.0'. 

## Wat is de relatie met DCAT-AP-NL en het NL profiel op ISO 19115?
[DCAT-AP-NL](https://docs.geostandaarden.nl/dcat/def-st-dcat-ap-nl30-20250526/)  is een applicatieprofiel op het Europese applicatieprofiel DCAT-AP van de DCAT standaard, dat ervoor zorgt dat informatie (metadata) over datasets en dataservices (API’s) op een uniforme manier wordt vastgelegd en gedeeld om uitwisseling van die metadata tussen datacatalogi uit verschillende domeinen mogelijk te maken. Het [NL profiel op ISO 19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115/) is een profiel op de internationale standaard ISO 19115, en richt zich op de eenduidige beschrijving van ruimtelijke datasets, uit verschillende domeinen.

## Wat is de relatie met andere metagegevensstandaarden?
MDTO is niet de enige norm voor metagegevens binnen de Nederlandse overheid. Maar wel de enige overheidsbrede norm voor generieke metagegevens voor duurzame toegankelijkheid. Er zijn diverse andere standaarden voor metagegevens, zoals het [Nederlands metadataprofiel op ISO 19115 geografie](https://docs.geostandaarden.nl/md/mdprofiel-iso19115/). Binnen de Gemeentelijke Modelarchitectuur (GEMMA) bestaat bijvoorbeeld al het Referentiemodel Gemeentelijke Basisgegevens Zaken (RGBZ). Deze andere standaarden zijn niet-generiek of dienen een ander doel.

MDTO is nadrukkelijk niet bedoeld als vervanger voor de andere metagegevensstandaarden. Elke standaard heeft zijn eigen toepassingsgebied en doel en is als zodanig onmisbaar naast MDTO. Veel van deze metagegevens dragen ook bij aan de vindbaarheid en interpreteerbaarheid van informatie. Daarom gaat de koppelvlakspecificatie ervan uit dat het bronsysteem bij uitwisseling alle beschikbare metagegevens meelevert, in de vorm zoals voorgeschreven door de betreffende standaard. Dit is wat MDTO aanvullende metagegevens noemt.

## Hoe verhoudt MDTO zich tot Records in Contexts (RiC)?
RiC is een nieuwe standaard die wordt ontwikkeld door de International Council on Archives (ICA). Als beoogd opvolger van onder andere ISAD(G). RiC en NEN-ISO 23081 (waar MDTO op gebaseerd is) bieden beide een raamwerk voor metagegevens die gebruikt worden om informatieobjecten (‘records’ in RiC en in de originele ISO 23081) te beschrijven en te beheren. 

Inhoudelijk zijn er de nodige overeenkomsten. Zo zijn de entiteiten binnen het conceptuele raamwerk van RiC beïnvloed door het entiteitenmodel uit NEN-ISO 23081. Veel attributen in RiC kennen een equivalent in NEN-ISO 23081. 

Het verschil tussen RiC en MDTO zit vooral in het toepassingsgebied. MDTO is in de kern een uitwisselingsstandaard, RiC is een standaard voor het beschrijven van informatieobjecten.

NEN-ISO 23081 richt zich daarbij op alle informatieobjecten, vanaf het moment van ontstaan of ontvangst en voor zolang als zij bewaard worden. MDTO is een nadere uitwerking van NEN-ISO 23081 en richt zich primair op archiefvormers binnen de Nederlandse overheid.

RiC richt zich op informatieobjecten die blijvend te bewaren zijn. De primaire doelgroep van RiC zijn dan ook erfgoedinstellingen.

RiC beoogt wel verdere afstemming met NEN-ISO 23081. 
Metagegevens die door archiefvormers aan de hand van MDTO zijn vastgelegd, kunnen ook met MDTO worden uitgewisseld met erfgoedinstellingen. Die instellingen kunnen RiC gebruiken voor het beheren en beschikbaar stellen van hun collecties. De praktijk moet nog uitwijzen of en hoe de huidige overeenkomsten het uitwisselen van MDTO-metagegevens en het nadien omzetten naar RiC metagegevens ten goede komt.
