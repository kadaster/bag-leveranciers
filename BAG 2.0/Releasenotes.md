**Releasenotes 15-02-2019**
--
*Stabiliteit ETO omgeving*

De stabiliteit van de ETO omgeving is verbeterd.

**Releasenotes 18-01-2019**
--
*Conformiteitstoets*

Zes leveranciers hebben de conformiteitstoets succesvol doorlopen.  

*BAG Extract*

We hebben alle bekende problemen met de BAG extracten opgelost. We sturen vandaag nog per e-mail de verbeterde extracten van alle bij ons bekende pilotgemeenten toe. We zijn geen onvolkomenheden in de xsd’s tegengekomen. Er volgt dus geen wijziging van de xsd’s. 

*Inrichting BAG 2.0 database ten behoeve van de pilot*

We hebben de conversie van de BAG 1.0 naar de BAG 2.0 database afgerond. De BAG 2.0 database bevat is een kopie van de BAG productiedatabase van 19 december 2018. We gebruiken deze database om BAG 2.0 extracten te maken. Deze database is ook beschikbaar om mutaties op door te voeren. De autorisatie hiervoor is gelijk aan de autorisatie voor de ETO. Via onderstaande endpoints kunnen jullie mutaties doorvoeren op deze database. 

*BAG Webservice*:

https://service30.kadaster.nl/lvbag/test/bag-kgb/service/kennisgeving/v20171101/KennisgevingService 
https://service30.kadaster.nl/lvbag/test/bag-kgb/service/synchronisatie/v20171101/SynchronisatieService 

*In onderzoek*:

https://service30.kadaster.nl/lvbag/test/bag-kgb/service/inonderzoek/v20171101/InOnderzoekService
 
*Ping-service*

Via onderstaande url is het mogelijk de verbinding met de ETO op basis van een certificaat te controleren. We hebben overigens gemerkt dat de ETO soms instabiel is. We zijn bezig met het oplossen van dit probleem. 
https://service30.kadaster.nl/lvbag/eto/bag-kgb/service/system/heartbeat 

*Mapping BAG 2018 gebeurtenissen naar de BAG berichtencatalogus* 

Ik heb een voorstel met een aangepaste mapping gepost op het discussieforum: 
https://discussie.kinggemeenten.nl/discussie/gemma/koppelvlak-bag/patch-op-stuf-bag-cq-bag-berichtencatalogus-voor-compatibiliteit-met#comment-6042
Op het eerste gezicht lijken de problemen met de mapping opgelost te kunnen worden. We ontvangen graag jullie reacties. 

*Validaties*

Binnenkort zetten we een overzicht met de validaties die tot nu toe zijn geïmplementeerd op Github. 

**Releasenotes 29-11-2018**
--
De conformiteitstoets is af. Het zou mogelijk moeten zijn de volledige toets succesvol te doorlopen. 

**Releasenotes 09-11-2018**
--
Software gereed om alle soorten berichten te verwerken


**Releasenotes 25-10-2018**
--

Synchronisatie pand geïmplementeerd

ADO + NUM geïmplementeerd (samengestelde berichten)

Met uitzondering van scenario’s 4.2, 4.4 en 5.1 kunnen alle scenario’s worden doorlopen

Enkele verbeteringen in de referentieset

In de XSD’s en het voorbeeld Extract is ten onrechte opgevoerd gewijzigd in verblijfsobject ten onrechte opgevoerd en pand ten onrechte opgevoerd.


**Releasenotes 16-10-2018**
--
Het BAG Extract is op de volgende punt aangepast:
Typefout aangepast (winkelfuntie)

Gebruiksdoelen waren samengevoegd. Deze zijn nu correct opgenomen 

Newlines en tabs zijn verwijderd 


**Releasenotes 10-10-2018**
---
Afhandeling foutberichten in lijn gebracht met wsdl's

**Releasenotes 28-09-2018**
---
In onderzoek scenario's 4.1 en 4.2 geïmplementeerd

**Releasenotes 19-9-2018**
---
Nieuwe xsd's opgeleverd (Koppelvlak en BAG extract)

**Releasenotes 14-09-2018**
---
Pand scenario's 4.3 en 4.5 geïmplementeerd

Inactief maken scenario 5.2 geïmplementeerd

Aanpassing scenario 3.5

**Releasenotes 15-08-2018**
---

Nieuwe SOAPberichten toegevoegd

Openbare ruimte scenario's 3.1, 3.2, 3.4 en 5.1 geïmplementeerd

*Inclusief*

Berichtverwerking inclusief validaties

Voorbeeldberichten


*Overige aanpassingen:*

Validatieoverzicht aangepast.

Swagger via basic authentication. Extra endpoint beschikbaar

Referentieset aangepast (Typfout in scenario 1.3) 



**Releasenotes 01-08-2018**
---

Woonplaatsscenario's 3.8 t/m 3.13 geïmplementeerd in de conformiteitstoets. 

*Inclusief*

Berichtverwerking inclusief validaties

Voorbeeldberichten

API (legen database en opvragen resultaten)


*Overige aanpassingen:*

XSD's voorbeeld BAG Extract

Swagger document

Concept BAG historiemodel

Github pagina leveranciers gevuld
