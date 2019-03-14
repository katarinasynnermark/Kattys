## E-bok

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid beskrivning av e-böcker tillgängliga online, med utgångspunkt från exempel. Många av egenskaperna finns redan i mallen E-bok, andra kan behöva läggas till. Använd gärna Berika från mall för att få med de viktigaste egenskaperna. För en del egenskaper hänvisas till andra hjälptexter.

För instruktioner om att lägga till eller ta bort egenskap, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För anvisningar om Adminmetadata, se Adminmetadata.

För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA") samt RDA [Toolkit](http://access.rdatoolkit.org/).

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

### Innehåll  

| [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- |
| [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Bärartyp](#barartyp) | [Språk](#sprak) |
| [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk)|
| [Upphovsuppgift](#upphovsuppgift) | [Genre](#genre) |
| [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| [Utgivning](#utgivning) | [Ämne](#amne) |
| [Copyrightår](#copyrightar) | [Målgrupp](#malgrupp)|
| [Identifikator](#identifikator) | [Innehållstyp](#innehallstyp) |
| [Omfång](#omfang) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) |
| [Seriemedlemskap](#seriemedlemskap) |  |
| [Innehållsanmärkning](#innehallsanmarkning) | | 
| [Anmarkning](#anmarkning)| | 
| [Digital karaktäristika](#digital-karaktaristika) | |
| [Annat bärarformat](#annat-bararformat) | |
| [Elektronisk adress](#elektronisk-adress) | |
| [Målgruppsanmärkning](#malgruppsanmarkning) | |

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Elektronisk). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entiteten:  
  ```Computer, c (= dator)```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entiteten:  
  ```Online resource, cr (= onlineresurs)```</BR>
  
  Om koden "r" (= fjärranslutning) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system, länka till entiteten:</BR>
  ```Onlineresurs, r```</BR>
  Om koden "o" (= onlineutgåva) behövs i 008/23 (= form för manifestationen) för bibliotekets lokala system, länka till entiteten:</br>
  ```Onlineutgåva, o```</BR>
  För att hitta entiteten Onlineutgåva, o, välj Form från listan under Föreslagna typer.
    
#### Titel
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  Återge huvudtiteln som den förekommer i källan, se [RDA 2.2.2.4.2](http://access.rdatoolkit.org/rdachp2_rda2-2904.html).</br>
 ```Exempel: Erik den rödes saga```  
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: Den frusna elden, fileringsvärde: 4```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

För att ange Föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Övrig titelinformation (undertitel)
För anvisningar om hur man anger övrig titelinformation, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 

##### Varianttitel   
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html). För anvinsningar om hur man anger olika typer av varianttitlar se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel.

För en huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](https://libris.kb.se/katalogisering/help/workflow-instance#titel) i hjälptexten Instans: Titel.
    
##### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 

##### Parallelltitel  
För anvisningar om hur man anger parallelltitel, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 

#### Upphovsuppgift
För anvisningar om hur man anger upphovsuppgift, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#upphovsuppgift): Upphovsuppgift.

#### Upplageuppgift
För anvisningar om hur man anger upplageuppgift, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#upplageuppgift): Upplageuppgift.
  
#### Utgivning  
För anvisningar om hur man anger utgivningsuppgifter, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#utgivning): Utgivning.
  
#### Copyrightar
För anvisningar om hur man anger copyrightår, se hjälptexten [Instans](https://github.com/katarinasynnermark/Kattys/blob/master/Hjalptexter/Film.md#copyrightar): Copyrightår.
     
#### Identifikator 
##### ISBN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 ‡a)  
  Ange identifikator.  
  ```Exempel: 9789188107213```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)  
  Ange eventuell bestämning.  

För ogiltiga ISBN, använd Indirekt identifierad av, direkt under Instans. Använd inte Ogiltigt värde under Identifikator/ISBN (identifiedBy/marc:hiddenValue).
  
#### Indirekt identifierad av  
Ange ogiltiga ISBN här och inte under Identifikator/ISBN/Ogiltigt värde. 
* Indirekt identifierad av/ISBN (indirectlyIdentifiedBy/ISBN = 020 ‡z)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 ‡a)  
  Ange identifikator.  
  ```Exempel: 97891881072```
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 ‡q)  
  Ange eventuell bestämning.
  
##### URN, DOI, handle
URN, DOI och handle anges i Identifikator/Identifikator/Värde med standardnummer eller standardkod specificerad i en Typanmärkning. 
* Identifikator/Identifikator/Värde (identifiedBy/Identifier/value = 024 7/- ‡a</BR>
  Skriv in uppgiften under Värde.</BR>
  ```Exempel: urn:nbn:se:su:diva-83163``` 
* Identifikator/Identifikator/Typanmärkning (identifiedBy/Identifier/typeNote = 024 7/- ‡2)</BR>
  För att specificera typ av standardnummer eller standardkod, lägg till Typanmärkning.</BR>
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```urn```
    * ```doi```
    * ```hdl```
 
#### Omfang
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html). Ange även antal underenheter, t.ex. sidor, inom parentes efter antal enheter och typ, se [RDA 3.4.1.7.5](http://access.rdatoolkit.org/rdachp3_rda3-2245.html). 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)   
  Skriv in uppgiften under Benämning.  
  ```Exempel:   1 onlineresurs (239 sidor)```  
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)     
  Skriv in uppgiften.  
  ```Exempel: illustrationer```
    
#### Seriemedlemskap
För anvisningar om hur man anger Seriemedlemskap, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#seriemedlemskap): Seriemedlemskap.

##### Författarserie
För anvisningar om hur man anger författarserie, se hjälptexten [Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#seriemedlemskap): Seriemedlemskap.
   
#### Innehallsanmarkning  
För anvisningar om hur man lägger till innehållsanmärkningar se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#innehallsanmarkning): Innehållsanmärkning.

#### Anmarkning
Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)  
  Skriv in allmänna anmärkningar här.  
  För att lägga till Anmärkning, välj Anmärkning (hasNote). Skriv in uppgiften under Benämning.</BR> 
  
#### Digital karaktaristika
* Digital karaktärisitika/Kodningsformat/Benämning (digitalCharacteristic/EncodingFormat/label = 347 ‡b)</BR>
  Ange kodningsformat här, se [RDA 3.19.3.3](http://access.rdatoolkit.org/rdachp3_rda3-5264.html). 
  Skriv in uppgiften under Benämning.</BR>
  ```Exempel: PDF```

#### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  För att länka till en utgåva i annat format, till exempel en tryckt utgåva, lägg till Annat bärarformat (Lägg till egenskaper, välj Annat bärarformat). Sök upp och länka till instansen. Klicka på plustecknet vid Annat bärarformat (Lägg till instans). I sidorutan under Lägg till entitet/Instans, skriv in id eller annat sökbegrepp. Välj instansen genom att klicka på plustecknet vid instansen eller på instansens titel. Om instansen som länken går till har identifikator (ISBN), skapas i marcexporten 776 #t (Titel) och #z (Identifikator). I webbsök ger detta en länk i högermenyn under rubriken Sök vidare/Andra versioner.   
* Annat bärarformat/Typanmärkning (776 ‡i)  
  Typanmärkning i samband med Annat bärarformat kan för närvarande inte läggas till.  
* Annat bärarformat/Beskriven av/Post/Kontrollnummer (776 ‡w)  
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera den i befintliga beskrivningar.  
  
#### Elektronisk adress
##### Tillhörande media
* Tillhörande media/Mediaobjekt/URI (associatedMedia/Mediaobject/uri = 856 4/0 ‡u)</br>
Använd Tillhörande media för att lägga in en elektronisk adress till den besrivna resursen. Lägg till Mediaobjekt under Tillhörande media. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning (marc:versionOfResource/Electronic/marc:publicNote = 856 4/0 ‡z)
Vid behov, lägg till Offentlig anmärkning. Skriv in anmärkningen.

#### Malgruppsanmarkning  
För anvisningar om hur man gör en målgruppsanmärkning, se hjälptexten [Instan](https://libris.kb.se/katalogisering/help/workflow-instance#malgruppsanmarkning): Målgruppsanmärkning.
   
### Verk   

#### Instans av Verk (instanceOfWork) 
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exemepl på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk.</br>
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk - Lägg till egenskaper under: Text. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Verkets titel
 
Ange den föredragna titeln för verket här, vid behov. Följ anvisningarna under [Konstruera sökingångar för verk och uttryck](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/) i Anvisningar för katalogisering - RDA. Föredragen titel ska anges för översättningar och för verk som har givits ut under olika titlar på samma språk. En föredragen titel ska också anges om olika verk har samma auktoriserade sökingång. 

##### Verkets titel - verk med primär medverkan
Föredragen titel för ett verk med primär medverkan ska anges i Har titel/Titel/Huvudtitel .</BR>
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)</br>
  Ange den föredragna titeln under Huvudtitel.</br>
  ```Exempel: Iliaden```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
* Har titel/Titel/Deltitel (hasTitle/Title/partName = 240 1/0 ‡p)</BR> 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
 * Har titel/Titel/Delbeteckning (hasTitle/Title/partNumber = 240 1/0 ‡n)</BR>
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).</BR> 
  ```Exempel: Bok 1-6 ```
* Språk/Språk/Benämning (language/Language/label = 240 ‡l)</BR>
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.</BR>
Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.</BR>
 ```Exempel: Engelska```
 
##### Verkets titel - verk utan primär medverkan
Föredragen titel för ett verk utan primär medverkan ska anges i Uttryck av/Verk/Har titel/Titel/Huvudtitel.
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
Under Instans av Verk, lägg till egenskapen Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), välj Verk. Det läggs till under Uttryck av. Lägg till Har titel. Välj Titel. Ange den föredragna titeln under Huvudtitel.  
```Exempel: Bibeln```</br>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
*	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
```Exempel: Nya testamentet```
*	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 ‡n)  
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning. Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 130 ‡l.</BR> 
```Exempel: Svenska```

#### Medverkan och funktion  
* Medverkan och funktion</br>
Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket samt funktionskod för respektive agent. Relationer till utgivare (710) anges för närvarande också här.</br>
  För ytterligare instruktioner om hur man anger relationer till agenter, se: [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).</BR>
  Se även: [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/). 
   
##### Primär medverkan
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.
<br/>```Exempel: Lindgren, Astrid, 1907-2002``` 
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/author (= författare)```

##### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Bengtsson, Nils, A., 1924-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/).    
  ```Exempel: relator/trl (= översättare)```  

#### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk här. För en text på svenska, länka till svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  För att ange att texten är på flera språk, ange ytterligare en språkkod.
  
##### Översättning    
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk och välj Anmärkning: Språk. Välj fras från lista. 
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en texten är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på plustecknet vid Instans av verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  

#### Relationer till ingaende verk och andra verk

##### Verk som ingår i det beskrivna verket 
För att ange verk som ingår i det beskrivna verket, motsvarande fält 700 1/2 ‡a, ‡d, ‡t (analytisk sökingingång för verk med primär medverkan) eller 730 0/2 ‡a (analytisk sökingång för verk utan primär medverkan) i marc:  
Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br>
Lägg till eventuell deltitel, delbeteckning och benämning på språk. (Lägg till Språk under Verk, skapa lokal entitet och lägg till Benämning. Skriv in språket)</br>
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion). 

##### Relationer till andra verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 1/- ‡a, ‡d, ‡t (icke-analytisk sökingingång för verk med primär medverkande) eller 730 0/_ ‡a (icke-analytisk sökingång för verk utan primär medverkande) i marc: 
Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel. Välj Titel. Ange föredragen titel i Huvudtitel.</br> 
Lägg till eventuell deltitel, delbeteckning och benämning på språk. (Lägg till Språk under Verk, skapa lokal entitet och lägg till Benämning. Skriv in språket)</br>
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion). 
  
#### Genre  
För anvisningar om hur man anger genre, se hjälptexten [Tryckt monongrafi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#genre): Genre.

#### Klassifikation  
För anvisningar om hur man anger klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.
   
#### Amne
Länka i första hand till entiteter för ämnesord. Följ instruktionerna under:<br>
[Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh)

#### Malgrupp     
För att lägga till målgrupp, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#malgrupp): Målgrupp.
  
#### Innehallstyp
För att lägga till innehållstyp, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#innehallstyp): Innehållstyp.
  
#### Sammanfattning av innehall    
För att lägga till en sammfattning av innehållet, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#sammanfattning-av-innehall): Sammanfattning av innehåll.
 
 #### Anmarkning om akademisk avhandling    
För att lägga till Anmärkning om akademisk avhandling, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#anmarkning-om-akademisk-avhandling): Anmärkning om akademisk avhandling.
    


