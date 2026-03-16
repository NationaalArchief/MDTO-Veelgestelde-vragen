# Ontwikkelproces en -keuzes

## Is bij het maken van MDTO ook feedback en advies gevraagd aan leveranciers van informatiesystemen of alleen van gebruikers?

Leveranciers hebben ook input geleverd. Bij de ontwikkeling van MDTO heeft het Nationaal Archief gebruik gemaakt van redactiegroepen, waarin experts vanuit overheidsorganisaties, archiefinstellingen en ook leveranciers een inhoudelijke bijdrage hebben geleverd. Bij de openbare review in 2019 hebben we ook weer leveranciers opgeroepen om te reageren. De feedback die dit opleverde is zoveel mogelijk verwerkt in MDTO.

## Waarom is MDTO ontwikkeld?

<strong>Opdracht</strong><br>
De Standaardisatieraad van het Nationaal Archief heeft de opdracht voor de ontwikkeling van MDTO en het resultaat van die doorontwikkeling (de huidige versie van MDTO) vastgesteld. 

MDTO is de opvolger van het Toepassingsprofiel Metagegevens Lokale Overheden (TMLO), versie 1.1. De oorspronkelijke versie van TMLO (1.0) is in 2013 vastgesteld door het Convent. Aan dit overleg nemen de Regionale Historische Centra (RHC’s) en het Nationaal Archief deel. Deze versie was grotendeels gebaseerd op het Toepassingsprofiel Metagegevens Rijksoverheid (TMR) uit 2009. 

Na een kleine revisie in opdracht van het programma Archief2020 werd versie 1.1 van TMLO in 2014 vastgesteld. 

Het Nationaal Archief heeft de nog door Archief2020 ingezette verdere doorontwikkeling  in 2017 opgepakt met een volledige revisie. Aan de revisie lag een analyse van het gebruik van zowel TMLO als TMR ten grondslag. MDTO lost de knelpunten die uit deze analyse naar voren kwamen zoveel mogelijk op.

Voor een betere synergie tussen TMLO en TMR en een zo efficiënt mogelijke inzet van beschikbare expertise is in 2019 besloten één norm voor de gehele overheid te maken: Metagegevens Duurzaam Toegankelijke Overheidsinformatie. MDTO is bedoeld om TMLO en TMR te vervangen.

De module Aanleverproces Submission Information Package is gebaseerd op de use case (de in kaart gebrachte systeemeisen) voor het aanleveren van metagegevens en bestanden aan een e-depot (in MDTO ‘doelsysteem’). Dit is niet de enige vastgestelde use case rondom uitwisseling. Op het Kennisplatform Informatie en Archief (KIA) staat een overzicht van de use cases die eerder zijn opgehaald. Deze andere use cases werken we op termijn uit, afhankelijk van de prioriteit die de Standaardisatieraad hieraan geeft.  

<strong>Ontwikkelproces</strong><br>
Het Nationaal Archief heeft de redactie gevoerd over de inhoud van alle modules van MDTO. Sinds 2019 begeleiden redactiegroepen het Nationaal Archief inhoudelijk bij een aantal modules van MDTO. In de redactiegroepen zitten experts van overheidsorganisaties, archiefinstellingen en (software)leveranciers.  Het Nationaal Archief heeft met hen conceptversies gedeeld ter review en inhoudelijke keuzes besproken. 

Ook zijn gedurende het proces twee openbare reviews gehouden: 

* voor TMLO 1.2 (2017)
* voor MDTO 0.2 (2020) <br>
(voor het metagegevensschema, het XML schema en de koppelvlakspecificatie)
De belangrijkste uitkomsten van de tweede openbare review en de inhoudelijke keuzes die hier uit voortvloeiden zijn ook besproken met de redactiegroepen. 

Afstemming is verder gezocht met het Kennis- en exploitatiecentrum Officiële Overheidspublicaties (KOOP, onderdeel van BZK), als beheerder van PLOOI en OWMS, met de Vereniging van Nederlandse Gemeenten (VNG) en met CIO Rijk (BZK) als beheerder van TMR.

Voor de communicatie rondom de doorontwikkeling van MDTO gebruiken we het Kennisnetwerk Informatie en Archief. Hier staan ook eerdere conceptversies van MDTO.


## Wat is het verschil tussen TMLO/TMR en MDTO?
<strong>Toepassingsgebied</strong><br>
MDTO is bedoeld voor toepassing door alle overheidsorganisaties.

<strong>Terminologie</strong><br>
MDTO gebruikt zoveel mogelijk bestaande termen en definities. Een aantal termen is anders ten opzichte van TMLO/TMR. De voornaamste reden hiervoor is om beter aan te sluiten bij terminologie die wordt gebruikt in de architectuur en door ontwerpers van informatiesystemen. MDTO is daarmee beter toepasbaar door archiefvormers. Zo gebruikt MDTO de term ‘klasse’  in plaats van entiteit en ‘informatieobject’ in plaats van record. Veel bestaande definities zijn behouden (al dan niet in aangepaste vorm).

<strong>Specificatie</strong><br>
De structuur van de specificatie van klassen en attributen is verbeterd. Hierdoor is de specificatie overzichtelijker en explicieter. Er zijn verder veel voorbeelden toegevoegd. Deze zijn gescheiden van de definities en de toelichting. Bij de definities, maar ook bij de teksten in MDTO in het algemeen, zijn veel onduidelijkheden of dubbelzinnigheden verwijderd.

<strong>Onderdelen</strong><br>
TMLO en TMR bestaan uit één onderdeel: het metagegevensschema.
Ze voorzien niet in een machineleesbaar schema (XML) en een uitwisselingsprotocol.

In de praktijk hebben archiefinstellingen daar zelf invulling aan gegeven. Dit leidde tot onderlinge verschillen (in wat en hoe er uitgewisseld wordt). MDTO kent meerdere modules, waarvan een deel normerend is en een deel niet. Hiermee is ook de uitwisseling zelf gestandaardiseerd.

Modules van MDTO zijn:
| Normerend                  | Niet-normerend             |
| -------------------------- | -------------------------- |
| Metagegevensschema         | RDF ontologie              |
| XML Schema                 | Aanleverproces SIP         |
| Definitie van MDTO conform | Mapping TMLO/TMR naar MDTO |
| MDTO begrippenlijsten      |                            |
| Specificatie SIP           |                            |

<strong>Nummering attributen</strong><br>
Attributen in MDTO zijn niet voorzien van een nummer, zoals in TMLO/TMR.

MDTO kent ten opzichte van TMLO/TMR nogal wat wijzigingen in de attributen. Hierdoor was de bestaande nummering uit TMLO/TMR niet meer bruikbaar.

Door MDTO als een set van webpagina’s te presenteren, is er wel sprake van onderlinge relaties, maar niet van een bepaalde volgordelijkheid.  Gebruikers kunnen op iedere webpagina terecht komen. Er is een mapping beschikbaar waarin de elementen uit TMLO/TMR worden gemapt naar attributen in MDTO (voor zover mogelijk).

<strong>Verplichtingsniveaus aangepast</strong><br>
TMLO/TMR kennen vijf verplichtingsniveaus (van verplicht tot optioneel). Die niveaus zijn soms moeilijk van elkaar te onderscheiden. Ook is het niet altijd duidelijk wat ‘van toepassing’ zijn in de praktijk inhoudt. In MDTO worden de verplichtingen teruggebracht tot twee: ‘verplicht’ en ‘verplicht indien bekend’. Een uitleg hierover staat in de Definitie van MDTO conform. 


<strong>Geen eigen toepassingsprofiel</strong><br>
Anders dan TMLO/TMR gaat MDTO niet uit van het maken van een eigen toepassingsprofiel (of metagegevensschema) op basis van MDTO. 

Door een metagegevensschema (zoals vermeld in de Archiefregeling) inhoudelijk te beperken tot wat alleen in TMLO/TMR is gespecificeerd, wordt geen recht gedaan aan andere metagegevens die voor andere doeleinden vastgelegd worden. Door de regels die werden gesteld in TMLO en TMR, was het ook omslachtig om extra, organisatiespecifieke gegevens toe te voegen aan een eigen profiel. Met als gevolg dat regelmatig werd geprobeerd om andere metagegevenselementen te mappen naar elementen in TMLO, die daar niet voor bedoeld waren. 

Elke organisatie zal nog steeds een eigen metagegevensschema moeten maken, zoals vermeld in de Archiefregeling. Maar dat hoeft geen profiel van MDTO te zijn. Zolang het eigen metagegevensschema maar wel te vertalen is naar MDTO (ook wel aangeduid als ‘mapping’). Het is daarbij niet noodzakelijk dat een organisatie één metagegevensschema voor de hele organisatie maakt. Dat kunnen er ook meerdere zijn, voor verschillende werkprocessen en informatiesystemen. De schema’s kunnen organisatie- of domeinspecifiek zijn. Voordeel van deze aanpak ten opzichte van TMLO/TMR is dat er recht wordt gedaan aan andere metagegevens die voor andere doeleinden vastgelegd worden. Ook zijn er geen omslachtige regels meer om extra, organisatiespecifieke gegevens toe te voegen aan een eigen profiel.

MDTO faciliteert de uitwisseling van organisatie- en domeinspecifieke metagegevens. In TMLO/TMR was hierin niet voorzien.



<strong>Aggregatieniveaus</strong><br>
MDTO definieert wat een informatieobject is, maar niet wat een organisatie als een informatieobject kan of moet beschouwen. Ook onderkent MDTO dat informatieobjecten kunnen worden geaggregeerd, dus dat informatieobjecten tezamen ook een informatieobject kunnen vormen. Zoals een zaak/dossier met daarbinnen documenten over op de zaak of het dossier.

In tegenstelling tot TMLO/TMR schrijft MDTO geen aggregatieniveaus voor. Maar vermeldt alleen een aantal mogelijke waarden. Archiefvormers kunnen zelf aggregatieniveaus onderscheiden en benoemen, of kunnen gebruik maken van de voorbeelden uit MDTO. Of beide. Dit maakt het eenvoudiger om een eigen ordening te hanteren. 


<strong>Beperking gebruik</strong><br>
TMLO/TMR kennen drie elementen die te maken hebben met beperkingen op het gebruik: Gebruiksrechten, Vertrouwelijkheid en Openbaarheid. In MDTO is hier de gegevensgroep ‘Beperking gebruik’ voor in de plaats gekomen. Hiermee kunnen meerdere typen beperkingen vastgelegd worden die voor informatieobjecten gelden (er kunnen meerdere beperkingen tegelijk van toepassing zijn). Zoals vanuit het Auteursrecht, de AVG, informatiebeveiliging (BIO) of de Archiefwet. In de praktijk zijn er veel verschillende beperkingen mogelijk, specifieke voorwaarden of meerdere betrokkenen die al dan niet toestemming kunnen geven voor gebruik van een informatieobject. Al deze mogelijkheden laten zich niet goed vatten in een schema. 

<strong>Betrokkene</strong><br>
In TMLO/TMR is de mogelijkheid om gegevens over een actor vast te leggen. Dat is in de praktijk een overheidsorganisatie of een vertegenwoordiger daarvan, verantwoordelijk voor de creatie of ontvangst van een informatieobject als onderdeel van zijn of haar taak. In MDTO is daarnaast het attribuut ‘Betrokkene’ toegevoegd. Hiermee kunnen ook gegevens over andere organisaties of personen worden vastgelegd die een relatie hebben met een informatieobject (zoals een aanvrager van een vergunning).

<strong>Bewaartermijn</strong><br>
Het attribuut ‘Bewaartermijn’ vervangt Event plan uit TMLO/TMR. Uit de bewaartermijn van een informatieobject kunnen toekomstige gebeurtenissen worden afgeleid (zoals vernietiging of overbrenging). Het apart vastleggen van die toekomstige gebeurtenissen gebeurt niet in MDTO.

Toekomstige gebeurtenissen zijn over het algemeen organisatie- en/of systeem specifiek. Dat maakt het lastig en weinig zinvol om gegevens hierover gestandaardiseerd uit te wisselen. De ontvangende partij bepaalt in de meeste gevallen zelf  welke toekomstige gebeurtenissen er  zijn. Met uitzondering van de bewaartermijn en de termijnen voor de beperkingen op het gebruikt. Daarom zijn hiervoor specifieke attributen in MDTO toegevoegd.

<strong>Integriteit</strong><br>
In TMLO/TMR is Integriteit een element dat betrekking heeft op de inhoudelijke integriteit (als tegenhanger van de technische integriteit van een bestand). Inhoudelijke integriteit laat zich lastig definiëren (het is meer dan volledigheid). En is in de praktijk eigenlijk altijd te koppelen aan een gebeurtenis (zoals een migratie of conversie). In MDTO wordt een gebeurtenis die betrekking heeft op de inhoud van een informatieobject vastgelegd met de gegevensgroep ‘Event’. Hieraan is nu een attribuut toegevoegd waarmee het resultaat van een event ook kan worden vastgelegd. Zoals het resultaat van controles die onderdeel zijn van een migratie- of conversieproces.

<strong>Vorm van informatieobjecten</strong><br>
In TMLO/TMR worden vormkenmerken vastgelegd met een eigen element. Dit biedt de mogelijkheid om informatie te categoriseren op basis van die kenmerken. Dit is een vorm van classificatie. In MDTO kunnen vormkenmerken vastgelegd worden met het attribuut ‘Classificatie’. 

## Waarom bevat MDTO een RDF-ontologie?
Steeds vaker stellen organisaties (meta)gegevens beschikbaar als linked data. Om deze ontwikkeling ook voor MDTO-metagegevens mogelijk te maken is al rekening gehouden met het uitwisselen van MDTO-metagegevens als Resource Description Framework (RDF). Daarvoor is een vertaling gemaakt van het MDTO-metagegevensschema naar een RDF-ontologie.

Maar omdat RDF nog niet algemeen gangbaar is binnen informatiebeheer, is MDTO niet helemaal in RDF gespecificeerd. Er kan niet van worden uitgegaan dat alle overheidsorganisaties met RDF kunnen werken. MDTO-metagegevens kunnen wel als RDF beschikbaar gesteld worden in aanvulling op de standaard XML-representatie van MDTO. Bij uitwisseling tussen twee partijen mogen MDTO-metagegevens als RDF beschikbaar gesteld worden in plaats van de standaard XML-representatie, als daar bilaterale afspraken over zijn gemaakt tussen de betrokken partijen. 

De RDF-ontologie is nu bedoeld om ervaring op te doen met het gebruik van RDF voor metagegevens. En is daarom nog geen normerend onderdeel van MDTO Als de praktijk uitwijst dat organisaties er mee uit de voeten kunnen, dan kan de RDF-ontologie alsnog een normerend onderdeel worden. 

## Waarom sluit MDTO niet aan bij het Metamodel Informatiemodellering (MIM)?
MDTO bestaat in de kern uit een metagegevensschema en een koppelvlak voor het uitwisselen van metagegevens. Het is geen informatiemodel zoals bedoeld in MIM (voor het onderscheid gebruikt MDTO nu ook de term metagegevensschema in plaats van de term informatiemodel zoals gebruikt in conceptversie 0.2).

Er is geprobeerd om MIM toe te passen in een conceptversie van MDTO. Maar dat gaf meer verwarring dan duidelijkheid, waarschijnlijk omdat de makers en gebruikers van MDTO niet vertrouwd zijn met MIM. Het gebruik van MIM zou dan betekenen dat de gebruikers eerst MIM moeten doorgronden voordat ze aan MDTO toe komen. Daar biedt MIM onvoldoende meerwaarde voor.
