## Datorspel - multimedia
Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid beskrivning av datorspel med utgångspunkt från exempel. Många av egenskaperna finns redan i mallen, andra kan behöva läggas till. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA") samt [RDA Toolkit](https://access.rdatoolkit.org/).

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  

För anvisningar om Adminmetadata, se hjälptexten [Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph).

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
| [Copyright- eller produktionsår](#copyright--eller-produktionsar) | [Innehållstyp](#innehallstyp) |
| [Identifikator](#identifikator) |  [Anmärkningar](#anmarkningar) |
| [Omfång](#omfang) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| [Övriga fysiska deltajer](#ovriga-fysiska-detaljer) | |
| [Bilagor](#bilagor) | |
| [Seriemedlemskap](#seriemedlemskap) | |
| [Målgruppsanmärkning](#malgruppsanmarkning) | |
| [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter) | |
| [Anmärkning](#anmarkning) | |

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Elektronisk). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```

#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entitet.  
  ```Exempel: computer, c```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entitet.  
  ```Exempel: computer disc, cd```  
  
#### Titel 
Titlar för datorspel kan vara svåra att bestämma. Ibland består de av ett franshisenamn följt av ett nummer och/eller en annan titel. I resursen anges ofta den andra titeln på en ny rad och i ett annat typsnitt. Rekommenderad praxis är att ange alla dessa titlar tillsammans i egenskapen huvudtitel, inte som huvudtitel och övrig titelinformation eller huvudtitel och deltitel/delbeteckning. Lägg till interpunktion om det behövs för tydlighet, [RDA 1.7.3.](http://access.rdatoolkit.org/rdachp1_rda1-808.html). Ange en endast en titel som undertitel om det klart framgår att den är underordnad huvudtiteln och inte är nödvändig för att särskilja titeln från andra titlar med samma franchisenamn.
<br/>```Exempel: Need for speed - undercover```
  
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA. 

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). 
  </BR>```Exempel: SimCity 4 - rush hour expansion```  
    För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.   
  ```Exempel: Huvudtitel: The hip hop dance experience, fileringsvärde: 4```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon,          mellanslag. 
  </BR>```Exempel: pro evolution soccer ```
  
För att ange föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Varianttitel
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html).
<br/>För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
  * Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 ‡a)<br/> 
 Skriv in uppgiften under Huvudtitel.    
```Exempel: Pro evoolution soccer 2014```

För en huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#Parallelltitel).<br/>

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som varianttitel. Notera dock att för datorspel är hela resursen godkänd källa, utan prioritetsordning, se [Librispraxis för RDA 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.<br/>

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning. 
  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)<br/> 
   ```Exempel: Titeln felstavad, korrekt titel:```   
   
##### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, se hjälptexten [Tryckt monografi](https://libris-qa.kb.se/katalogisering/help/workflow-print-monograph#titel): Titel. 


##### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel   
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Ange alternativa titlar här för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord.  

  För att lägga till en alternativ sökingång för titeln, klicka på plustecknet Lägg till egenskaper under: Elektronisk och välj Relation. Välj sedan typ: Relation. Lägg till Entitet (plustecknet vid Relation - lägg till egenskaper under: Relation). Skapa verk som lokal entitet (plustecknet vid Entitet - lägg till verk). Klicka i rutan Skapa lokal entitet, längst ner i sidorutan till höger, och välj Verk. Lägg till Har titel (plustecknet vid Verk - lägg till egenskaper under: Verk). 
Skriv in uppgiften under Huvudtitel.  

  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)
  
##### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 ‡a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 ‡a)   
Välj först Har titel, välj sedan typ Parallelltitel.      
Skriv in uppgiften under Huvudtitel.     
  
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 ‡b)   
Vid behov, klicka även på plustecknet vid Parallelltitel och lägg till Övrig titelinformation (subtitle).  
     
#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)<BR/>
  För att lägga till upphovsuppgift, klicka på plustecknet Lägg till egenskaper under: Elektronisk.
  <BR/>```Exempel: developed by Revolution Software```
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)<BR/>
  För att lägga till upplageuppgift, klicka på plustecknet Lägg till egenskaper under: Elektronisk.
  <BR/>Skriv in upplagebeteckning här. 
 <br/>```Exempel: Version 1.2```  
  
#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.<BR/>
Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.<BR/>
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c) finnas med.
 
##### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  För att lägga till Plats, klicka på plustecknet vid Primär utgivning (lägg till egenskaper under Primär utgivning) och välj Plats. Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.   
  Skriv in uppgiften under Benämning.  
  ```Exempel: Burbank, California```  
  
##### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Förenta staterna (xxu)``` 
  
##### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
  För att lägga till Agent, klicka på Lägg till egenskaper under Primär utgivning och välj Agent. Sök inte efter Agent som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Agent och välj det.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: Insomniac Games```   
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum  ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
##### Ar och datum 
* År (= Utgivningstid) (date = 008/07-10, 264 -/1 ‡c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Ange utgivningsår, utan klamrar eller andra tecken, endast fyra positioner. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.  
  ```Exempel: [2017]```  
* Datum (= Utgivningstid) (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange ett utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 ‡c. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, använd endast År.  
  Skriv in uppgiften.
 <br/>```Exempel:```
 
    * ```[2017]```
    * ```[mellan 2003 och 2007?]```
    
* Flera år (flerbandsverk)  
  För anvisningar om hur man anger delbeteckning och deltitel, se hjälptexten [Tryckt monografi](https://libris-qa.kb.se/katalogisering/help/workflow-print-monograph#utgivning): Utgivning. 

Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
  
#### Copyright- eller produktionsar
För datorspel anges alltid copyright- eller produktionsår, även om det sammanfaller med utgivningsår/distributionsår, se [Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html)
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  Skriv in uppgiften. För att få fram © eller, kopiera härifrån eller sök på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  Se också [Specialtecken](https://libris-dev.kb.se/katalogisering/help/search-04-special-chars). 
<br/>```Exempel:``` 

   * ```©2017```
   * ```℗2017```
    
#### Identifikator
Flera typer av identifikatorer kan finnas på datorspel. I mallen är Utgivningsnummer (annat) och EAN förvalda.

##### Utgivningsnummer (annat)
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: Utgivningsnummer (annat)```
* Identifikator/Utgivningsnummer (annat)/Värde (identifiedBy/VideoRecordingNumber/value = 028 5/1 ‡a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 7303903501```
* Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 5/1 ‡b)<br/> 
  Ange utgivarens namn.<br/>
  ```Exempel: Electronic Arts```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)<br/>
  Ange en bestämning.<br/>
  
##### EAN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: EAN```
* Identifikator/EAN/Värde (identifiedBy/EAN/value = 024 ‡a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 5705535059701```

För anvisningar om hur man anger ISBN, se hjälptexten [Tryckt monografi](https://libris-qa.kb.se/katalogisering/help/workflow-print-monograph#utgivning): Identifikator
   
#### Omfang  
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)<br/>
Skriv in uppgiften under Benämning.
 <br/>```Exempel: 1 DVD-ROM``` 
<br/>Om så önskas, för att uppgiften ska bli synlig i lokala system, kan konsol anges inom parentes efter omfång.
 <br/>```Exempel: 1 DVD-ROM (Xbox 360)```
<br/>Notera att det är obligatoriskt att ange konsol i egenskapen [Systemkrav](#systemkrav).
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)  
  ```Exempel: ljud, färg```
  
#### Bilagor
* Tillsammans med/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 ‡e)   
För att lägga till Tillsammans med, klicka på plustecknet Lägg till egenskaper under: Elektronisk och välj Tillsammans med. Skapa Instans som lokal entitet. (Plustecknet vid Tillsammans med, välj Skapa lokal entitet, längst ner i sidorutan till höger, skriv Instans och välj ** Instans.) Lägg till Benämning (plustecknet vid Instans - Lägg till egenskaper under: Instans). 
Skriv in uppgiften under Benämning.
<br/>```Exempel: 1 handledning (36 sidor)``` 

#### Seriemedlemskap
För anvisningar om hur man anger Seriemedlemskap, se hjälptexten [Tryckt monografi: Seriemedlemskap](https://libris-qa.kb.se/katalogisering/help/workflow-print-monograph#seriemedlemskap).<br/>
Franchisenamn ska inte anges som serieuppgift, se [Titel](#titel).

#### Malgruppsanmarkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 ‡a)  
För att lägga till målgruppsanmärkning, klicka på plustecknet Lägg till egenskaper under: Elektronisk och välj Målgrupp.  
Skapa Målgrupp som lokal entitet (plustecknet vid Målgrupp - Lägg till målgrupp. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Målgrupp och välj det).<BR/>
Skriv in uppgiften under Benämning. Åldersnivån kan om så önskas, preciseras enligt [PEGI](https://pegi.info), Pan European Game Information.<BR/>
```Exempel: PEGI 12```  
Observera att kodning av målgrupp, motsvarande 008/22, ska anges under Instans av Verk/Genre. 

#### Systemkrav
Det är obligatoriskt i Libris att ange konsol här. 
* Systemkrav/Modell/Benämning (systemRequirement/MachineModel/label)
Skriv in uppgiften under Benämning.  
```Exempel: XBox 360```<BR/>
Konsol kan även, om så önskas, för att uppgiften ska bli synlig i lokala system, anges inom parentes efter [omfång](#omfang).

#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)   
  Skriv in allmänna anmärkningar här. 
  </BR>För att lägga till Anmärkning, klicka på plustecknet Lägg till egenskaper under: Elektronisk och välj Anmärkning (hasNote). Tryck Enter för att lägga till Anmärkning.   
  Skriv in uppgiften under Benämning. 
```Exempel: Avsett för 1-7 spelare, 1-2 spelare i nätverk```  
  
#### Systemkrav och mediespecifika uppgifter
Här kan systemkrav och mediespecifika uppgifter som inte framgår någon annanstans i beskrivningen anges. Ange uppgiften som den är presenterad i resursen. Notera att uppgift om konsol anges i egenskapen [Systemkrav](#Systemkrav). 
* Har anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkningstext        (marc:hasSystemDetailsNote = 538 #a)
För att lägga till anmärkning om systemkrav och mediespecifika uppgifter, klicka på plustecknet Lägg till egenskaper under: Elektronisk och välj Har anmärkning: Systemkrav och mediespecifika uppgifter. Klicka på plustecknet Lägg till egenskaper under: Anmärkning: Systemkrav och mediespecifika uppgifter, välj Anmärkningstext (marc/systemDetailsNote).
Skriv in uppgiften.
    
### Verk   

#### Instans av Verk/Projicerad bild
* Instans av Verk/Projicerad bild (instanceOf/Work/ProjectedImage)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Projicerad bild.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  
För att lägga till egenskaper under Instans av Verk/Projicerad bild, klicka på plustecknet vid Instans av Verk/Projicerad bild - Lägg till egenskaper under: Projicerad bild. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

#### Verkets titel 
Ange vid behov den föredragna titeln för verket här. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").

##### Verkets titel - verk utan primär medverkande
Datorspel har sällan en primär medverkande och verkets föredragna titel ska då anges i Uttryck av/Verk/Har titel/Titel/Huvudtitel. Om den föredragna titeln är densamma som den titel som angetts som huvudtitel under Instans, behöver denna egenskap inte läggas till.
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
Under Instans av Verk/Multimedia, lägg till Uttryck av (plustecknet vid Instans av Verk/Multimedia - Lägg till egenskaper under: Multimedia, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.    
Skriv in uppgiften under Huvudtitel.  
```Exempel:  Prototype (datorspel)```
</BR>Tillägget inom parentes (datorspel) görs för att skilja datorspelet Prototype från filmen Prototype. Läs mer om [Tillägg till auktoriserade sökingångar för verk](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/#tillaggtillauktsokingforverk) i Anvisningar för katalogisering (RDA).
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning). 
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.  
Skriv in uppgiften.  
```Exempel: Svenska```

##### Verkets titel - verk med primär medverkande
Föredragen titel för ett verk med primär medverkan anger du enligt nedan.  Obs! Det är ovanligt att datorspel har primär medverkande. För att en agent ska ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet.
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a) 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.  
  
##### Verkets titel - analytisk sökingång  
För att ange verk som ingår i det beskrivna verket, motsvarande fält 700 0/2 ‡a ‡d + ‡t (analytisk sökingingång för verk med primär medverkande) eller 730 0/2 (analytisk sökingång för verk utan primär medverkande) i marc:  
Under Instans av Verk/Projicerad bild, klicka på plustecknet vid Verk (lägg till egenskaper under: Verk) och välj Har del.
Skapa verk som lokal entitet (plustecknet vid Har del - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Har del. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation. Ange föredragen titel i Huvudtitel. 
Lägg till eventuell deltitel, delbeteckning och benämning på språk.
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion). 

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 0/_ ‡a ‡d + ‡t (icke-analytisk sökingingång för verk med primär medverkande) eller 730 0/_ (icke-analytisk sökingång för verk utan primär medverkande) i marc: 
Under Instans av Verk/Projicerad bild, lägg till Relation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Projicerad bild) och välj Relation. Välj typ Relation. Lägg till Entitet genom att klicka på plustecknet vid Relation (Lägg till egenskaper under: Relation), välj Entitet. Skapa verk som lokal entitet (plustecknet vid Entitet - Lägg till verk). Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation. Ange föredragen titel i Huvudtitel. 
Lägg till eventuell deltitel, delbeteckning och benämning på språk.
För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under [Medverkan och funktion](#medverkan-och-funktion). 

#### Medverkan och funktion
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
##### Primär medverkan
Det är ovanligt att datorspel har primär medverkande. Ofta är det två eller flera agenter (programmerare, utvecklare etc.) som är gemensamt ansvariga för att ha skapat verket. För att en agent ska ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet.  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  

##### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Sydow, Max von, 1929-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 710 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden. 
```Exempel: Röst, tal, spk```  
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/) 
 
En utgivare är enligt RDA en agent som har en relation till manifestationen men i Libris anges utgivare i Instans av verk.
* Medverkan och funktion/Medverkan/Agent/Organisation (contribution/agent/organisation = 710 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Ubisoft Entertainment```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 710 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: Utgivare, pbl```  

Utbudet av funktionskoder för agenter kopplade till datorspel är fortarande ganska begränsat. För att ange en funktion som inte har en motsvarande funktionskod, klicka på plustecknet vid Funktion (Lägg till funktion) och sedan på Skapa lokal entitet. Klicka på plustecknet Lägg till egenskaper under: Funktion och välj Benämning. Skriv in önskad term. Värdet exporteras till 7XX #e.
```Exempel: Spelutvecklare```
  
#### Sprak 
Ange språk här.
* Språk (language = 008/35-37)</BR>
  Länka till entitet.  
  ```Exempel: engelska (eng)``` 
  </BR>Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram entitet för språket.</BR>
  Länka till entitet.  
  
##### Översättning  
För datorspel som innehåller en översättning, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Projicerad bild och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange originalspråk här.  
  Klicka på Lägg till egenskaper under: Projicerad bild, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
   
#### Genre  
 Länka till entitet. 
För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet (längst upp i sidorutan till höger), välj typ i listan över typer. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. Om sidorutan är stängd, klicka på plustecknet vid Genre/form (lägg till entitet) för att söka fram och välja fler entiteter.  

##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe. Välj kod från rätt lista. Mer [information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  
<BR/>```Exempel: Datorspel```

Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  

Här anges även typ av fil 008/26. Datorspel ska ha koden g (dataspel). Länka till entitet.
  ```Exempel: marc/ComputerTypeOfFileType-g```
 
#### Klassifikation  
För anvisningar om hur man anger klassifikation, se hjälptexten [Tryckt monografi: Klassifikation.](https://libris.kb.se/katalogisering/help/workflow-print-monograph#klassifikation)
 
#### Amne 
För anvisningar om hur man anger ämne, se hjälptexten [Tryckt monografi: Ämne](https://libris.kb.se/katalogisering/help/workflow-print-monograph#amne). 
 
#### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```
 
#### Innehallstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.</BR>
  ```Exempel: computer program, cop```
  
#### Anmarkningar
##### Anmärkning om språk
 * Anmärkning/Anmärkning om språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Tal och text på svenska, danska, norska, finska. Manual på engelska.```  
  
#### Sammanfattning av innehall
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
För att lägga till Sammanfattning av innehåll, klicka på plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text. Välj Sammanfattning av innehåll. Tryck Enter för att lägga till Samanfattning. Tryck Enter för att söka fram och lägga till Benämning (Lägg till egenskaper under: Sammanfattning).  
 Skriv in uppgiften under Benämning.  
     
 * Typ av innehållsbeskrivning/sammanfattning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av innehållsbeskrivning/sammanfattning (plustecknet vid Sammanfattning - lägg till egenskaper under: Sammanfattning). Välj typ från lista.  
 ```Exempel: Ej preciserad```  
     
