# **MediKuh**

<img src="https://github.com/riosarah/MediKuh/assets/145586660/8523b1ea-f87f-4356-a884-f359d8b86d21" alt="drawing" width="300"/> <br>

## Projekt Outline

Das Projekt MediKuh geht jenes Problem an, vor dem bestimmte Gruppen in unserer Gesellschaft stehen, 
wenn es um die tägliche Einnahme von wichtigen Medikamenten geht. <br>
Mithilfe moderner Technik sollen diese Personengruppen bei der Einnahme von Medikamenten unterstützt werden (Erinnerung). <br>
Die Unterstützung erfolgt mittels einer App, die sich in 2 wesentlichen Punkten von bereits am Markt befindlichen Lösungen unterscheidet:

>- Einfachheit in der Bedienung <br>
>- Individualiserbarkeit für bestimmte Personengruppen

<br>

Da es sich hierbei um sensible Daten handelt, werden Daten eines Users vertraulich behandelt. 
Auch ist es uns wichtig zu betonen, dass die App den User im negativen Sinn nicht überwachen soll, <br>
sondern vielmehr als Unterstützung und Hilfe gesehen werden soll. 

<hr>

### Initial situation:

Beim Umgang mit Medikamenten ist Sorgfalt gefragt. 
Man muss sie zur richtigen Zeit und korrekt dosiert einnehmen.
Apps für das Smartphone können dabei helfen, den Überblick zu behalten.

Die aktuell marktdominierenden Apps sind:

> - **Mediteo**<br>
> - **MyTherapy**<br>
> - **Medisafe**

### Die größten Schwachstellen aktuell:

<br>

**Unzureichende Stabilität der Applikation**<br>
Fehleranfällig durch zu komplexen Aufbau

**Accessibility**<br>
Zu viel und unzureichend benutzerfreundlicher Text <br>
Wenige Bilder

**Customization**<br>
Fehlende Optionen hinsichtlich verschiedener Einschränkungen <br>
UI/UX-Anpassungen (körperliche oder visuelle Beeinträchtigungen)

**Intransparenz**<br>
Teilweise nicht ersichtlich, womit Geld verdient wird
<br>
<br>

### Die Person soll im Mittelpunkt der Gestaltung der UI/UX stehen:

<br>

**Wahrnehmbar**<br>
Informationen un Bestandteile der Benutzerschnittstelle müssen <br>
den Benutzern so präsentiert werden, dass diese sie wahrnehmen können.

**Bedienbar**<br>
Einfache Bedienbarkeit der Navigation muss gegeben sein.

**Verständlich**<br>
Informationen und Bedienung müssen verständlich sein.

**Robust**<br>
Inhalte müssen robust genug sein, damit sie von einer großen Auswahl an Benutzer, <br>
einschließlich assistierender Techniken interpretiert werden können.

## Accessibilty

Ein Hauptaugenmerk unserer App soll die Barrierefreiheit sein. Hier möchten wir weit über die Mindestanforderungen hinaus gehen. Das User-Experience ist eines unserer Hauptanliegen.

Laut einer Studie von Shunguo Yan und P. G. Ramachandran, zwei Accessibilty Forschern in Texas, über "The Current Status of Accessibility in Mobile Apps" gibt es ein paar Kernelemente, <br>
an der die Accessibilty von Apps oft scheitert. In 97 Prozent der Fällen, scheiterte es an fehlenden Elementfokus, fehlende Elementbeschreibungen, geringen Text-Farbkontrast, <br>
unzureichenden Abstand zwischen Elementen und Unterschreitung der minimalen Textschriftgrößen und Elementgrößen verursacht. Zusammen genommen machten diese Barrierefreiheitsprobleme 97,0% der Verstöße aus.


Das Hauptinterface soll in der Darstellung extrem minimalistisch und intuitiv gestaltet sein. Um sich an alle Bedürfnisse des Users anpassen zu können, sollen viele Elemente der Oberfläche individualisierbar sein. <br>
Folgende Möglichkeiten sind in den Einstellungen wählbar:
>- Schriftart (Zwischen drei legasthenie-freundlichen Schriftvarianten wählbar)
>- Schriftgröße (Bis auf 200% vergrößerbar)
>- Farben (Farbblindheitsfreundliches Design, sowie eine Erhöhung des Kontrastes)
>- visuelle Darstellungselemente / Icons

<br>

Unsere Medikamentensuche schlägt mehrere Medikamentennamen bei der Eingabe vor, um selbst bei Erinnerungslücken die Suche zu erleichtern. <br>
Die App hat einen integrierten Screen-Reader, der alle Bedienungselemente und Inhalte ausliest. <br>
Die Benutzung dieses Elementes wird beim ersten Download der App abgefragt und kann zu einem späteren Zeitpunkt in den Einstellungen wieder aktiviert werden.

### Weitere Elemente:

Barcodescanner für Medikamente
Eine Option zur Medikamentensuche soll das Scannen von Medikamenten - Barcode sein. Dies erspart die händische Eingabe des Medikamentennamens. <br>
Weiters soll in der Betaversion die Möglichkeit bestehen, Beipackzettel aufzurufen und sich diese auslesen zu lassen. 

Mit Voice device control ermöglichen wir nicht nur eine optimierte Steuerung für sehbeeinträchtigte Nutzer,<br>
sondern bieten auch Benutzern mit muskulären Beeinträchtigungen oder rheumatischen Erkrankungen eine alternative Steuermöglichkeit. <br>
Dafür benötigen wir Erlaubnis für den Audiozugriff auf dem Mobilgerät. <br>
Stimmunterstütze Suche kann anstelle von Medikamentenname - Eingabe oder Barcode Scanner benutzt werden.


<br>


## Datensicherheit

Wir streben an unsere App auf verschiedenen Betriebssystemen laufen lassen zu können. Die dafür geltenden Datenbestimmung werden wir für unser Programm selbstverständlich umsetzen. <br>
Da unser System mit medizinisch heiklen Daten arbeitet, die als besonders schützenswerte Daten deklariert sind, muss darauf besonderes Augenmerk gelegt werden. <br>
So ist neben der eigentlichen Appentwicklung der Datenschutz eines unserer wichtigsten Schwerpunkte. <br>
Unsere App soll zu Beginn mit minimalen Standardberechtigungen funktionieren, um Sicherheitsentscheidungen zu vereinfachen.

Mit einem auf die Sicherheitsbestimmungen angepassten Anwendungsframework, stellen wir sicher, dass wir die Daten so verschlüsseln, dass andere Applikationen nicht darauf zugreifen können. <br>
Es schränkt auch die Berechtigungen und Zugriffe anderer Programme auf unsere internen Daten auf den Mobilgeräten ein.

Wir verwenden Pseudonymisierung für die Verschlüsselung unserer Daten. Daten werden außerhalb des Endnutzergeräts nur verschlüsselt gespeichert, <br>
so dass diese selbst bei einem Datenleak nicht den Benutzern zugeordnet werden können. 

Um ein gültiges Verzeichnis der erfassten Einwilligungen speichern und sicher verwahren zu können, benötigt unsere App einen Netzwerkzugang <br>
und einen Cloudspeicher mit hochgradiger Datenverschlüsselung. Hierbei werden alle Personenbezogenen Daten nur Identifikationsnummern für die heruntergeladene Applikation zugeordnet. <br>
So soll das Risiko von medizinischem Profiling über unsere Datenbank verringert werden.

Regelmäßige Risikoanalyse unserer Technischen Sicherheit. 
Patch Management um Sicherheitslücken zu schließen. Ablauf und Prozedere wird im 6-Monatsupdate festgehalten.



**Lokaler Datenspeicher:** <br>
Aktualisieren des internen Speichers der App auf dem Endnutzergerät in regelmäßigen Abständen
Externe Daten können nur aus von uns genehmigen Quellen in das Programm geladen werden.<br>
Wir nutzen Systeme, wie Adress Space Layout Randomization (ASLR) und No-Execute (NX)um Speicherverwaltungsfehler zu reduzieren.<br>
In der Beta-version soll unser Programm nur auf oberflächliche Daten wie Datum, Uhrzeit am Handy zugreifen. 
Es darf Benachrichtigungen senden. <br>
Zugriffe auf Kamera - Fotos sollen nicht gespeichert werden.

<br>
<br>

# Allgemeine Bedingungen und Einschränkungen

## Organisatorische Einschränkungen und Framework Bedingungen

Wir sind eine unabhängiges Entwicklerteam, dass sich in seiner Freizeit mit der Entwicklung
der **App Medikuh** beschäftigt. Unser Budget ist momentan beschränkt auf die Ressourcen, <br>
die uns durch unsere anderen Einkünfte zur Verfügung stehen. Wir sind offen für Interessierte, die sich finanziell 
an diesem Projekt beteiligen wollen.<br>
Wir haben ein gutes Basiswissen im Bereich Datenbanken und Grafikdesign. Daher können wir dieses Wissen gut 
in die Projektplanung einfließen lassen.<br>
Die Planung des Projekts befindet sich in der Metaphase. Während der Projektplanung sind wir offen dafür, 
Investoren und weitere Mitarbeiter anzuwerben.

Unsere Verpflichtungen gegenüber diesem Projekt bedingen sich durch unsere Teilnahme an dem Kurs *Systemplanung und Projektmanagement*.<br>
Die Deadline für die Abgabe der ersten Outline ist der 24 Dezember. 


## Technische Einschränkungen ##
Alle Unterlagen sind momentan auf GitHub verfügbar. Ob der eigentliche Code einsehbar sein wird, ist noch nicht absehbar und
hängt von den Rahmenbedingungen des Projekts in der aktiven Durchführungsphase ab.<br>
Das Grundgerüst des Projekts wird auf C# aufbauen, während das grafische Design auf Adobe basierten Applikationen aufbauen soll.<br>
Außer unseren Rechnern werden mehrere mobile Geräte angeschafft werden müssen, um ein glattes Ablaufen auf diesen zu testen.


### Datenschutz ###
Wir streben an unsere App auf verschiedenen Betriebssystemen laufen lassen zu können. Die dafür geltenden Datenbestimmung
werden wir für unser Programm selbstverständlich umsetzen. <br>
Da unser System mit medizinisch heiklen Daten arbeitet, 
muss darauf besonderes Augenmerk gelegt werden. <br>
So ist neben der eigentlichen Appentwicklung
der Datenschutz eines unserer wichtigsten Schwerpunkte.

Um ein gültiges Verzeichnis der erfassten Einwilligungen speichern und sicher verwahren zu können, benötigt unsere App einen Netzwerkzugang, <br>
bzw braucht es einen möglichst sicheren Cloudspeicher mit hochgradiger Datenverschlüsselung. <br>
Um den bestmöglichen Sicherheitsstandard zu erreichen, werden wir vorraussichtlich Experten in diesem Bereich 
hinzuziehen müssen.

<br>

## Project objectives and system concepts: 
Der Grundgedanke des Projektes ist es, Nutzern unserer App die Möglichkeit zu geben, sich mittels moderner Technologie eine Erleichterung bei der täglichen Einnahme von Medikamenten zu verschaffen.<br>
Diese tägliche Routine kann für gewisse Personengruppe eine nicht zu unterschätzende Hürde darstellen, vor allem dann, wenn eine Unterstützung durch andere Personen (Angehörige, etc) nicht im ausreichenden Maße erfolgen kann.<br>
Genau in diesem Punkt soll unsere App eingreifen und Unterstützung bieten! Wie man bereits nach kurzer Recherche herausfinden kann, gibt es am Markt zahlreiche Programme, die eine diesbezügliche Unterstützung bieten (wollen), <br>
aber - unserer Meinung nach - keine derartige Individualiserung bieten.

**Dafür steht die App:**
> **M** - MODERN<br>
> **E** - EINZIGARTIG<br>
> **D** - DAUERHAFT<br>
> **I** - INNOVATIV<br>
> **K** - KOSTENGÜNSTIG<br>
> **U** - UNKOMPLIZIERT<br>
> **H** - HILFEGEBEND

<br>

## Wichtige Schritte: ##
- Kooperation mit Ärzten und Seniorenheimen.
- Zusammenarbeit eventuell mit Herstellern bestimmter Handymarken (Pre-Instalation).
- Festlegen der einzelnen Teams (Anzahl, Budget, ...) - IT, Marketing, Organisation.
- Datenschutz: Rechtliche Situation klären, da es sich um personenbezogene Daten handelt.
- Service: Wie soll den Usern bei Fragen geholfen werden.
- Haftung: Wie gehen wir mit Problemen um (Falscheinnahme)?
- Testphase: Detailplanung erforderlich (ev mit Seniorenheim etc).

<br>


## Möglichkeiten und Risiken 

### Marktanalyse und potenzielle Kundschaft ##
Laut der Statistik Austria wird der Bevölkerungsanteil der über 65 Jährigen in den 30er Jahren 25 Prozent der Bevölkerung ausmachen.<br>
Wenn man allein auf die wachsende Anzahl zukünftigen Senioren den Fokus legt, die anders als vorherige ältere Generationen, <br>
ein immer besseres Verständnis von Technik aufweist, zeigten sich ganz klare Wachstumsmöglichkeiten für unsere App heraus. 

Ein Ziel, dass wir im Hinblick auf diesen Markt sehen wäre, besonders auf **Seniorenhandys** wie Emporia, Doro oder Tiptel unsere App zu einer der zentralen Applikationen zu machen. <br>
Dass nun immer mehr Anbieter auf diesen Markt einsteigen, zeigt auch die steigende Nachfrage unter älteren Menschen nach technischer Hilfe. <br>
Gleichzeitig kristallisiert sich in den letzten Jahren ein Mangel an Pflegepersonal hervor, die diese Bevölkerungsgruppe im Alltag unterstützen könnte.<br>
Hier werden unterstützende Werkzeuge einen immer wichtigeren Platz einnehmen.

Eine weitere Kundschaft, die noch leichter aufzuschließen wäre, sind der Anteil psychisch oder chronisch kranker Menschen in Österreich.<br>
Allein fünf Prozent der Österreicher sind mit schweren psychiatrischen Erkrankungen diagnostiziert und auf die regelmäßige Einnahme von **Psychopharmaka** angewiesen ist. <br>
Aber auch unter der Gesamtbevölkerung nimmt der Einsatz von Psychopharmaka zu. Laut der Donau Universität Krems stieg der Verbrauch innerhalb von neun Jahren um 25 Prozent. <br>
Somit ist es einer der am meisten wachsenden Spalten der Pharmazeutik.

Diese zwei Bevölkerungsgruppen weisen einen hohen Bedarf für Unterstützungstechnologie auf. Gleichzeitig mangelt es an übersichtlichen und frei zugänglichen Hilfsmitteln.<br>
Besonders im Bereich der intuitiven Designgestaltung zeigen sich gigantische Verbesserungsmöglichkeiten. 

Bei vergleichbaren Apps wird auf viele Eingabemöglichkeiten gesetzt. <br>
Man kann unzählige Daten bezüglich der Tabletteneinnahme festhalten und sieht sich schnell mit den steril wirkenden, mit Schrift überladenen Displays überfordert.

Ein intuitiveres Design, dass auf die nötigsten Daten abgespeckt ist, kommt unserer Zielkundschaft hier viel näher. <br>
Ohne dass es notwendig ist, ewig viele Zeilen zu lesen, oder einzugeben, kann unsere App anhand der Symbolbilder kinderleicht bedient werden.


## Profitchancen ##
Der Marktführer Smartpatient mit seiner App "MyTherapy" wird von rund 1,4 Millionen Patienten Europaweit genutzt. Der Konkurent "Arznei aktuell" hat laut eigenen Angaben 250 Tausend regelmäßige Nutzer. <br>
Selbst "Mediteo", eine Medikamenten-App, die erst vor kurzem als Testsieger von Stiftung Warentest ausgezeichnet wurde, hat ein Display voller überwältigender Informationen.<br>
Auch hier braucht es eine Weile, um sich mit der Flut an Möglichkeiten zurecht zu finden.



## Verlustrisiko und wahrscheinliche Verluste ##
Durch die sehr bekannten Konkurrenten am Markt, könnten sich Schwierigkeiten beim Erreichen von potenziellen Kunden auftuen. <br>
Hier ist es sehr wichtig, sich nicht nur optisch von denen schon am Markt erhältlichen Programmen zu unterscheiden, sondern ganz gezielt auf Marketinglücken dieser Produkte abzuzielen. <br>
Da wir momentan mit noch wenig finanzieller Rückendeckung agieren, die uns im Bereich Publicity ein große Hilfe sein könnte, müssen wir uns auf einen schleppenden Start einstellen.<br>
Es bleibt zu berücksichtigen, dass trotz Überlegenheit unseres Produkts im Hinblick auf viele Designfeatures, all unsere Bemühungen umsonst sind, wenn wir unsere Kundschaft nicht erreichen können. 

Eine kurzfristige Möglichkeit, um den schleppenden Start zu verkürzen, wäre Kontakt mit Health Influencern aufzunehmen. Wenn wir beispielsweise einflussreiche Personen mit Beeinträchtigungen,<br>
oder chronischen Erkrankungen, in unsere Appplanung mit einbeziehen ergeben sich zweierlei Möglichkeiten. <br>
Ein kostengünstiger Zugang zu Betat-Testern und ein großartiges Marketingpotential mit verhältnismäßig geringem Aufwand.

<br>

## Kalkulation
Bei der Entwicklung unserer Gesundheits-App sind uns - zusätzlich zu technischen Aspekten - auch die finanziellen Punkte natürliche einige Überlegungen wert:

>Gesamtbudget: **EUR 30000**<br>
>Kosten: **EUR 26000**<br>
>Differenz: **EUR 4000** für zusätzliche Kosten

Hierfür unterscheiden wir 3 Gruppen:

### Entwicklungskosten:
Die Kosten für die Entwicklung einer Gesundheits-App können je nach Umfang und Komplexität der App variieren. <br>
Laut einer Studie betragen die durchschnittlichen Kosten für die Entwicklung einer App zwischen 20 und 30.000 Euro. <br> 
Quelle: ![starting-up.de](www.starting-up.de)

Denn der zeitliche Aufwand, Komplexität und Funktionsumfang einer mobilen App ist ausschlaggebend für den Preis. Für folgende Bereiche fallen bei der App-Entwicklung Kosten an:

**Planungsphase (Zielfindung) - EUR 2000**
- Erstellung von Mockups, Design-Patterns
- Definition von Zielfunktionen
- Konkurrenzanalyse ev mit externer Hilfe (Agentur)

**App Design - EUR 2000**
- optische Gestaltung (UI)
- Benutzerfreundlichkeit (UX)
- Ein UI/UX-Designer kostet im Durchschnitt 100 € pro Stunde bzw. **EUR 1000** Tagessatz.

**Programmierung und Testing - EUR 10000**
- In dieser Phase folgt die tatsächliche Programmierung der App.
- Das Programmieren ist der zeit- und kostenintensivste Teil bei der Entwicklung einer App.

**--- Unser Approach ---**
Unter Einbeziehung obiger Kosten würden wir einen Prototyp bzw. MVP (*Minimum viable product, Quelle: [t2informatik.de](https://t2informatik.de/wissen-kompakt/minimum-viable-product))*<br>
also ein brauchbares Produkt mit minimalen Eigenschaften entwickeln. Dieser Ansatz zielt auf frühzeitiges Nutzer- und Marktfeedback ab.

Wir rechnen daher mit **EUR 14.000** für eine lauffähige Version.<br>
Zum Vergleich:<br>
Goodfirms (2018, GoodFirms is an internationally B2B reviews and ratings platform, [goodfirms.co](https://www.goodfirms.co)) untersuchte die durchschnittliche Zeit<br> 
und die Kosten für die Entwicklung einiger erfolgreicher Apps und kam zu folgenden Schätzungen: Die MVP-Version von Tinder kostete zwischen **35.000 bis 50.000 Euro**.


### Marketingkosten:
Beim App-Marketing geht es um die Interaktion mit Nutzern. <br>
Dort angefangen, wo diese das erste Mal von unserer App gehört haben, bis dahin, wo sie treue User sind, die unsere App täglich nutzen.

Beim Marketing für unsere App setzen wir auf einen Marketing-Mix. <br>
Geworben werden soll in sozialen Medien, aber auch über Influencer-Marketing soll unsere Zielgruppe erreicht werden. <br>
Zu guter Letzt soll auch die App-Store-Optimierung durchgeführt werden.<br>
Wir werden ca. 30 % des Budgets für Werbung einplanen. Somit sind das dann **EUR 9000**.


### Wartungskosten:
Nach der Veröffentlichung Ihrer App müssen wir Wartungskosten berücksichtigen, um sicherzustellen, dass unsere App reibungslos funktioniert und auf dem neuesten Stand bleibt.<br>
Lt. Studien können sich App-Wartungskosten auf ca. 20% der Entwicklungskosten belaufen (Quelle: [uhp.digital](https://uhp.digital/blog/was-kostet-eine-app)).<br>
Wir veranschlagen hierfür ca. **EUR 3000**.


### Monetarisierung:
Es gibt verschiedene Möglichkeiten mit einer App Geld zu verdienen. Einige der gängigsten Modelle sind Werbung, In-App-Käufe und Abonnements. <br>
Uns ist bewusst, dass es wichtig ist, das richtige Monetarisierungsmodell auswählen, um sicherzustellen, dass wir genügend Einnahmen generieren, <br>
um Kosten zu decken aber gleichzeitig die User nicht durch hohe Preise abschrecken.

Im Schnitt generiert man laut der aktuellen Studie nach 6 Monaten am Markt die ersten Umsätze und spätestens nach 12 Monaten die ersten Gewinne. <br>
Womit verdient man bei einer App sein Geld? „Viele glauben an Premium-Modelle, bei denen man für den App-Download bezahlt, oder an Banner-Werbung“. <br>
In Wahrheit wären das aber die zwei schlechtesten Formen: „Am besten verdient man mit Verkäufen innerhalb der App sowie an Kooperationspartnern und Sponsoren, <br>
die in der App kreativ mitbeworben werden.“ (Quelle: [deineseite.at](https://www.deineseite.at)).

Somit werden wir In-App-Käufe anbieten. Bei dieser Variante ist die Nutzung der App zunächst kostenlos. <br>
Einzelne Funktionen, Bereiche oder Pakete können durch In-App-Käufe freigeschaltet werden.
Uns ist bewusst, dass die Zielgruppe mit gewissen Einschränkungen unsere App nutzt und wir daher die Kaufoption so einfach als möglich gestalten möchten.
Die aktuelle Health-Studie des Innovationsdienstleisters Zühlke zeigt, dass Gesundheitsapps bei den befragten 1.000 Deutschen sehr beliebt sind: <br>
So nutzen fast 60 Prozent von ihnen Gesundheitstracker und -apps.

Geht es jedoch um die Zahlungsbereitschaft für eine umfangreiche Gesundheitsapp, die z. B. auch das Vereinbaren von Arztterminen, <br>
die Übermittlung von Untersuchungsergebnissen und die Überwachung persönlicher Gesundheitswerte beinhaltet, <br>
würde laut der Studie nur jeder Fünfte dafür mehr als zehn Euro monatlich bezahlen (Quelle. [devicemed.de](https://www.devicemed.de)).

Daher würden wir eine Standardvariante (kostenlos) und eine Premium-Variante (**für 3 Jahre EUR 49,90**) anbieten.

<br>

<img src="https://raw.githubusercontent.com/riosarah/MediKuh/main/pictures/financePic1.jpg" alt="drawing" width="800"/> <br>
<img src="https://raw.githubusercontent.com/riosarah/MediKuh/main/pictures/financePic2.jpg" alt="drawing" width="800"/> <br>
 
## Planung

### A. Zeitplan und Meilensteine
- Entwicklungsphasen: Unterteilung der App-Entwicklung in Phasen (z.B. Erstentwurf, Prototyping, Beta-Test, endgültige Veröffentlichung).
- Meilensteine: Festlegung spezifischer Ziele für jede Phase mit geschätzten Fertigstellungsterminen.
- Startzeitpunkt: 1.1.2024
- Geplantes Veröffentlichungsdatum: 1.4.2025

**3 Monate - Version 0.3**
- Datenbank für Medikamente vorweisen können – Datenspeicherstruktur anlegen
- Technisches Grundgerüst
- Erste Designpräsentation von UI
- Networking im Pharmasektor
- Anfrage an Sozialhilfswerke, sozialen Vereinen für Zusammenarbeit

**6 Monate Version 0.5**
- Spezifische Datenbankgruppen über App verknüpfen und zugreifen können.
- Mit Prototyp 0.5 – Investorensuche
- Miteinbeziehen und Zurateziehen von Stakeholdern

**9 Monate Version 0.7**
- Datensicherheit, Cloudspeicher
- Alphaversion
- Vertiefung der Zusammenarbeit mit Sozialhilfswerke

**12 Monate Betaversion**
- Erster Release am Markt – eingeschränkte Funktionen
- Kostenfreier Zugang für 3 Monate
- Anwerben von Testern

**15 Monate Release**
- Full release von MediKuh
 
### B. Ressourcenzuweisung
- Teamzusammensetzung: Darstellung der benötigten Rollen (z.B. Entwickler, Designer, Qualitätssicherungstester) und der Teamstruktur.
- Budget: Kostenschätzung für jede Phase, einschließlich Software, Hardware und Personal.
- Public Relations und Marketing - Ralph und Sarah
- Finanzierung und Monetarisierung, Kostenschätzung - Jürgen
- Projektmanagement - Ralph
- Design - Sarah 
- Kooperation mit der FH für soziale Berufe. (Praktika, Tester)
- Angebote von Consultingfirma einholen für Praxistests

 
### C. Technologie und Werkzeuge
- Entwicklungswerkzeuge: Spezifizierung der Software und Plattformen, die für die App-Entwicklung verwendet werden.
- Mit Framework Xamarin können wir mit C# sowohl für Android als auch iOS arbeiten.
- Datensicherung vorerst getrennt von öffentlich Datenbanken. – Sicherheitsrisiko;
- Details – siehe „Datensicherheit“.

 
### D. Benutzererfahrung und Design
- Benutzeroberfläche: Detaillierung des Designprozesses für die Benutzeroberfläche der App, mit Fokus auf Benutzerfreundlichkeit und Zugänglichkeit.
- Benutzertests: Planung von Benutzertestphasen, um Feedback zu sammeln und die App zu verbessern.
- Design mit Unterstützung von Frau Prof Rammelmüller.
 
### E. Marketing- und Startstrategie
- Marketingplan: Erstellung eines Plans zur Bewerbung der App, gezielt auf potenzielle Nutzer und Gesundheitsdienstleister.
- Anfänglich kostenloser Zugang
- Werbekampagne in Altenheimen
- Werbeflächen in Umgebung von Wagner Jauregg mieten
- Vertreter die unsere App an Psychiater anpreisen

 
### F. Risikomanagement und Notfallplanung
- Risikoidentifizierung: Auflistung potenzieller Risiken (z.B. technische Probleme, Budgetüberschreitungen) und deren Wahrscheinlichkeit.
- Notfallpläne: Entwicklung von Plänen zur Bewältigung dieser Risiken, falls sie eintreten.
- Finanzielle Überbrückung von Notsituationen über Fremdkapital von Bank
- Rückgreifen auf Startkapital, um Überleben aller Mitarbeiter sicherzustellen

### G. Rechtliche und Compliance-Überlegungen
- Datenschutz: Sicherstellung der Einhaltung von Datenschutzgesetzen (wie GDPR oder HIPAA) durch die App.
- Regulatorische Genehmigung: Planung zur Erlangung aller notwendigen Genehmigungen von gesundheitsrechtlichen Aufsichtsbehörden.
- Consulting im rechtlichen Bereich – Anwalt mit Spezialisierung Gesundheitsrechts wurde kontaktiert
 
### H. Langzeitunterstützung und Wartung
- Updates und Wartung: Planung regelmäßiger Updates und Wartungsarbeiten, um die App funktionsfähig und sicher zu halten.
- Feedback-Schleife: Einrichtung eines Systems zur Sammlung von Nutzerfeedback für kontinuierliche Verbesserungen.
- Dokumentieren von Zugriffen auf System.
- Patch Management, um Sicherheitslücken zu schließen.
 
### I. Bewertung und Metriken
- Erfolgs Metriken: Definition, wie der Erfolg der App gemessen wird (z.B. Anzahl der Nutzer, Nutzerzufriedenheit).
- Nachstart-Bewertung: Planung für regelmäßige Bewertungen der Leistung und Auswirkung der App.


