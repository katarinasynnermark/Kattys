---
section: Materialtyper
title: Bidrag
order:
date: 2020-03-
tags:
- under arbete
- Bidrag
- Artikel
--- 

# Bidrag
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för ett bidrag, t.ex. en artikel eller recension? i en tidskrift eller ett kapitel i en årsbok eller i ett samlingsverk. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Språk](#sprak) |
| | [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |
| | [Upphovsuppgift](#upphovsuppgift) |  [Genre/form](#genre-form) |
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation)|
| | [Utgivning](#utgivning) | [Ämne](#amne) |
| | [Copyrightår](#copyrightar) |  [Målgrupp](#malgrupp)  |
| | [Identifikator](#identifikator) | [Innehållstyp](#innehallstyp)  |
| | [Omfång](#omfang) | [Anmärkningar](#anmarkningar) |
| | [Övriga fysiska deltajer](#ovriga-fysiska-detaljer) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| | [Medföljande material](#medfoljande-material) | |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |
| | [Systemkrav](#systemkrav) | |
| | [Anmärkning](#anmarkning) | |
| | [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter) | |


## Inledning
Beskrivningen av en artikel innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans för ett bidrag är titel, upphov och utgivning.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen bidrag, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Datorspel.  Ta bort hela stycket?

För information om katalogiseringsregler och Librispraxis, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") samt [se RDA Toolkit](https://access.rdatoolkit.org/). 

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** Ta bort?

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Instans). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Del av sammansatt resurs```

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:
  </br>```Unmediated, n (= omedierad)```
  
### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entiteten:
  </br>```Volume, nc (= volym)```
  
  MARC-koder?
  
### Titel 
#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  </br>```Exempel: Amerikanen och bilen```  
  </br>För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.   
  </br>```Exempel: Huvudtitel: Ett backstugebarn, fileringsvärde: 4```  
 [Se exempel i formathandboken för Libris/Voyager - Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/).

För att ange föredragen titel, t.ex. om bidraget är översatt, se Verk/Har titel/Titel/Huvudtitel.  

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  </br>```Exempel: Vilhelm Moberg ser på Amerika```
Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag. 
  
#### Varianttitel
* Har titelVarianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)
Används till exempel för felaktigheter och för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller    oväntade stavningar av ord. Skriv in uppgiften under Huvudtitel.

Varianttitel används för närvarande också för att ange titlar i icke-latinsk skrift.

För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra. 

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning. 
  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)<br/> 
   ```Exempel: Titeln felstavad, korrekt titel:```   
   
#### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, [se hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 
  
#### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)   
Välj först Har titel, välj sedan typ Parallelltitel. Skriv in uppgiften i Huvudtitel.</br> 
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra. 
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)   
Vid behov, lägg till Övrig titelinformation (subtitle) under Parallelltitel.  
     
### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)<br/>
  ```Exempel: Johan Ahlner, Karin Kjellgren```
  
### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För bidrag, använd Primär utgivning. 
 
#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
    
#### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Utgivningsår anges här, utan klamrar eller andra tecken - endast fyra positioner. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c.</br>
  ```Exempel: 2017```</br>
 
 Observera att År måste finnas med i beskrivningen, även om datum finns med.</br>
  
  För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.
  * Datum (= Utgivningstid) (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  Utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, anges här. Det kommer att exporteras till marcpostens 264 -/1 #c.
<br/>```Exempel:```
   * ```[2017]``` 
   * ```[mellan 2003 och 2005?]```

För att ange ett år utan klamrar eller andra tecken, använd År.

För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, [följ exempel i hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion): Produktion: Huvudsakligt tillgängliggörande. 
  
### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)   
  Skriv in allmänna anmärkningar här. För att lägga till Anmärkning, välj Anmärkning (hasNote) och lägg till.
  Skriv in uppgiften under Benämning.<BR/>
```Exempel: ```  
  
## Verk 
### Instans av verk (instanceOf/Work)
Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk.  
[Läs mer om Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).</BR> 

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk - Lägg till egenskaper under: Multimedia. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

### Verkets titel 
Ange vid behov den föredragna titeln för verket här. [Följ anvisningarna under Konstruera sökingångar för verk och uttryck i Anvisningar för katalogisering - RDA.](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/) 

#### Verkets titel - verk utan primär medverkan
Datorspel har sällan en primär medverkande. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet. Föredragen titel för ett verk utan primär medverkan ska anges i Uttryck av/Verk/Har titel/Titel/Huvudtitel. 
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
Under Instans av Verk, lägg till egenskapen Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), välj Verk. Det läggs till under Uttryck av. Lägg till Har titel. Välj Titel. 
Ange  den föredragna titeln i Huvudtitel.  
```Exempel:  Prototype (datorspel)```</BR>
Tillägget inom parentes (datorspel) görs för att skilja datorspelet Prototype från filmen Prototype.</BR> 
[Läs mer om Tillägg till auktoriserade sökingångar för verk](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/#tillaggtillauktsokingforverk) i Anvisningar för katalogisering (RDA).</BR>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
*	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 #p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
*	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 #n)  
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
*	•	Uttryck av/Verk/Språk (expressionOf/Work/language = 130 #l)
Lägg till eventuellt språk som ska ingå i sökingången. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 130 #l.

#### Verkets titel - verk med primär medverkan
Det är ovanligt att datorspel har primär medverkan. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet. Föredragen titel för ett verk med primär medverkan ska anges i Har titel/Titel/Huvudtitel.
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)</BR> 
Ange den föredragna titeln i Huvudtitel.
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
* Har titel/Titel/Deltitel (hasTitle/Title/partName = 240 1/0 #p)</BR> 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
* Har titel/Titel/Delbeteckning (hasTitle/Title/partNumber = 240 1/0 #n)</BR>
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).</BR> 
* Språk/Språk/Benämning (language/Language/label = 240 #l)</BR>
**Från och med version 1.7 skapas språktillägget automatiskt, för 240 #l. Språktillägget skapas även när det inte är en översättning. Det kommer att korrigeras i en kommande release av Libris katalogisering.**

### Medverkan och funktion
* Medverkan och funktion  
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket samt funktionskod för respektive agent.  Relationer till utgivare (710) anges för närvarande också här.</BR>
  För ytterligare instruktioner om hur man anger relationer till agenter, [se hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).</BR>
  [Se även Auktoritetsgruppens rekommendationer på Supportforum för nya Libris](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/).   
  
#### Primär medverkan
Det är ovanligt att datorspel har primär medverkande. Ofta är det två eller flera agenter (programmerare, utvecklare etc.) som är gemensamt ansvariga för att ha skapat verket. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet.  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  

#### Medverkan
* Medverkan och funktion/Medverkan/Agent (contribution/agent = 700 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Sydow, Max von, 1929-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.</BR> 
```Exempel: Röst, tal, spk```  
För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/) 
 
#### Funktioner som saknar funktionskod
Utbudet av funktionskoder för agenter kopplade till datorspel är fortarande ganska begränsat. För att ange en funktion som inte har en motsvarande funktionskod, klicka på plustecknet vid Funktion (Lägg till funktion) och sedan på Skapa lokal entitet. Klicka på plustecknet Lägg till egenskaper under: Funktion och välj Benämning. Skriv in önskad term. Värdet exporteras till 7XX #e.</BR>
```Exempel: Spelutvecklare```
  
### Sprak 
* Språk (language = 008/35-37)</BR>
  Länka till entitet.  
  ```Exempel: engelska (eng)``` 
  </BR>Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram entitet för språket.</BR>
  Länka till entitet.  
  
#### Översättning  
För datorspel som är/innehåller en översättning, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Multimedia och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 #h)  
  Ange originalspråk här. Klicka på plustecknet vid Instans av Verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ```Exempel: japanska (jpn)```  

### Relationer till ingaende verk och andra verk
#### Verk som ingår i det beskrivna verket
För att ange verk som ingår i det beskrivna verket motsvarande fält 700 1/2 #a, #d, #t (analytisk sökingingång för verk med primär medverkan) eller 730 0/2 #a (analytisk sökingång för verk utan primär medverkan):  
Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br>
Lägg till eventuell deltitel, delbeteckning och språk som ska ingå i sökingången. (För att lägga till språk, klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 700 eller 730 #l.)</br>
För ingående verk med primär medverkan, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna under [Medverkan och funktion](#medverkan-och-funktion): Primär medverkan.</br>
För utförligare instruktioner, [se även hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

#### Relationer till andra verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 1/- #a, #d, #t (icke-analytisk sökingingång för verk med primär medverkan) eller 730 0/_ #a (icke-analytisk sökingång för verk utan primär medverkan): 
Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br> 
Lägg till eventuell deltitel, delbeteckning och språk som ska ingå i sökingången. (För att lägga till språk, klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 700 eller 730 #l.)</br>
För ingående verk med primär medverkan, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna under [Medverkan och funktion](#medverkan-och-funktion): Primär medverkan.</br>
För utförligare instruktioner, [se även hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
   
### Genre form 
För utförliga anvisningar om hur man anger genre/form, [se hjälptexten Verk](https://libris.kb.se/katalogisering/help/workflow-work#genre): Genre form.
 
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)</br> 
Länka till entiteten:</br> 
 ```Datorspel```

För datorspel ska typ av fil (= 008/26) anges med termen Dataspel, g i Genre/form.

* Genre/form - termer som motsvarar marc-koder i 008</br> 
Välj Typ av fil.
Länka till entiteten:</br>
 ```Dataspel, g```
    
### Klassifikation  
För anvisningar om hur man anger klassifikation, [se hjälptexten Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.
 
### Amne  
* Ämne  
  Länka  i första hand till entiteter för ämnesord. [Följ instruktionerna under Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh).   

### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)```</br> 
  Normalvärde för spel som riktar sig till barn och ungdom.

För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), [se Målgruppsanmärkning](#Malgruppsanmarkning) under Instans.
 
### Innehallstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entiteten:</BR>
  ```Computer program, cop (= datorprogram)```
  
### Anmarkningar
#### Anmärkning om språk
 * Anmärkning/Anmärkning om språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
  ```Exempel: Tal och text på engelska. Manual på svenska.```  

### Sammanfattning av innehall
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. 
 Skriv in uppgiften under Benämning.
     
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad```
