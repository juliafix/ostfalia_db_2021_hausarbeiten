# 4 Fazit

Die Ausarbeitung hat sich mit dem Vergleich der TSDBs InfluxDB, GridDB und TimescaleDB beschäftigt. Die nachfolgenden Tabelle fasst die wichtigsten Vergleichsmerkmale zusammen:

| Vergleichsmerkmal                 | InfluxDB    | GridDB        | TimescaleDB |
| :---                              |    :---     |    :---       | :---        | 
| Datenmodell-/Struktur             | abc123      | 80            | Wide-Table- und Narrow-Tabel-Modelle    | 
| Partitionierungsmechanismen       | def456      | 90            | Zeitpartitionierung und Zeit- und Raum-Partitierung   |
| Replikationsmechanismen           | ghi789      | 120           | Streaming-Replikation      | 
| Unterstützte Programmiersprachen  | abc123      | 80            | .Net, C, C++, Delphi, Java info, JavaScript, Perl, PHP, Python, R, Ruby, Scheme, Tcl    | 
| APIs und andere Konzeptzugriffe   | def456      | 95            | ADO.NET, JDBC, Native C library, ODBC, Streaming API für große Objekte    | 
| Einsatzbereiche                   | ghi789      | 100           | Internet of Things, <br />Zeitreihen-Workloads    | 
| Vorteile                          | ghi789      | 100           | SQL-Unterstützung, <br />hohe Performance, <br />großer Datenumfang möglich, <br />JOINs möglich, <br />schnelle Verfügbarkeit,<br /> geringe Speicherkosten    | 
| Besonderheiten                    | ghi789      | 100           | Relationale Datenbank in Verbindung mit einer Zeitreihendatenbank    | 
| Nachteile                         | ghi789      | 100           | Für eine Speicherung geringer Datenmengen eher nicht geeignet, <br />Probleme mit geringen Kardinalitäten,<br /> Einschränkungen durch die Verwendung von Hypertabellen    | 

Tabelle 3.1: Vergleichstabelle InfluxDB, GridDB und TimescaleDB
