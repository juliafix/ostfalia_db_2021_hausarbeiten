# 4 Fazit

Die Arbeit beschäftigt sich mit Open-Source-Datenbankmanagementsystemen für Zeitreihen, auch *Time Series Database* genannt. Drei Zeitreihendatenbanken wurden dabei beispielhaft für unterschiedliche Datenbankmodelle eingehender betrachtet: InfluxDB, GridDB und TimescaleDB. Jedes dieser Time Series DBMS vereint mehrere Datenbankmodelle. Während alle drei Zeitreihendatenbanken-Datenbankmanagementsysteme primär ein Time Series DBMS sind, unterscheiden sie sich in ihrem sekundären Ansatz des Datenbankmodells. Die mit Abstand populärste Time Series Database *InfluxDB* basiert sekundär auf dem Datenbankmodell des *Spatial DBMS*. *GridDB* verwendet als sekundäre Datenbankmodelle den *Key-Value Store* und das *relationale DBMS*. *TimescaleDB* ist als sekundäres Datenbankmodell ein relationales DBMS. 
Die drei Time Series DBMS wurden nach verschiedenen Kriterien analysiert und verglichen. Ein Vergleichskriterium war das Datenmodell. Das Datenmodell von *InfluxDB* verwendet *Tag-Sets* und basiert auf *Measurements*, die Tabellen sind und Messwerte enthalten. InfluxDB hat kein festes Schema. Dies ermöglicht eine große Flexibilität und verringert den administrativen Aufwand für das Einrichten einer relationalen Struktur. *GridDB* setzt dagegen auf das *Key-Container*-Datenmodell, wobei die *Container* entweder *Time Series* mit Zeitwerten als *Key* oder *Collections* mit beliebigen Werten als *Key* enthalten können. GridDB verbindet mit seinem Datenmodell die Vorteile von klassischen relationalen DBMSen und NoSQL-DBMSen. *TimescaleDB*  


Im Zeitalter von Big Data, dem Aufkommen des Internet der Dinge oder auch der Künstlichen Intelligenz wächst das Aufkommen von zeitindizierten Daten. Es gibt kaum noch Bereiche, die nicht auf die Verarbeitung von zeitbasierten Daten setzen und für die der Einsatz einer Zeitreihendatenbank einen Mehrwert liefern kann.

Zeitreihen-DBMS haben sich in den vergangenen Jahren zu einem der wichtigsten Datenbankmanagementsysteme entwickelt und sich durch eine spezielle Funktionsweise gegenüber anderen Datenbanken durchsetzen können. In dieser Arbeit werden diese Vorteile aufgegriffen und anhand ausgewählter Zeitreihendatenbanken detaillierter beschrieben.
Zu Beginn gibt die Arbeit einen Überblick über die notwendigen Grundlagen von Zeitreihendatenbanken. Durch die Erklärung von Big Data, dessen zunehmenden Aufkommen und der Zusammenhang zu leistungsstarken Datenbanken gibt eine Basis, welche Idee hinter der Struktur und dem Erfolg von Zeitreihendatenbanken steht. Anschließend folgt die Beschreibung erster Umsetzungen für die Verarbeitung von Zeitreihendaten sowie ein Überblick über den aktuellen Stand und unterschiedliche Einsatzbereiche von Zeitreihendatenbanken.
Neben Vorteilen wird außerdem auf auftretende Schwierigkeiten, die sich im Hinblick auf Big Data ergeben, hingewiesen.

Für den Vergleich werden die Zeitreihendatenbanken InfluxDB, GridDB und TimescaleDB nach zuvor definierten Kriterien analysiert.
Für die Auswahl dieser Datenbanken wurde sich auf das Ranking von DB Engine gestützt und sich für populäre Datenbanken entschieden, die sich in ihrer Funktionsweise voneinander unterscheiden [1.1.1]. Im Vordergrund des Vergleichs stehen Aspekte der Datenbankstruktur, die Partionierungsmechanismen, Replikationsmechanismen, unterstützte Programmiersprachen, APIs und andere Konzeptzugriffe, Einsatzbereiche sowie Vorteile, Besonderheiten und Nachteile.

unterschiedliche Lösungsansätze
<!--
 In the past, the focus of time-series databases has been narrowly on metrics and monitoring; today it’s become clear that software developers really need a true time-series database designed for a variety of operational workloads.
IoT

Conclusion
Now of course, each TSDB has its own unique set of pros and cons. Let’s briefly touch on them here:

InfluxDB

Pros: Easy to get up and running. Good performance for one node
Cons: No strict schema can be seen as a detriment. Only one node in open source.

TimeScaleDB

Pros: Full SQL, fast ingest, fixed schema
Cons: fixed schema

Note: I list “fixed schema” as both a pro and a con, because — like many things — it has many tradeoffs. If you want to hit the ground running and expand aggressively, a fixed schema can be a detriment. But if you are ok with planning out your schema and making sure all incoming data fits the schema, having ACID compliance can be worth the extra effort.

GridDB

Pros: very performant, fixed schema, scales out linearly
Cons: fixed schema
-->
