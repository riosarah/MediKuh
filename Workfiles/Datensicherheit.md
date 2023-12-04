## Datensicherheit

Wir streben an unsere App auf verschiedenen Betriebssystemen laufen lassen zu können. Die dafür geltenden Datenbestimmung werden wir für unser Programm selbstverständlich umsetzen. Da unser System mit medizinisch heiklen Daten arbeitet, die als besonders schützenswerte Daten deklariert sind, 
muss darauf besonderes Augenmerk gelegt werden. So ist neben der eigentlichen Appentwicklung
der Datenschutz eines unserer wichtigsten Schwerpunkte.
Unsere App soll zu Beginn mit minimalen Standardberechtigungen funktionieren, um Sicherheitsentscheidungen zu vereinfachen.

Mit einem auf die Sicherheitsbestimmungen angepassten Anwendungsframework, stellen wir sicher, dass wir die Daten so verschlüsseln, dass andere Applikationen nicht darauf zugreifen können. Es schränkt auch die Berechtigungen und Zugriffe anderer Programme auf unsere internen Daten auf den Mobilgeräten ein.

Wir verwenden Pseudonymisierung für die Verschlüsselung unserer Daten. Daten werden außerhalb des Endnutzergeräts nur verschlüsselt gespeichert, so dass diese selbst bei einem Datenleak nicht den Benutzern zugeordnet werden können. 

Um ein gültiges Verzeichnis der erfassten Einwilligungen speichern und sicher verwahren zu können, benötigt unsere App einen Netzwerkzugang, und einen Cloudspeicher mit hochgradiger Datenverschlüsselung. Hierbei werden alle Personenbezogenen Daten nur Identifikationsnummern für die heruntergeladene Applikation zugeordnet. So soll das Risiko von medizinischem Profiling über unsere Datenbank verringert werden.

Regelmäßige Risikoanalyse unserer Technischen Sicherheit. 
Patch Managemen tum Sicherheitslücken zu schließen. Ablauf und Prozeder wird im 6-Monatsupdate festgehalten.



Lokaler Datenspeicher:
Aktualisieren des internen Speichers der App auf dem Endnutzergerät in regelnmäßigen Abständen
Externe Daten können nur aus von uns genehmigen Quellen in das Programm geladen werden.
Wir nutzen Systeme, wie Adress Space Layout Randomization (ASLR) und No-Execute (NX)um Speicherverwaltungsfehler zu reduzieren.
In der Beta-version soll unser Programm nur auf oberflächliche Daten wie Datum, Uhrzeit am Handy zugreifen. 
Es darf Benachrichtigungen senden. Zugriffe auf Kamera - Fotos sollen nicht gespeichert werden.


