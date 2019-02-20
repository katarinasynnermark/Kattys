## Film - videoinspelning
Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid beskrivning av film på DVD eller Blu-ray, med utgångspunkt från exempel. Många av egenskaperna finns redan i mallen Film - videoinspelning, andra kan behöva läggas till. Använd gärna Berika från mall för att få med de viktigaste egenskaperna. För en del egenskaper hänvisas till andra hjälptexter för mer detaljerad information.

För instruktioner om att lägga till eller ta bort egenskap, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För anvisningar om Adminmetadata, se Adminmetadata. 

För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA") samt [RDA Toolkit](https://access.rdatoolkit.org/).

Tänk på att för utgivna rörliga bilder är hela den utgivna resursen godkänd källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. Denna Librispraxis, [KB SP 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.3](http://access.rdatoolkit.org/rdachp2_rda2-2892.html).

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).  


### Innehåll  

| [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- |
| [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Bärartyp](#barartyp) | [Språk](#sprak) |
| [Titel](#titel) | [Genre](#genre) |
| [Upphovsuppgift](#upphovsuppgift) | [Klassifikation](#klassifikation) |
| [Upplageuppgift](#upplageuppgift) | [Ämne](#amne) |
| [Utgivning](#utgivning) | [Målgrupp](#malgrupp) |
| [Copyrightår](#copyrightar) | [Bild- och filmtexter](#bild--och-filmtexter) |
| [Identifikator](#identifikator) | [Innehållstyp](#innehallstyp) |
| [Omfång](#omfang) | [Anmärkningar](#anmarkningar) |
| [Övriga fysiska deltajer](#ovriga-fysiska-detaljer) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| [Bilagor](#bilagor) | |
| [Videokarakteristika](#videokarakteristika) | |
| [Seriemedlemskap](#seriemedlemskap) | |
| [Målgruppsanmärkning](#malgruppsanmarkning) | |
| [Innehållsanmärkning](#innehallsanmarkning) | |
| [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter) | |
| [Anmärkning](#anmarkning) | |
| [Relaterad beskrivning eller innehåll](#relaterad-beskrivning-eller-innehall) | |

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Videoinspelning). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```

#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entiteten:  
  ```Exempel: video, v```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entiteten:  
  ```Exempel: videodisc, vd```  
  
#### Titel  
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA. 

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html). 
  <br/>Om titeln förekommer i källan på mer än ett språk eller i mer än en skriftart, se [RDA 2.3.2.4](http://access.rdatoolkit.org/rdachp2_rda2-3375.html) samt [Librispraxis för RDA 2.3.2.4](http://access.rdatoolkit.org/kbspchp2_kbsp2-84.html).  
 ```Exempel: The beguiled```  
    För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: The Beguiledh, fileringsvärde: 4```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon,          mellanslag. 
  <br/>```Exempel: mer om modelljärnvägar : allt samlaren behöver veta```
  
För att ange föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Varianttitel
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html).
<br/>För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
  * Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 ‡a)<br/> 
 Skriv in uppgiften under Huvudtitel.    
  ```Exempel: Cool girls```<br/>

För en huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#parallelltitel).<br/>

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som varianttitel. Notera dock att för utgivna rörliga bilder är hela resursen godkänd källa, utan prioritetsordning, se [KB SP 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.<br/>

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning. 
  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)<br/> 
   ```Exempel: Titeln felstavad, korrekt titel:```   
   
##### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 ‡n)  
Lägg till Har del (hasPart) under Har titel/Titel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Har del).  
Under Har del, skapa Titeldel (TitlePart) som lokal entitet (skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel). Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.</BR>
Om Har del/Titeldel/Deltitel redan finns, lägg till Delbeteckning under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Delbeteckning (partNumber)).   
Skriv in uppgiften under Delbeteckning.  
```Exempel: 1```   

##### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 ‡p)  
Lägg till Har del (hasPart) under Har titel/Titel. Under Har del, skapa Titeldel (TitlePart) som lokal entitet (skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel). Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.</BR>
Om Har del/Titeldel/Delbeteckning redan finns, lägg till Deltitel under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Deltitel (partName)).   
Skriv in uppgiften under Deltitel.  
```Exempel: Stark rygg & god hållning```  

För att ange Delbeteckning och Deltitel i en annan ordning, till exempel en deltitel som har efterföljande delbeteckningar, upprepa Titeldel och ange Delbeteckning och Deltitel som det passar i det aktuella fallet.  

##### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel   
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Ange alternativa titlar här för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord.  

 För att lägga till en alternativ sökingång för titeln, lägg till Relation. Lägg till Entitet. Skapa verk som lokal entitet. Klicka i rutan Skapa lokal entitet, längst ner i sidorutan till höger, och välj Verk. Lägg till Har titel (plustecknet vid Verk - lägg till egenskaper under: Verk). Skriv in uppgiften under Huvudtitel.

  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde under Titel och ange en siffra.
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/).
  
##### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 ‡a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 ‡a)   
Välj först Har titel, välj sedan typ Parallelltitel.      
Skriv in uppgiften under Huvudtitel.     
  ```Exempel: Räddarna```</br>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.

* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 ‡b)   
Vid behov, lägg till Övrig titelinformation (subtitle) under Parallelltitel.  
  ```Exempel: berättelser om mod```  
  
#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)</BR>
  ```Exempel:```
  
  * ```written, produced and directed by Hilary Ng'weno```
  * ```av Astrid Lindgren ; producent: Waldemar Bergendahl ; regi: Lasse Hallström```
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)</BR>
  Skriv in upplagebeteckning här. 
 <br/>```Exempel: Limited edition```  
  
#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.  
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.      
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c) finnas med.
 
##### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
Sök inte efter Plats som entitet. Skapa plats som lokal entitet.   
  Skriv in uppgiften under Benämning. Klamra vid behov.</br> 
  ```Exempel: [Stockholm]```  
  
##### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
  
##### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
Sök inte efter Agent som entitet. Skapa agent som lokal entitet.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: Njutafilms```   
 Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.
Ange Plats/Plats/Benämning och Agent/Agent/Benämning inom respektive utgivningsavsnitt. Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning. Land, År och eventuellt Datum ska ligga inom Primär utgivning.</br>
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
##### Ar och datum 
* År (= Utgivningstid) (date = 008/07-10, 264 -/1 ‡c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Ange utgivningsår, utan klamrar eller andra tecken, endast fyra positioner. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum. 
  Observera att År måste finnas med i beskrivningen, även om datum finns med.</br>
  ```Exempel: 2017```  
* Datum (= Utgivningstid) (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange ett utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 ‡c. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, använd endast År.  
  Skriv in uppgiften.
 <br/>```Exempel:```
 
    * ```[2017]```
    * ```[mellan 2003 och 2007?]```
  
  För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, följ exempel i hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion): Produktion. Lägg in egenskaper under Utgivning/Utgivning och Huvudsakligt tillgängliggörande/Primär utgivning). Ange Land, År, Kompletterande datum och Typ av utgivningsdatum under Huvudsakligt tillgängliggörande.
    
* Flera år (flerbandsverk)  
  För anvisningar om hur man anger flera år (flerbandsverk), se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#utgivning): Utgivning. 

Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
  
#### Copyrightar
För film anges alltid copyrightår, även om det sammanfaller med utgivningsår/distributionsår, se [Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html).
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  Skriv in uppgiften. För att få fram ©, kopiera härifrån eller sök på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  Se också [Specialtecken](https://libris-dev.kb.se/katalogisering/help/search-04-special-chars). 
<br/>```Exempel: ©2017```
       
#### Produktionsland
Produktionsland anges tills vidare i [Anmärkning](#anmarkning).
    
#### Identifikator
Flera typer av identifikatorer kan finnas på film. I mallen för Utgivningsnummer (videoinspelning) och EAN förvalda.

##### Utgivningsnummer (videoinspelning)
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: Utgivningsnummer (videoinspelning)```
* Identifikator/Utgivningsnummer (videoinspelning)/Värde (identifiedBy/VideoRecordingNumber/value = 028 ‡a)<br/>
  Ange utgivningsnumret som det förekommer i resursen.<br/>
  ```Exempel: NF780```
* Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 ‡b)<br/> 
  Ange utgivarens namn.<br/>
  ```Exempel: Njutafilms```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)<br/>
  Ange eventuell bestämning.<br/>
  
##### EAN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: EAN```
* Identifikator/EAN/Värde (identifiedBy/EAN/value = 024 ‡a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 5705535059701```

För anvisningar om hur man anger ISBN, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#identifikator): Identifikator
   
#### Omfang  
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). Ange speltid (inom parentes) efter omfång när uppgiften är lätt åtkomlig.
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)<br/>
Skriv in uppgiften under Benämning.
 <br/>```Exempel:```</br>
 
     * ```1 DVD-video (2 tim., 7 min.)```</br>
     * ```1 Blu-ray Disc (1 tim., 40 min.)```
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)  
  ```Exempel: stum, svartvit```
  
#### Bilagor
* Tillsammans med/Instans/Benämning (accompaniedBy/Instance/label = 300 ‡e)   
Lägg till Tillsammans med. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans.)</br> 
Lägg till Benämning. Skriv in uppgiften.
<br/>```Exempel: 1 häfte (10 sidor)``` 

#### Videokarakteristika
* Videokarakteristika (videoCharacteristics = 007/04)
  <BR/>Länka till entitet. 
  Här anges format, antingen DVD eller Blu-ray Disc. 

#### Seriemedlemskap
För anvisningar om hur man anger Seriemedlemskap, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#seriemedlemskap): Seriemedlemskap. 

#### Malgruppsanmarkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 ‡a)  
Lägg till Målgrupp. Skapa Målgrupp som lokal entitet (skriv målgrupp i rutan Skapa lokal entitet och välj det). Skriv in uppgiften under Benämning.<BR/> 
```Exempel: Barntillåten```  
Observera att kodning av målgrupp, motsvarande 008/22, ska anges i [Målgrupp](#malgrupp) under Instans av Verk. 

#### Innehallsanmarkning  
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  För en enkel innehållsanmärkning (505 ‡a), lägg till Har innehållsförteckning. Läggg därefter till Innehållsförteckning. Skriv in uppgiften under Benämning.     
  ```Exempel: Adjö Puh! -- Var är Nasse? -- Fiskar på land -- Himlen trillar ner! -- Nasses ballongspel```  
  
* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning/Upphovsuppgift (tableofContents = 505 8/0 t‡, ‡r)  
För en utökad innehållsanmärkning med titlar och upphovsuppgifter, lägg till Har innehållsförteckning (från Lägg till egenskaper under: Videoinspelning). Klicka på plustecknet under Har innehållsförteckning i vänstermenyn (Lägg till innehållsförteckning). Ta bort Benämning. Lägg till Har del (plustecknet vid Innehållsförteckning - Lägg till egenskaper under: Innehållsförteckning). Skriv Har del i sökrutan och välj det. Klicka på plustecknet vid Har del (Lägg till resurs) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv Utökad innehållsanmärkning i rutan för Skapa lokal entitet och välj * Utökad innehållsanmärkning. Utökad innehållsanmärkning läggs till under Har del. Klicka på Utökad innehållsanmärkning och det fälls ut. Lägg in titel under Benämning. Lägg in upphovsuppgift under Upphovsuppgift.  
Upprepa, för ytterligare titel (Benämning) + upphovsuppgift, genom att lägga till ytterligare en Utökad innehållsanmärkning som lokal entitet (klicka på Duplicera entitet).
  
#### Systemkrav och mediespecifika uppgifter
Här kan systemkrav och mediespecifika uppgifter som inte framgår någon annanstans i beskrivningen anges. Ange uppgiften som den är presenterad i resursen.
* Har anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkningstext        (marc:hasSystemDetailsNote = 538 #a)
  </BR>```Exempel: Systemkrav: Region 2 ; bildformat: 16:9 (2.35:1 ); ljudformat: Dolby digital 5.1```
  
#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)   
  Skriv in allmänna anmärkningar här. Här anges tills vidare Produktionsland. 
  </BR>För att lägga till Anmärkning, välj Anmärkning (hasNote). Skriv in uppgiften under Benämning.  
   ```Exempel: Produktionsland: Frankrike```  

#### Relaterad beskrivning eller innehall
* Relaterad beskrivning eller innehåll/Dokument/URI (isPrimaryTopicOf/Dokument/uri = 856 4/2 ‡u)</BR>
  Länka till delar, sammanfattningar, innehållsförteckningar eller andra resurser som på något sätt hör samman med den resurs som beskrivs.</BR>
  Lägg till Relaterad beskrivning eller innehåll. Skapa Dokument som lokal entitet. Lägg till egenskapen URI. Klistra in aktuell. 
  
### Verk
#### Instans av verk (instanceOf/Work)
Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal   entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka     entitet) vid Instans av Verk.  
  Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).</BR> 

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen Projicerad bild - Lägg till egenskaper under: Projicerad bild. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

#### Verkets titel 
Ange vid behov den föredragna titeln för verket här. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA"). 

##### Verkets titel - verk utan Primär medverkan
Film har sällan en primär medverkande och verkets föredragna titel ska då anges i Uttryck av/Verk/Har titel/Titel/Huvudtitel. 
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
Under Instans av Verk, lägg till egenskapen Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), välj Verk. Det läggs till under Uttryck av. Lägg till Har titel. Välj Titel. 
Skriv in uppgiften under Huvudtitel.  
```Exempel: Gomorra (tv-serie)```    
Tillägget inom parentes (tv-serie) görs för att skilja tv-serien Gomorra från filmen Gomorra. Läs mer om [Tillägg till auktoriserade sökingångar för verk](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/#tillaggtillauktsokingforverk) i Anvisningar för katalogisering (RDA).</BR>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: The truth matters, fileringsvärde: 4```
*	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
*	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 ‡n)  
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
*	Uttryck av/Verk/Språk/Språk/Benämning (expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning. Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 130 ‡l.</BR> 

För en resurs som innehåller endast en dubbning men inte originalversionen ska dubbningens språk anges här. Om resursen innehåller originalversionen och en eller flera dubbade versioner kan, om så önskas, dessa istället anges enligt instruktionerna under [Verk som ingår i det beskrivna verket](#Verk-som-ingar-i-det-beskrivna-verket).

##### Verkets titel - verk med primär medverkande
Det är ovanligt att film har primär medverkande. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av filmen.
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)</BR>
Ange den föredragna titeln.
* Har titel/Titel/Deltitel (hasTitle/Title/partName = 240 1/0 ‡p)</BR> 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
* Har titel/Titel/Delbeteckning (hasTitle/Title/partNumber = 240 1/0 ‡n)</BR>
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).</BR> 
* Språk/Språk/Benämning (language/Language/label = 240 ‡l)</BR>
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.
Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.

För en resurs som innehåller endast en dubbning men inte originalversionen ska dubbningens språk anges här. Om resursen innehåller originalversionen och en eller flera dubbade versioner kan, om så önskas, dessa istället anges enligt instruktionerna under [Verk som ingår i det beskrivna verket](#Verk-som-ingar-i-det-beskrivna-verket).

#### Medverkan och funktion  
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Relationer till Agent i verksbeskrivningen](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)</BR>

##### Primär medverkan
Det är ovanligt att film har primär medverkande. För att en agent ska ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av filmen. 
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
 ```Exempel: Moore, Andy, 1956-```
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/fmk (= filmskapare)```

##### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Wechselman, Maj, 1942-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: relator/drt (= regissör)```    

#### Sprak 
* Språk (language = 008/35-37)</BR>
  Ange det talade eller sjungna språket här.</BR>
  För film som saknar ljudinnehåll (eller med ljud, men utan språkligt innehåll) ange "icke-språkligt medium".</BR>
  För en film som är dubbad ange dubbningens språk här. Om resursen innehåller både originalversionen och en eller flera dubbade versioner, ange originalversionens språk först och sedan språk/språken för dubbningen/dubbningarna.</BR>
  Länka till entitet.  
  ```Exempel: engelska (eng)``` 
  </BR>Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram rätt entitet för språket.</BR>
  Länka till entitet. Språk/språken för dubbningarna hamnar då i separata 041 #a.

Om resursen innehåller originalversionen och en eller flera dubbade versioner kan, om så önskas, dessa istället anges enligt instruktionerna under [Verk som ingår i det beskrivna verket](Verk-som-ingar-i-det-beskrivna-verket). I så fall ska endast originalversionens språk anges här.

För språk i bild- och filmtexter, samt i textskyltar i stumfilm, se egenskapen [Bild- och filmtexter](#bild-och-filmtexter).
 
##### Översättning  
För en film som är dubbad, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Projicerad bild och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Filmens originalspråk anges här. För en engelsk film som är dubbad till svenska, ange engelska här.   
  Klicka på Lägg till egenskaper under: Projicerad bild, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```</br> 
Om resursen innehåller originalversionen och en eller flera dubbade versioner kan, om så önskas, dessa anges enligt instruktionerna under [Verk som ingår i det beskrivna verket](Verk-som-ingar-i-det-beskrivna-verket). 

#### Relationer till ingående verk och andra verk
##### Verk som ingår i det beskrivna verket
Om resursen innehåller originalversionen och en eller flera dubbade versioner kan, om så önskas, dessa anges som verk som ingår i det beskrivna verket.
För att ange verk som ingår i det beskrivna verket, motsvarande fält 700 0/2 ‡a ‡d + ‡t (analytisk sökingingång för verk med primär medverkande) eller 730 0/2 ‡a (analytisk sökingång för verk utan primär medverkande) i marc:  
Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br>
Lägg till eventuell deltitel, delbeteckning och benämning på språk (lägg till Språk under Verk, skapa lokal entitet och lägg till Benämning. Skriv in språket). I varje Har del ska även Språk, Anmärkning: Språk samt originalversionens språk anges enligt instruktionerna under Språk och Översättning, ovan.</br>
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion): Primär medverkan.
För utförligare instruktioner, se även hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

##### Relationer till andra verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 0/_ ‡a ‡d + ‡t (icke-analytisk sökingingång för verk med primär medverkande) eller 730 0/_ ‡a (icke-analytisk sökingång för verk utan primär medverkande) i marc: 
Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br> 
Lägg till eventuell deltitel, delbeteckning och benämning på språk (lägg till Språk under Verk, skapa lokal entitet och lägg till Benämning. Skriv in språket).</br>
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion): Primär medverkan. 
För utförligare instruktioner, se även hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
  
#### Genre  
Länka till entiteter.</BR>
För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet, välj typ. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan.

Under Genre/form, ange dels saogf-termer (genre/form-termer enligt Svenska ämnesord), dels termer som motsvarar marc-koder i 008.
För att länka till saogf-termer, välj Genre/form i listan (det första alternativet under Alla).
För att länka till termer som motsvarar marc-koder i 008, se övriga rubriker. 

##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe.</BR> 
 Välj kod från rätt lista. Mer [information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  
```Exempel:```

   * ```Spelfilmer```
   * ```Dokumentärfilmer```</BR>

Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  
  
#### Klassifikation
För anvisningar om hur man anger Klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.
 
#### Amne  
* Ämne  
  Länka  i första hand till entiteter för ämnesord. Följ instruktionerna på följande sidor:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Lägg till sammansatt men ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Lägg till okontrollerade ämnesord, t.ex. prel-termer i samband med ämnesordsförslag](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)

##### Allmänt ämnesord  
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡2 sao)  
  Länka till entitet från Svenska ämnesord, enligt instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)    
   
* Ämne - annan kontrollerad lista (subject = 650 -/7 ‡a, ‡2)  
  För ämnesord från andra kontrollerade listor, följ denna instruktion:  
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)  
  
* Ämne - okontrollerade (subject = 653 -/- ‡a)  
  För ämnesord från andra kontrollerade listor, följ denna instruktion:  
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   

##### Allmänt ämnesord med underindelning   
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡x, ‡2 sao)  
  Länka till entitet från Svenska ämnesord, enligt instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)  
  
##### Geografiska ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Länka till entitet från Svenska ämnesord, enligt instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)
  
##### Geografiskt ämnesord med geografisk underindelning  
* Geografiskt ämnesord (subject = 651 -/7 ‡a, ‡x, ‡2 sao)  
  För auktoriserade geografiska ämnesordssträngar, följ denna instruktion:    
 [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  För ej auktoriserade geografiska ämnesordssträngar, följ denna instruktion:  
 [Lägg till sammansatt men ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh) 
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
  Länka till entitet. Följ denna instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  
##### Ämnesord Person  
* Ämne/Agent/Person (subject = 600 1/4- ‡a)      
 Länka till entitet. Följ dessa instruktioner:  
 [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   
 I undantagsfall, skapa lokal entitet.  
  
##### Ämnesord Organisation  
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
  Länka till entitet. Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   
  I undantagsfall, skapa lokal entitet.  
 
#### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)``` Normalvärde för film som riktar sig till barn och ungdom.

#### Bild- och filmtexter 
 * Bild- och filmtexter (marc:subtitlesOrCaptions/marc:SubtitlesOrCaptions/language = 041 ‡j)</BR>
 Ange språk i eventuella bild- och filmtexter.</BR>
   ```Exempel: svenska (swe)```</BR> 
 Ange ytterligare språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram rätt entitet för språket.</BR>
 Länka till entitet.   
   ```Exempel: engelska (eng)``` 
 
#### Innehallstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.</BR>
  ```Exempel:```
  
   * ```two-dimensional moving image, tdi (= tvådimensionell rörlig bild)```
   * ```three-dimensional moving image, tdm (= tredimensionell rörlig bild)```  
  
#### Anmarkningar
##### Anmärkning om språk
 * Anmärkning/Anmärkning om språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Tal på engelska. Dubbad till svenska, finska, norska. Textad på engelska, svenska, finska och norska.```  

##### Anmärkning om medverkande
 * Anmärkning/Anmärkning om medverkande/Benämning (hasNote/marc:ParticipantOrPerformerNote/label = 511 ‡a)
  ```Exempel: Skådespelare: Nicole Kidman, Kirsten Dunst, Elle Fanning```
  
#### Sammanfattning av innehall
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. Skriv in uppgiften under Benämning.
     
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad```  
     
