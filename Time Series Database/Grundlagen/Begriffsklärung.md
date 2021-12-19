# Begriffsklärung

Grundsätzlich können *Daten* (engl.: *data*) als Symbole verstanden werden, die außer *Zeichen* oder Zeichenfolgen unter anderem auch akustische Signale, Farben oder Bewegtbilder umfassen können. Werden Daten entsprechend einer Syntax miteinander kombiniert und zusammengefügt, entsteht zwischen den Daten ein Bezug in einem speziellen Kontext. Werden Daten auf diese Art um eine Bedeutung ergänzt, werden daraus *Informationen*. [1] 

Als *Big Data* können sehr große Datenmengen oder auch Massendaten bezeichnet werden, die mit hoher Geschwindigkeit aus verschiedensten Quellen gesammelt werden können. Diese Quellen können beispielsweise folgende sein: Social-Media-Plattformen, Sensordaten, Satellitenbilder, Audio- und Video-Streams, Banken- und Börsentransaktionsdaten oder Telemetriedaten von Kraftfahrzeugen [2]. Diese heterogenen Daten haben trotz ihres enormen Potenzials für sich genommen keinen Wert, solange sie nicht in einen Bedeutungskontext gebracht werden [3]. Aufgrund des großen Volumens können für die Verarbeitung und Analyse von Big Data keine klassischen Technologien oder konventionelle Hardware verwendet werden. Stattdessen werden *Big-Data-Technologien* eingesetzt, die sich durch besondere Eigenschaften auszeichnen. Die Hauptmerkmale sind *Volumn* (engl. für: *Volumen*), *Velocity* (engl. für: *Geschwindigkeit*) und *Variety* (engl. für: *Vielfalt*), auch kurz als *3 Vs* oder *VVV* bezeichnet. Darüber hinaus gibt es noch weitere Vs, von denen hier einige genannt, aber nicht näher beschrieben werden: *Veracity* (engl. für: *Echtheit*), *Validity* (engl. für: *Validität*), *Value* (engl. für: *Wert*), *Variability* (engl. für: *Veränderbarkeit*), *Venue* (engl. für: *Ort*), *Vocabulary* (engl. für: *Vokabular*), *Vague* (engl. für: *unspezifisch*). [2][4]
*Volumn* kennzeichnet diesbezüglich große Datenbestände, die im Terabyte- (Terabyte = 10^12 Byte) bis Yottabyte-Bereich (Yottabyte = 10^24 Byte) liegen. *Velocity* beschreibt die Geschwindigkeit, mit der Daten verarbeitet und analysiert werden können. Für Big-Data-Anwendungen erfordert dies beispielsweise die Möglichkeit, *Data Streams* in Echtzeit auswerten zu können. *Data Streams* (engl. für: *Datenströme* oder auch *Streaming-Daten*) sind kontinuierlich fließende digitale Daten, die in unterschiedlichen zeitlichen Abständen übertragen werden können und die chronologisch geordnet sind [5]. *Variety* steht für heterogene Daten, die in *strukturierter*, *semistrukturierter* und *unstrukturierter* Form vorliegen können. [2][4]

*Strukturierte Daten* sind in ihrer Ordnung stark vom Menschen geprägt. Sie lassen sich leicht in Tabellen ablegen und verändern sich aufgrund eines festgelegten Schemas in ihrer Struktur nur sehr langsam. *Semistrukturierte Daten* unterliegen keinem festen Schema, da sich Struktur und Inhalte der Datenobjekte kontinuierlich ändern können. Diese Datenobjekte können einerseits atomar mit einem spezifischen Datentyp sein oder sich aus mehreren Datenobjekten zusammensetzen. *Unstrukturierte Daten* weisen keine festen Strukturen auf und können Multimedia-Daten wie beispielsweise Text oder Bild-, Audio- und Video-Daten sein. [5]

An Big Data werden besondere Anforderungen gestellt, die mit klassischen relationalen Datenbanktechnologien kaum gelöst werden können. Große Datenmengen müssen schnell verarbeitet werden können. Da die Daten physisch verteilt vorliegen, müssen zudem Fragestellungen der Datenkonsistenz, Verfügbarkeit und Skalierbarkeit berücksichtigt werden. Um diese Anforderungen zu erfüllen, können *NoSQL-Technologien* eingesetzt werden. [4]

NoSQL
SQL

*Zeitreihendaten* oder auch *Zeitseriendaten* (engl.: *Time-Series Data*) sind Sammlungen von Werten, die zum Beispiel durch Messungen gewonnen werden und denen Zeitstempel zugeordnet sind. Diese Zeit-Werte-Zuweisungen werden in aufeinanderfolgenden Zeitintervallen erfasst und durch den festen zeitlichen Ablauf geordnet. Dadurch können Veränderungen der Merkmalsausprägungen von beobachteten Objekten über einen bestimmten Zeitraum beschrieben und auf dieser Basis tiefer gehend analysiert werden. [6][7][8]

*Zeitreihendatenbanken* (engl.: *Time-Series Database*, kurz: *TSDB*) sind darauf spezialisiert, den Umgang mit großen Mengen an Zeitreihendaten zu optimieren. Zeitreihendaten werden fortlaufend mit dem jeweils neuesten Zeitintervall gesammelt, in Zeitreihendatenbanken gespeichert und sind anschließend analysierbar [7]. 
Zeitreihendaten werden aufgrund ihrer zeitlichen Ordnung meist in einer vorgegebenen Reihenfolge erfasst. Durch die gemeinsame Unterbringung von Datenblöcken des gleichen Zeitbereichs im gleichen Datenbank-Cluster wird ein schnellerer Zugriff auf die Daten und damit eine effizientere Analyse ermöglicht. In Zeitreihendatenbanken sind häufig Funktionen integriert, die für die Analyse erforderlich sind. Sie nutzen beispielsweise Datenaufbewahrungsrichtlinien und unterstützen Bereichsabfragen. [9]

whatis.com


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
