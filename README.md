# event-identification
Event Identification is a streaming application which identify event of intereset from stream using configurations.

1.Producer will produce events to kafka. this may be streaming application or single kafka producer.
2.Spark streaming will read events from kafka and identify event of interest using configurations.
3.Identified events can be published to another kafka topic for enrichment/correlations/notification purpose or saved to permanent storage.

4. Configurations will be in RDBMS-MySQL which can be updated any time or stream application can use them from current/next batch after cache refresh in streaming application.
