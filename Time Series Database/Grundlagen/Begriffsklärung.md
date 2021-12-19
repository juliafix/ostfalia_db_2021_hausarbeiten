# Begriffsklärung

## Big Data
Grundsätzlich können *Daten* (engl.: *data*) als Symbole verstanden werden, die außer *Zeichen* oder Zeichenfolgen unter anderem auch akustische Signale, Farben oder Bewegtbilder umfassen können. Werden Daten entsprechend einer Syntax miteinander kombiniert und zusammengefügt, entsteht zwischen den Daten ein Bezug in einem speziellen Kontext. Werden Daten auf diese Art um eine Bedeutung ergänzt, werden daraus *Informationen*. [1] 

Als *Big Data* können sehr große Datenmengen oder auch Massendaten bezeichnet werden, die mit hoher Geschwindigkeit aus verschiedensten Quellen gesammelt werden können. Diese Quellen können beispielsweise folgende sein: Social-Media-Plattformen, Sensordaten, Satellitenbilder, Audio- und Video-Streams, Banken- und Börsentransaktionsdaten oder Telemetriedaten von Kraftfahrzeugen [2]. Diese heterogenen Daten haben trotz ihres enormen Potenzials für sich genommen keinen Wert, solange sie nicht in einen Bedeutungskontext gebracht werden [3]. Aufgrund des großen Volumens können für die Verarbeitung und Analyse von Big Data keine klassischen Technologien oder konventionelle Hardware verwendet werden. Stattdessen werden *Big-Data-Technologien* eingesetzt, die sich durch besondere Eigenschaften auszeichnen. Die Hauptmerkmale sind *Volumn* (engl. für: *Volumen*), *Velocity* (engl. für: *Geschwindigkeit*) und *Variety* (engl. für: *Vielfalt*), auch kurz als *3 Vs* oder *VVV* bezeichnet. Darüber hinaus gibt es noch weitere Vs, von denen hier einige genannt, aber nicht näher beschrieben werden: *Veracity* (engl. für: *Echtheit*), *Validity* (engl. für: *Validität*), *Value* (engl. für: *Wert*), *Variability* (engl. für: *Veränderbarkeit*), *Venue* (engl. für: *Ort*), *Vocabulary* (engl. für: *Vokabular*), *Vague* (engl. für: *unspezifisch*). [2][4]
*Volumn* kennzeichnet diesbezüglich große Datenbestände, die im Terabyte- (Terabyte = 10^12 Byte) bis Yottabyte-Bereich (Yottabyte = 10^24 Byte) liegen. *Velocity* beschreibt die Geschwindigkeit, mit der Daten verarbeitet und analysiert werden können. Für Big-Data-Anwendungen erfordert dies beispielsweise die Möglichkeit, *Data Streams* in Echtzeit auswerten zu können. *Data Streams* (engl. für: *Datenströme* oder auch *Streaming-Daten*) sind kontinuierlich fließende digitale Daten, die in unterschiedlichen zeitlichen Abständen übertragen werden können und die chronologisch geordnet sind [5]. *Variety* steht für heterogene Daten, die in *strukturierter*, *semistrukturierter* und *unstrukturierter* Form vorliegen können. [2][4]

*Strukturierte Daten* sind in ihrer Ordnung stark vom Menschen geprägt. Sie lassen sich leicht in Tabellen ablegen und verändern sich aufgrund eines festgelegten Schemas in ihrer Struktur nur sehr langsam. *Semistrukturierte Daten* unterliegen keinem festen Schema, da sich Struktur und Inhalte der Datenobjekte kontinuierlich ändern können. Diese Datenobjekte können einerseits atomar mit einem spezifischen Datentyp sein oder sich aus mehreren Datenobjekten zusammensetzen. *Unstrukturierte Daten* weisen keine festen Strukturen auf und können Multimedia-Daten wie beispielsweise Text oder Bild-, Audio- und Video-Daten sein. [5]

An Big Data werden besondere Anforderungen gestellt, die mit klassischen relationalen Datenbanktechnologien kaum gelöst werden können. Große Datenmengen müssen schnell verarbeitet werden können. Da die Daten physisch verteilt vorliegen, müssen zudem Fragestellungen der Datenkonsistenz, Verfügbarkeit und Skalierbarkeit berücksichtigt werden. Um diese Anforderungen zu erfüllen, können *NoSQL-Technologien* eingesetzt werden. [4]

## SQL und NoSQL
*NoSQL-Technologien* sind Datenbanksysteme, die eine Alternative zu klassischen *relationalen Datenbankmanagementsystemen* (*RDBMS*, kurz für: *Relational Database Management System*) darstellen, bei denen für die Erstellung, Pflege und Administration von strukturierten Daten zumeist *SQL* (kurz für: *Structured Query Language*) eingesetzt wird. In relationalen Datenbanken stehen die Daten in definierten Beziehungen zueinander und werden in Tabellen abgelegt. 
*NoSQL* wird in den meisten Fällen als *Not only SQL* bezeichnet, allerdings oft als nichtrelationaler (engl.: *nonrelational*) Ansatz verstanden. NoSQL-Datenbankmanagementsysteme sind nicht fest an strukturierte Daten und damit an kein festes Schema gebunden. Eine Architektur, die NoSQL-Technologien einsetzt, unterstützt verteilte Systeme, Daten-Replikation und horizontales Skalieren. NoSQL-Datenbankmanagementsysteme folgen dem *CAP-Theorem* (kurz für: *consistency*, *availability*, *partition tolerance*). *Consistency* (engl. für: *Konsistenz*) in einem verteilten System bedeutet, dass nach Durchführung einer Operation die Aktualisierung aller Replikate des geänderten Datensatzes sichergestellt sein muss. *Availability* (engl. für: *Verfügbarkeit*) bezieht sich auf die Verfügbarkeit eines Gesamtsystems und akzeptable Antwortzeiten. *Partition tolerance* (engl. für: *Ausfalltoleranz*) besagt, dass der Ausfall einzelner Knoten oder deren Verbindung untereinander nicht die Stabilität eines Gesamtsystems beeinträchtigt. Bei dem CAP-Theorem müssen mindestens zwei der drei Eigenschaften gegeben sein.  [5]
Die Kerntechnologien von NoSQL-Datenbanksystemen sind  
- *Key Value Stores* (auch *Key Value Database*, engl. für: Schlüssel-Werte-Datenbank)  
- *Column Stores* (engl. für: *spaltenorientierte Datenbank*)
- *Document Stores* (auch *Document Database*, engl. für: *Dokumenten-Datenbank*)
- *Graph Databases* (engl. für: *Graphdatenbank*).

Sowohl SQL-basierte als auch NoSQL-basierte Datenbankmodelle haben jeweils ihre Vorteile und Nachteile. Je nach Einsatzbereichen und den damit verbundenen Anforderungen können verschiedene Datenmodelle innerhalb einer Anwendung kombiniert werden. 

## Time Series DBMS - Zeitreihen-Datenbankmanagementsysteme

*Zeitreihendaten* oder auch *Zeitseriendaten* (engl.: *Time-Series Data*) sind Sammlungen von Werten, die zum Beispiel durch Messungen gewonnen werden und denen Zeitstempel zugeordnet sind. Diese Zeit-Werte-Zuweisungen werden in aufeinanderfolgenden Zeitintervallen erfasst und durch den festen zeitlichen Ablauf geordnet. Dadurch können Veränderungen der Merkmalsausprägungen von beobachteten Objekten über einen bestimmten Zeitraum beschrieben und auf dieser Basis tiefer gehend analysiert werden. Da Änderungen in Zeitreihendaten oft nicht überschrieben sondern neu eingefügt werden, kann eine Historie der Daten abgebildet werden. [6][7][8]

*Time Series DBMS* (engl. für: *Zeitreihen-Datenbankmanagementsystem*) sind darauf spezialisiert, den Umgang mit großen Mengen an Zeitreihendaten zu optimieren. Zeitreihendaten werden fortlaufend mit dem jeweils neuesten Zeitintervall gesammelt, in Zeitreihendatenbanken gespeichert und sind anschließend analysierbar [7]. 
Zeitreihendaten werden aufgrund ihrer zeitlichen Ordnung meist in einer vorgegebenen Reihenfolge erfasst. Zeitintervalle, in den Daten erfasst werden, können von Time Series DBMS komprimiert werden. Durch die gemeinsame Unterbringung von Datenblöcken des gleichen Zeitbereichs im gleichen Datenbank-Cluster wird ein schnellerer Zugriff auf die Daten und damit eine effizientere Analyse ermöglicht. Die schnelle Datenabfrage wird durch die Aufteilung in feste und dynamische Daten erleichtert. In Time Series DBMS sind häufig Funktionen integriert, die für die Analyse erforderlich sind. Sie nutzen beispielsweise Datenaufbewahrungsrichtlinien und unterstützen Bereichsabfragen. Die Suche kann nach einem Ereigniszeitraum oder -zeitpunkt erfolgen. Time Series DBMS sind benutzerfreundlich, können ein großes Datenvolumen organisieren, bieten hohe Schreibraten, eine spezifische Suche nach Daten und eine sehr gute Abfrageleistung. Dies ermöglicht das Streaming und die Analyse von Daten in Echtzeit. [8][9]

Um einen effizienten Umgang mit den riesigen Datenmengen bewältigen zu können, müssen Datenbankmanagementsysteme entsprechend skalieren können, einhergehend mit der Distribution über mehrere Knoten. Mit Operationen und Transaktionen in geringem Umfang versuchen skalierbare RDBMS eine bessere Skalierbarkeit und höhere Leistung zu erreichen als bei klassischen RDBMS. Für spezielle Anwendungsfälle können demnach RDBMS für Zeitreihendaten eingesetzt werden. NoSQL-DBMS bieten bereits Lösungen für die Verteilung der Daten, mit zwangsläufig schwächeren Relationen der Daten untereinander und nachlassender Konsistenz. Sie sind in der Lage, sehr große Mengen von Zeitreihendaten in sehr kurzer Zeit zu speichern und Abfrge-Operationen auf ihnen durchzuführen. Die Grenzen zwischen NoSQL-DBMS und Time Series DBMS sind daher fließend. [10]

Im Time Series DBMS können teilweise folgende Funktionen bieten:  
- *Einfügen* (engl.: *Insertion*)
- *Aktualisierung* (engl.: *Updating*)
- *Lesen* (engl.: *Reading*)
- *Durchsuchen* (engl.: *Scanning*)
- *Durchschnittsberechnung* (engl.: *Averaging*)
- *Zusammenfassung* (engl.: *Summarization*)
- *Zählung* (engl.: *Counting*)
- *Löschung* (engl.: *Deletion*)
- *Maximierung* (engl.: *Maximization*)
- *Minimierung* (engl.: *Minimization*) [10]

Beim *Einfügen* einer *Row* (engl. für: *Zeile*) von Zeitreihendaten wird der TSDB ein Eintrag mit einem Zeitstempel und einem dazugehörigen Wert und optional einem *Row-Key* (auch: *Tag Name*) weiteren Werten hinzufügt. Mehrere Zeitreihen können in einer TSDB gespeichert werden, wobei eine Zeitreihe aus einem Namen und mehreren Rows von Zeitreihendaten besteht. Eine Zeitreihe kann für die Gruppierung von Zeitreihendaten auf höherer Ebene verwendet werden. Ein Zeitstempel symbolisiert einen bestimmten Zeitpunktund wird oft mit einer Genauigkeit von Millisekunden angegeben. Der Abstand zwischen zwei Zeitstempeln gibt Aufschluss über die Detailgenauigkeit, mit der Zeitreihendaten gespeichert werden können. Die Granularität der Speicherung von Daten und die Granularität der Abfrage der Daten können unterschiedlich sein. Eine Zeitspanne ist der zeitliche Abstand zwischen zwei Zeitstempeln. Beim Aktualisieren werden eine oder mehrere Rows mit einem konkreten Zeitstempel geändert. Das Lesen und das Löschen erfolgen jeweils für eine oder mehrere Rows mit einem bestimmten Zeistempel oder für die kleinstmögliche Zeitspanne. Das Durchsuchen erfolgt für eine oder mehrere Rows einer bestimmten Zeitspanne. Mit Hilfe der Aggregtionsfunktionen *Durchschnittsberechnung*, *Zusammenfassung*, *Zählung*, *Maximierung* und *Minimierung* können Daten nach bestimmten Kriterien angesammelt werden. Die Ergebnisse einer solchen Abfrage, gruppiert für bestimmte Zeitspannen, werden auch als *Buckets* (engl. für: Behälter) bezeichnet. Der Durchschnitt kann für mehrere Werte einer bestimmten Zeitspanne berechnet werden. Die Zusammenfassung von Zeitreihendaten ebenso wie die Suche nach den Maximal- und Minimalwerten beziehen sich ebenfalls auf eine festgelegte Zeitspanne. [10]

An Time Series DBMS werden zusätzlich zu den oben genannten Funktionen noch weitere Anforderungen gestellt. Diese können wie die Funktionen als Vergleichskriterien für den Vergleich von Time Series DBMS herangezogen werden. Einige werden im Folgenden erläutert.  
Hochverfügbarkeit (engl.: high availability, kurz: HA) sagt etwas darüber aus, wie viel Prozent der Zeit ein System ohne Ausfall arbeitet. Das Bundesamt für Sicherheit in der Informationstechnik gibt verschiedene Verfügbarkeitsklassen an. Eine Hochverfügbarkeit entspricht danach der Verfügbarkeitsklasse 3 mit einer Mindestverfügbarkeit von 99,99%. Dies entspricht einer Ausfallzeit von höchstens fünf Minuten in einem Monat und einer Ausfallzeit von höchstens 53 Minuten in einem Jahr. [11]  
Wenn ein System hochverfügbar ist, besteht die Möglichkeit, dass unerwartete Knotenausfälle und 

HA gives the possibility to compensate unexpected node failures and network partitioning. To compensate means that a query must be answered under the mentioned circumstances, but it is not expected that the given answer is always consistent. It is expected that the DBMS uses eventual consistency at least, but since some time series databases do not give any explicit consistency guarantee or depend on DBMS that have configurable consistency guarantees, consistency levels are not further considered. It is also expected that a client needs to know more than one entry point (e. g., IP address) to compensate a node failure of an entry node.


scalability
Horizontales und vertikales Skalieren

load balancing

Tags, Continuous Calculation, Long-term Storage, and Matrix Time Series

Granularity

Interfaces and Extensibility



## Literaturverzeichnis

[1] K. North, Wissensorientierte Unternehmensführung: Wissensmanagement im digitalen Wandel, 7. Aufl. Wiesbaden: Springer Gabler, 2021.

[2] U. Dulhare, K. Ahmad und K. Bin Ahmad, Machine Learning and Big Data: Concepts, Algorithms, Tools and Applications, 1. Aufl. Erscheinungsort nicht ermittelbar, Boston, MA: Wiley-Scrivener; Safari, 2020.

[3] R. Bhatnagar, „Unleashing Machine Learning onto Big Data: Issues, Challenges and Trends“ in Studies in Computational Intelligence Ser, v.801, Machine Learning Paradigms, A. E. Hassanien, Hg., Cham: Springer International Publishing AG, 2019.

[4] D. Fasel und A. Meier, Big data: Grundlagen, Systeme und Nutzungspotenziale. Wiesbaden: Springer Vieweg, 2016.

[5] A. Meier und M. Kaufmann, SQL & NoSQL Databases: Models, languages, consistency options and architectures for Big Data Management. Wiesbaden, Heidelberg: Springer Vieweg, 2019.

[6] S. Fangman, „The Time Has Come for a New Type of Database - DataDrivenInvestor“, DataDrivenInvestor, 28. Jan. 2019, 2019. [Online]. Verfügbar unter: https://medium.datadriveninvestor.com/the-time-has-come-for-a-new-type-of-database-47cf8df1667a. Zugriff am: 10. November 2021.

[7] T. Joos, „Zeitreihendatenbanken für das Speichern von Messdaten“, BigData-Insider, 9. Juli 2021, 2021. [Online]. Verfügbar unter: https://www.bigdata-insider.de/zeitreihendatenbanken-fuer-das-speichern-von-messdaten-a-1034400/. Zugriff am: 17. November 2021.

[8] Whatis.com/de, Zeitreihendatenbank (Time Series Database, TSDB). [Online]. Verfügbar unter: https://whatis.techtarget.com/de/definition/Zeitreihendatenbank-Time-Series-Database-TSDB (Zugriff am: 17. November 2021).

[9] M. Fadhel, E. Sekerinski und S. Yao, „A Comparison of Time Series Databases for Storing Water Quality Data“ in Mobile Technologies and Applications for the Internet of Things: Proceedings of the 12th IMCL Conference, Cham, 2019. 

[10] A. Bader, O. Kopp und M. Falkenthal, „Survey and Comparison of Open Source Time Series Databases“ (en), 1617-5468, 2017. [Online]. Verfügbar unter: https://dl.gi.de/handle/20.500.12116/922;jsessionid=E7C67433B85AD0167BC17657C2EA23D9

[11] BSI, „Band G: Kapitel 2: Definitionen“ in HV-Kompendium V 1.6, Bundesamt für Sicherheit in der Informationstechnik, Hg., 2013.
