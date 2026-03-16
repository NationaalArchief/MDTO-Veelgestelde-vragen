# Inhoudelijke keuzes – koppelvlak

## Waarom is het MDTO-koppelvlak gesplitst in twee documenten, één voor de SIP specificatie en één voor het proces van aanlevering?
Vanuit het werkveld bleek behoefte aan meer flexibiliteit en minder vastleggen. Vooral voor het aanleverproces was dit een grote wens. Vandaar dat het koppelvlak is gesplitst.

De status van beide modules is niet gelijk: 

* De SIP specificatie maakt deel uit van de norm. Bij gebruik van MDTO is deze verplicht.
* Het proces van aanlevering is een handreiking die advies geeft. Deze heeft geen verplichtend karakter. 

## Waarom is gekozen voor de sidecar structuur?
Deze keuze is gemaakt omdat de sidecar structuur:

* meer flexibiliteit biedt in vergelijking met één groot XML-bestand voor alle metagegevens. Bijvoorbeeld bij het opsporen van fouten die tijdens een uitwisseling worden geconstateerd.
* beter opschaalt bij de uitwisseling van grote hoeveelheden informatieobjecten.

## Mag ik op een andere manier uitwisselen dan met een sidecar structuur?
De aanleverende en ontvangende partij kunnen afspreken om bij de aanlevering de metagegevens niet in een sidecar structuur uit te wisselen. Dit is dan niet conform MDTO, maar op basis van de onderlinge afspraak. Maar als een van beide partijen conform MDTO wil uitwisselen, moet dit mogelijk zijn.

## Hoe wordt in de SIP de relatie gelegd tussen het informatieobject en het bestand?
Dit is een relatie die specifiek in de metagegevens moet worden meegegeven. Vanuit het Bestand door het attribuut ‘Is representatie van’, vanuit het informatieobject door het attribuut ‘Heeft representatie’.

NB. Er is geen relatie mogelijk tussen bestanden onderling. Er moet altijd een relatie met een informatieobject zijn. Wel kunnen meerdere bestanden een relatie hebben met één informatieobject.

## Waarom staat er bronsysteem, terwijl er vaak een exporttool wordt gebruikt?
Een bronsysteem als definitie kan ook een exporttool omvatten. Het is niet mogelijk om alle verschillende opties afzonderlijk op te sommen. 

## Wat is het verschil tussen een koppelvlak en een uitwisseling via zaak- en documentservices?
MDTO richt zicht op uitwisseling van duurzaam toegankelijke informatie, onafhankelijk  van het soort informatiesysteem. De zaak- en documentservices werken juist goed voor de koppeling tussen zaak- en document management systeem. 

## Waarom is er nog een uitwisselformaat met een SIP?
Een SIP is niet veel meer dan een pakket waarmee het mogelijk is om bestanden als één groep te kunnen versturen. Het heeft als voordeel dat de informatie die je uitwisselt één geheel blijft vormen. Dat is vaak wel wenselijk. Andere uitwisselmogelijkheden zijn meestal gericht op uitwisseling van individuele  bestanden. 

## Is het koppelvlak alleen bedoeld voor de uitwisseling met een e-depot?
Het koppelvlak is bedoeld voor uitwisseling van informatie tussen willekeurige informatiesystemen, via een koppeling. Dus niet alleen voor de uitwisseling met een e-depot. Het is ook bedoeld voor het beschikbaar stellen van informatie uit systemen aan gebruikers (bijvoorbeeld via een website).