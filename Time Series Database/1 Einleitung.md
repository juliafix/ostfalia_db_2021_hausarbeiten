# 1 Einleitung

Im Zeitalter von Big Data, dem Aufkommen des Internet der Dinge oder auch der Künstlichen Intelligenz wächst das Aufkommen von zeitindexierten <!-- "zeitindizierten" --> Daten. 
Es gibt kaum noch Bereiche, die nicht auf die Verarbeitung von zeitbasierten Daten setzen und für die der Einsatz einer Zeitreihendatenbank einen Mehrwert liefern kann.  

Zeitreihendatenbanken <!-- "Zeitreihen-DBMS", weil hier mit anderen DBMS verglichen wird --> haben sich in den vergangenen Jahren zu einer <!-- "einem" --> der wichtigsten Datenbankmanagementsystemen <!-- "Datenbankmanagementsysteme" --> hochgearbeitet <!-- "entwickelt" klingt hier echt besser ;) --> und sich durch eine spezielle Funktionsweise gegenüber anderen Datenbanken durchsetzten <!-- "durchsetzen" --> können. 
In dieser Arbeit werden diese Vorteile aufgegriffen und anhand ausgewählter Zeitreihendatenbanken detaillierter beschrieben.  
Zu Beginn gibt die Arbeit einen Überblick über die notwendigen Grundlagen von Zeitreihendatenbanken. So zum Beispiel das Aufkommen von Big Data, welches auch als Basis für die Idee hinter der Struktur von Zeitreihendatenbanken verstanden werden kann. <!-- der letzte Teilsatz klingt ein wenig durcheinander gewürfelt; vllt. könnte er noch umformuliert werden? -->
Anschließend folgt die Beschreibung erster Ideen für die Verarbeitung von Zeitreihendaten sowie ein Überblick über den aktuellen Stand und unterschiedliche Einsatzbereiche von Zeitreihendatenbanken.  
Neben Vorteilen wird außerdem auf auftretende Schwierigkeiten, die sich im Hinblick auf Big Data ergeben, hingewiesen. 

Für den Vergleich werden die Zeitreihendatenbanken InfluxDB, GridDB und TimescaleDB nach zuvor definierten Kriterien analysiert.   
Für die Auswahl dieser Datenbanken wurde sich auf das Ranking von DB Engine gestützt und sich für populäre Datenbanken entschieden, die sich in ihrer Funktionsweise voneinander unterscheiden [1.1.1].
Im Vordergrund des Vergleichs stehen Aspekten <!-- "Aspekte" --> der Datenbankstruktur, die Partionierungsmechanismen, Replikationsmechanismen, unterstützte Programmiersprachen, APIs und andere Konzeptzugriffe, Einsatzbereiche sowie Vorteile, Besonderheiten und Nachteile.   
Zuletzt ist anzumerken, dass sich dieser Vergleich ausschließlich auf funktionale Kriterien stützt und nicht-funktionale Kriterien nicht betrachtet werden. <!-- das stimmt so leider nicht, wir betrachten ja insbesondere nichtfunktionale Kriterien; den Satz würde ich eigentlich besser wegnehmen -->
