## Ljudbok - ljudinspelning 

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid beskrivning av ljudböcker (tillgängliga på CD eller MP3-CD), med utgångspunkt från exempel. Många av egenskaperna finns redan i mallen Ljudbok - ljudinspelning, andra kan behöva läggas till. Använd gärna Berika från mall för att få med de viktigaste egenskaperna. För en del egenskaper hänvisas till andra hjälptexter för mer detaljerad information. 

För instruktioner om att lägga till eller ta bort egenskap, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För anvisningar om Adminmetadata, se Adminmetadata,

För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA"). Notera att för utgivna fysiska fonogram är hela resursen godkänd källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. Denna Librispraxis, [KB SP 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.4.1](http://access.rdatoolkit.org/rdachp2_rda2-2904.html). 

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).  

### Innehåll  

| [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- |
| [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Bärartyp](#barartyp) | [Språk](#sprak) |
| [Titel](#titel) | [Genre](#genre) |
| [Upphovsuppgift](#upphovsuppgift) |[Klassifikation](#klassifikation) |
| [Upplageuppgift](#upplageuppgift) | [Ämne](#amne) |
| [Utgivning](#utgivning) | [Målgrupp](#malgrupp) |
| [Copyright- eller p-år](#copyright--eller-p-ar) | [Innehållstyp](#innehallstyp) |
| [Identifikator](#identifikator) | [Anmärkning om medverkande](#anmarkning-om-medverkande) |
| [Omfång](#omfang) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | |
| [Bilagor](#bilagor) | |
| [Seriemedlemskap](#seriemedlemskap) | | 
| [Innehållsanmärkning](#innehallsanmarkning) | | 
| [Anmarkning](#anmarkning) | | 

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Ljudinspelning). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entiteten:  
  ```audio, s```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entiteten:</br> 
  ```audio disc, sd```</BR>
  
  Om koden "d" (= ljudskiva) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system länka även till entiteten: </BR>
  ```marc/SoundDisc```
  
#### Titel
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html).</BR> 
 ```Exempel: Den frusna elden```  
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: Den frusna elden, fileringsvärde: 4```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

För att ange Föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
 ```Exempel: C-byråns kvinnliga agenter under andra världskriget : en dokumentär spionberättelse```

##### Varianttitel   
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html).</BR>
För att lägga till varianttitel, klicka på plusteknet vid Har titel (lägg till titel) och välj typ Varanttitel.
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 ‡a)   
  Skriv in uppgiften under Huvudtitel.    
 ```Exempel: Hierarchy in organizations```  

För en huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#parallelltitel).

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som en varianttitel. Notera dock att för utgivna fysiska fonogram är hela resursen godkänd källa, utan prioritetsordning, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varanttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning.

* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)  
  ```Exempel: Titeln felstavad, korrekt titel:```   
    
##### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 ‡n)  
Lägg till Har del (hasPart) under Har titel/Titel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Har del).  
Under Har del, skapa Titeldel (TitlePart) som lokal entitet (plustecknet vid Har del - Lägg till resurs, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel. Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.)   
Om Har del/Titeldel/Deltitel redan finns, lägg till Delbeteckning under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Delbeteckning (partNumber)).   
Skriv in uppgiften under Delbeteckning.  
```Exempel: 1```   

##### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 

##### Titel - alternativ stavning
För anvisningar om hur man lägger till en alternativ sökingång för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord (= 740), se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel.  
  
##### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 ‡a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 ‡a)   
Välj först Har titel, välj sedan typ Parallelltitel.      
Skriv in uppgiften under Huvudtitel.     
  ```Exempel: The Great Northern War explained```  
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 ‡b)   
Vid behov, klicka även på plustecknet vid Parallelltitel och lägg till Övrig titelinformation (subtitle).  
  ```Exempel: Charles XII and the ideological address```  
  
#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)  
  För att lägga till upphovsuppgift, klicka på plustecknet Lägg till egenskaper under: Instans.  
  Vid postimport: i vissa importerade poster saknas upphovsuppgift. Lägg då till det.   
  Skriv in uppgiften.  
  ```Exempel: Tom Marcus ; översättning: Svante Skoglund```
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)</BR>
  För att lägga till upplageuppgift, klicka på plustecknet Lägg till egenskaper under: Elektronisk.
  Skriv in upplagebeteckning här.  
  ```Exempel: Första upplagan```  
  
#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.    
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.      
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c) finnas med.
 
##### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  Sök inte efter Plats som entitet. Skapa Plats som lokal entitet. Skriv in uppgiften under Benämning. Klamra vid behov.</br>
  ```Exempel: [Malmö]```  
  
##### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
  
##### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
  Sök inte efter Agent som entitet. Skapa Agent lokal entitet. Skriv in uppgiften under Benämning.  
  ```Exempel: Bokfabriken```   
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning inom respektive utgivningsavsnitt. Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning. Land, År och eventuellt Datum ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
##### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 ‡c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Ange utgivningsår, utan klamrar eller andra tecken, endast fyra positioner. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.  
  ```Exempel: 2017```  
  * Datum (= Utgivningstid) (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange ett utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 ‡c.   
  För att ange ett år utan klamrar eller andra tecken, använd endast År. 
  <br/>```Exempel:```
  
    * ```[2017]```
    * ```[mellan 2003 och 2005?]```

För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, följ exempel i hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion): Produktion: Huvudsakligt tillgängliggörande. 
  
* Flera år (flerbandsverk)  
 För anvisningar om hur man anger flera år (flerbandsverk), se hjälptexten [Tryckt monografi](https://libris-qa.kb.se/katalogisering/help/workflow-print-monograph#utgivning): Utgivning. 
 
 Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
  
#### Copyright- eller p-ar
För fonogram anges alltid copyright- eller p-år, även om det sammanfaller med med utgivningsår/distributionsår, se [Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html). Det går bra att ange ett år här, så om både copyright- och p-år förekommer i resursen ange det senaste p-året.</br>
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  Skriv in uppgiften.
  <br/>```Exempel:``` 
    
    * ```©2017```
    * ```℗2017```
 
 För att få fram copyrighttecknet eller tecknet för p-år, kopiera från exemplet nedan.  
  Se också [Specialtecken](https://libris.kb.se/katalogisering/help/search-04-special-chars). Du kan t ex söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.
  <br/>```Exempel:``` 
    
    * ```©2017```
    * ```℗2017```
     
#### Identifikator 
Flera typer av identifikatorer kan finnas på ljudböcker. I mallen är Utgivningsnummer (ljudinspelning) och ISBN förvalda.
##### Utgivningsnummer (ljudinspelning)
* Identifikator (identifiedBy)<br/>
  Välj typ från lista.
  <br/>```Exempel: Utgivningsnummer (ljudinspelning)```
* Identifikator/Utgivningsnummer (ljudinspelning)/Värde (identifiedBy/AudioIssueNumber/value = 028 ‡a)<br/>
  Ange identifikator.
  <br/>```Exempel: NA242512```
* Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 #b)<br/>
  Ange utgivarens namn.
  <br/>```Exempel: Naxos AudioBooks```<br/>
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)  
  Ange eventuell bestämning.    
  
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
  Skriv in uppgiften.  
  ```Exempel: 97891881072```
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 ‡q)  
  Ange eventuell bestämning.  
    
#### Omfang
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). Ange speltid (inom parentes) efter omfång när uppgiften är lätt åtkomlig. 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)   
  Skriv in uppgiften under Benämning.  
  ```Exempel: 11 CD (13 tim., 30 min.) ```  
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)     
  Skriv in uppgiften.  
  ```Exempel: stereo```
  
#### Bilagor
* Tillsammans med/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 ‡e)   
För att lägga till Tillsammans med, klicka på plustecknet Lägg till egenskaper under: Ljudinspelning och välj Tillsammans med. Skapa Instans som lokal entitet. (Plustecknet vid Tillsammans med, välj Skapa lokal entitet, längst ner i sidorutan till höger, skriv Instans och välj ** Instans.) Lägg till Benämning (plustecknet vid Instans - Lägg till egenskaper under: Instans).    
Skriv in uppgiften under Benämning.  
 ```Exempel: 1 MP3-CD```
    
#### Seriemedlemskap
För anvisningar om hur man anger Seriemedlemskap, se hjälptexten [Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#seriemedlemskap): Seriemedlemskap.
   
#### Innehallsanmarkning  
För anvisningar om hur man lägger till olika typer av innehållsanmärkningar, se hjälptexten [Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#innehallsanmarkning)

#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)  
  Skriv in allmänna anmärkningar här.  
  För att lägga till Anmärkning, klicka på plustecknet i redigeringsvyn (den stora runda ikonen under Verktygsikonen - Lägg till egenskaper under: Ljudinspelning) och välj Anmärkning (hasNote). Tryck Enter för att lägga till Anmärkning.  
  Skriv in uppgiften under Benämning.</BR> 
  ```Exempel: Inläst ur: Stockholm : Bonnier, 2012. ISBN 978-91-0-012761-9```
  
### Verk   

#### Instans av Verk/Ljudmaterial  
* Instans av Verk/Ljudmaterial (instanceOf/Work/Audio)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Ljudmaterial.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

För att lägga till egenskaper under Instans av Verk/Ljudmaterial, klicka på plustecknet vid Instans av Verk/Ljudmaterial - Lägg till egenskaper under: Ljudmaterial. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Verkets titel
 
Ange vid behov den föredragna titeln för verket här. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
Föredragen titel ska anges för översättningar och för verk som har givits ut under olika titlar på samma språk. En föredragen titel ska också anges om olika verk, som saknar primär medverkande, har samma titel. 

##### Verkets titel - verk med primär medverkande
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  Ange den föredragna titeln för ett verk med primär medverkande här.</BR>
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: En äkta man, fileringsvärde: 3```
* Har titel/Titel/Deltitel (hasTitle/Title/partName = 240 1/0 ‡p)</BR> 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
* Har titel/Titel/Delbeteckning (hasTitle/Title/partNumber = 240 1/0 ‡n)</BR>
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).</BR> 
  ägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
* Språk/Språk/Benämning (language/Language/label = 240 ‡l)</BR>
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning. Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.</BR>
 
##### Verkets titel - verk utan primär medverkande
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
  Ange den föredragna titeln för ett verk utan primär medverkande här.  
Under Instans av Verk/Ljudmaterial, lägg till Uttryck av (plustecknet vid Instans av Verk/Ljudmaterial - Lägg till egenskaper under: Ljudmaterial, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Skriv in uppgiften under Huvudtitel.  
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning. Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 130 ‡l.</BR>

##### Verkets titel - verk som ingår i det beskrivna verket 
För att ange verk som ingår i det beskrivna verket, motsvarande fält 700 0/2 ‡a ‡d + ‡t (analytisk sökingingång för verk med primär medverkande) eller 730 0/2 ‡a (analytisk sökingång för verk utan primär medverkande) i marc:  
Under Instans av Verk/Ljudmaterial, klicka på plustecknet vid Verk (lägg till egenskaper under: Verk) och välj Har del.
Skapa verk som lokal entitet (plustecknet vid Har del - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Har del. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation. Ange föredragen titel i Huvudtitel. 
Lägg till eventuell deltitel, delbeteckning och benämning på språk.
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion). 

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 0/- ‡a ‡d + ‡t (icke-analytisk sökingingång för verk med primär medverkande) eller 730 0/- ‡a (icke-analytisk sökingång för verk utan primär medverkande) i marc: 
Under Instans av Verk/Ljudmaterial, lägg till Relation genom att klicka på plustecknet vid Instans av Verk/Ljudmaterial (Lägg till egenskaper under: Ljudmaterial) och välj Relation. Välj typ Relation. Lägg till Entitet genom att klicka på plustecknet vid Relation (Lägg till egenskaper under: Relation), välj Entitet. Skapa verk som lokal entitet (plustecknet vid Entitet - Lägg till verk). Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation. Ange föredragen titel i Huvudtitel. 
Lägg till eventuell deltitel, delbeteckning och benämning på språk.
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion). 

#### Medverkan och funktion  
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Relationer till Agent i verksbeskrivningen](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
##### Primär medverkan
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.
<br/>```Exempel: Lindgren, Astrid, 1907-2002```
  
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/author (= Författare)```

##### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Sauk, Stefan, 1955-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: relator/nrt (= berättare, inläsare)```  

#### Sprak 
* Språk (language = 008/35-37)  
  Ange det talade språket här. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  För att ange att texten är på flera språk, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  
  
##### Översättning 

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Ljudmaterial och välj Anmärkning: Språk. Välj fras från lista</BR>
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till egenskaper under: Ljudmaterial, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
#### Genre  
 Länka till entitet. 
För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet (längst upp i sidorutan till höger), välj typ i listan över typer. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. Om sidorutan är stängd, klicka på plustecknet vid Genre/form (lägg till entitet) för att söka fram och välja fler entiteter.  

##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe. Välj kod från rätt lista. Mer [information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  
  ```Exempel:``` 
  
   * ```Självbiografier```
   * ```Ljudböcker```

Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  

##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Välj Litterär genre i listan över typer. Länka till entitet.  
  ```Exempel: 0 ( = ej skönlitterärt verk)```
  
##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Välj Biografiskt material i listan över typer. Länka till entitet.  
  ```Exempel: a (= självbiografi)```  

#### Klassifikation  
För anvisningar om hur man anger Klassifikation, se hjälptexten [Tryckt monografi:](https://libris.kb.se/katalogisering/help/workflow-print-monograph#klassifikation) Klassifikation.
   
#### Amne
För anvisningar om hur man anger Ämne, se hjälptexten [Tryckt monografi:](https://libris.kb.se/katalogisering/help/workflow-print-monograph#amne) Ämne.

#### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
  ```Exempel: term/rda/SpokenWord```  
  
#### Anmarkning om medverkande
 * Anmärkning/Anmärkning om medverkande/Benämning (hasNote/marc:ParticipantOrPerformerNote/label = 511 ‡a)
  ```Exempel: Inläsare: Gunilla Röör```
  
#### Sammanfattning av innehall    
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 ‡a)  
För att lägga till Sammanfattning av innehåll, klicka på plustecknet vid Instans av Verk/Ljudmaterial - Lägg till egenskaper under: Ljudmaterial. Välj Sammanfattning av innehåll. Tryck Enter för att lägga till Samanfattning. Tryck Enter för att söka fram och lägga till Benämning (Lägg till egenskaper under: Sammanfattning).  
 Skriv in uppgiften under Benämning.  
     
 * Typ av innehållsbeskrivning/sammanfattning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av innehållsbeskrivning/sammanfattning (plustecknet vid Sammanfattning - lägg till egenskaper under: Sammanfattning). Välj typ från lista.  
 ```Exempel: Ej preciserad```  
    


