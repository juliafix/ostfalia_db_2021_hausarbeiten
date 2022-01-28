# 4 Fazit

Die Ausarbeitung hat sich mit dem Vergleich der TSDBs InfluxDB, GridDB und TimescaleDB beschäftigt. 

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
