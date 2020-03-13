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
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för ett bidrag, t.ex. en artikel eller recension? i en tidskrift eller ett kapitel i en monografi. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Språk](#sprak) |
| | [Titel](#titel) |[Genre/form](#genre-form)|
| | [Upphovsuppgift](#upphovsuppgift) | [Klassifikation](#klassifikation)  |
| | [Utgivning](#utgivning)| [Ämne](#amne)|
| | [Anmärkning](#anmarkning) | [Innehållstyp](#innehallstyp) |
| | | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |


## Inledning
Beskrivningen av ett bidrag innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans för ett bidrag är titel, upphov och utgivning.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen bidrag, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Datorspel.  Ta bort hela stycket?

För information om katalogiseringsregler och Librispraxis, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") samt [se RDA Toolkit](https://access.rdatoolkit.org/). 

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). 

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Instans). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista:  
  ```Exempel: Del av sammansatt resurs```

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:
  </br>```Unmediated, n (= omedierad)```
  
### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entiteten:
  </br>```Volume, nc (= volym)```
  
### Titel 
#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  ```Exempel: Amerikanen och bilen```</br>   
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.
 ```Exempel: Huvudtitel: Ett backstugebarn, fileringsvärde: 4```  
 [Se exempel i formathandboken för Libris/Voyager - Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/).</br>
 
För att ange föredragen titel, t.ex. om bidraget är översatt, se [Verkets titel] (#verkets titel).  

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  </br>```Exempel: Vilhelm Moberg ser på Amerika```</br>
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
<br/>```Exempel:```
   * ```Om en planerad fredskonferens som aldrig kom till stånd``` Eller ska en sådan anmärkning ligga i 505 8/_ #a Har    innehållsförteckning/Innehållsförteckning/Benämning?
   * ```Replik på Tommy Hammarströms artikel "Lögnen om Sigismund"``` Recension av?
  
## Verk 
För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

[Läs mer om egenskaperna under den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work)

### Instans av verk 
* Instans av verk/Text (instanceOf/Work/Text)
För ett tryckt bidrag är verkstypen Text. 

### Verkets titel 
Ange vid behov den föredragna titeln för verket här. [Följ anvisningarna under Konstruera sökingångar för verk och uttryck i Anvisningar för katalogisering - RDA.](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/) 
Ange föredragen titel för översättningar, för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk.

#### Verkets titel - verk med primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)</BR> 
"Originaltitel" för ett verk med Medverkan och funktion/Primär medverkan anges här.

#### Verkets titel - verk utan primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  

### Medverkan och funktion
[Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance) 

* Medverkan och funktion/Primär medverkan/Agent/Person</br>
(contribution/PrimaryContribution/agent/Person = 100 1/- #a)

* Medverkan och funktion/Primär medverkan/Funktion</br>
(contribution/PrimaryContribution/role = 100 #4)

* Medverkan och funktion/Medverkan/Agent/Person</br>
(contribution/agent/Person = 700 1/- #a)

* Medverkan och funktion/Medverkan/Agent/Organisation (710 2/-)</br>

* Medverkan och funktion/Medverkan/Agent/Jurisdiktion (710 1/-)</br>
 
#### Sprak 
* Språk (language = 008/35-37)</BR>
  Länka till entitet.  
  ```Exempel: svenska (swe)``` 
  För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk under [Översättning](#oversattning).
  
#### Översättning  
För en artikel som är/innehåller en översättning, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 #h)  
  Ange originalspråk här. Klicka på plustecknet vid Instans av Verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  

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
