# Inhoudelijke keuzes - metagegevensschema

## Wat is het verschil tussen informatieobject en bestand?
Een bestand is de representatie van de inhoud van een informatieobject. Het is in die zin een specifieke technische vorm om een informatieobject in vast te leggen. Een informatieobject kan gerepresenteerd worden door meerdere bestanden. Het onderscheid tussen informatieobject en bestand maakt het mogelijk om voor beide objecten aparte attributen te specificeren. De attributen gerelateerd aan een informatieobject beschrijven daarbij de inhoud en de context van het informatieobject. De attributen gerelateerd aan bestanden zijn vooral gericht op het vastleggen van vormkenmerken zoals het bestandsformaat. Zie verder de inleiding van het metagegevensschema voor een beschrijving van het object Bestand. 

## MDTO gebruikt de term ‘informatieobject’, terwijl in de Wet open overheid en de nieuwe Archiefwet voor de term ’document‘ is gekozen. Is dit niet verwarrend?
MDTO heeft een aantal doelgroepen benoemd, waaronder leveranciers en ontwerpers van informatiesystemen. MDTO gebruikt zoveel mogelijk bestaande termen die aansluiten bij de terminologie die gebruikt wordt binnen de doelgroepen. ‘Informatieobject’ wordt vanuit dat oogpunt als voorkeursterm gebruikt. Het is daarnaast een term die binnen de NORA en DUTO gebruikt wordt, waarbij de term ‘document’ als alternatief wordt gezien. 

De term ‘document’ wordt veelal geassocieerd met tekstdocumenten (bijvoorbeeld gerepresenteerd in de vorm van Word-bestanden). Maar zoals het in de nieuwe Archiefwet wordt bedoeld, omvat het meer dan alleen tekstdocumenten (gedocumenteerde informatie in enigerlei vorm).

## Waarom bevat MDTO geen domeinspecifieke metagegevens?
Het doel van MDTO is om als norm te worden toegepast op alle informatiesystemen. Vanuit dat oogpunt specificeert het gegevens die generiek zijn voor de Nederlandse overheid. Dus dat ze voorkomen bij (bijna) alle overheidsorganisaties, werkprocessen en informatiesoorten. 

Als MDTO ook nog gegevens zou bevatten die specifiek voor bepaalde domeinen zijn, wordt het veel te groot om te onderhouden. Het zou de toepassing van MDTO ook niet ten goede komen.

Het Nationaal Archief beschikt ook niet over de expertise om domeinspecifieke metagegevens te specificeren. De kenniscentra binnen de betreffende domeinen (zoals Geonovum) zijn daar beter toe in staat. Het is ook beter om bestaande standaarden te gebruiken die al binnen de domeinen worden gebruikt, in plaats van daar nog weer een andere norm naast te zetten.

## Hoe kunnen organisaties workflowgegevens van zaken vastleggen en uitwisselen met MDTO?
Binnen MDTO kunnen gebeurtenissen die betrekking hebben op een informatieobject worden vastgelegd en uitgewisseld, door middel van het attribuut ‘Event’. Denk hierbij aan een wijziging of een conversie van een document. Maar MDTO biedt geen directe mogelijkheid om met specifieke attributen gebeurtenissen die betrekking hebben op een proces of zaak vast te leggen en uit te wisselen. Zoals gegevens over wie op welk moment een proceshandeling (zoals digitaal paraferen) heeft verricht.

Gelukkig zijn er twee praktische oplossingen om de vastgelegde gegevens toch met MDTO uit te wisselen. Procesgegevens kunnen worden vastgelegd als onderdeel van een domeinspecifiek of organisatiespecifiek model, zoals het Referentiemodel Gemeentelijke Basisgegevens Zaken (‘Status’ in RGBZ). Binnen MDTO is het mogelijk om deze RGBZ-metagegevens, of andere specifieke gegevens, uit te wisselen met het attribuut ‘Aanvullende metagegevens’.

Een andere mogelijkheid is om procesgegevens op te nemen in een afzonderlijk (tekst)bestand en dit bestand als onderdeel van de zaak uit te wisselen. De zaak is dan het informatieobject waar het bestand aan gerelateerd moet worden.

## Waarom kunnen toekomstige events (eventplan) niet meer worden vastgelegd in MDTO?
MDTO is een uitwisselingsstandaard. Omdat het informatiebeleid van organisaties vaak verschilt, zal een organisatie na een uitwisseling moeten bepalen of en welke events in de toekomst gepland kunnen en/of moeten worden. Dit kan wel worden bijgehouden in een informatiesysteem. Maar die gegevens hoeven niet gestandaardiseerd te worden en uitgewisseld te worden.

Bewaartermijnen en beperkingen in het gebruik worden met andere attributen vastgelegd en uitgewisseld.

## Waarom is tijdens de ontwikkeling van MDTO het attribuut Aggregatieniveau toegevoegd, en hoe kan dit attribuut vertaald worden naar de praktijk?
Dit attribuut is toegevoegd na de openbare review van MDTO. Met dit attribuut kunnen aggregaties van informatieobjecten onderscheiden worden. MDTO specificeert niet wat een aggregatie is En schrijft ook niet voor hoe een aggregatieniveau moet heten. Meer traditionele niveaus als dossier of serie worden als voorbeeld genoemd, maar organisaties zijn vrij om aggregatieniveaus te benoemen en deze zelf een naam toe te kennen.

Aggregatieniveaus moeten wel te herleiden zijn naar een begrippenlijst.

## Veel attributen zijn in MDTO zijn niet zonder meer verplicht, zorgt dat niet alsnog voor veel verschillen in de vastlegging van metadata? Het doel is standaardisatie, loop je dat doel zo niet mis?
Alle attributen in MDTO zijn verplicht, een aantal daarvan zijn verplicht indien bekend. De vraag is dus eerder waarom niet meer attributen zonder meer verplicht zijn. Een uitgangspunt van MDTO is dat het vastleggen van metagegevens alleen zin heeft als deze al binnen het werkproces gebruikt worden. Anders is de kans groot dat de gegevens niet vastgelegd worden of van slechte kwaliteit zijn. Het staat organisaties vrij om zelf meer attributen zonder meer verplicht te stellen.

MDTO standaardiseert verder de manier van uitwisselen en niet zozeer de manier van vastleggen. Dat betekent dat er verschillen kunnen optreden in hoe gegevens worden vastgelegd en welke gegevens beschikbaar zijn. Maar de manier waarop metagegevens beschikbaar worden gesteld is wel gestandaardiseerd.

## Waarom zijn niet alle mogelijke waarden in de begrippenlijsten gestandaardiseerd? Hierdoor kan er een ongewenste diversiteit in waarden optreden.
MDTO kent bij een aantal attributen begrippenlijsten, waarbij consensus bestaat over de waarden zelf en het belang van die waarden voor de duurzame toegankelijkheid van informatie. MDTO biedt daarnaast de mogelijkheid om andere waarden uit te wisselen (afkomstig uit bijvoorbeeld een organisatie- of een domeinspecifieke begrippenlijst). Over deze andere waarden bestaat geen consensus over de betekenis of het belang voor de duurzame toegankelijkheid.

Ook betekent het opnemen van meer specifieke waarden dat begrippenlijsten vaak te groot worden om te onderhouden, wat de toepassing van MDTO niet ten goede komt.