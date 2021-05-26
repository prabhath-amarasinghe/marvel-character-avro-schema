# marvel-character-schema
Apache avro schema to publish and subscribe to receive bio of all Marvel characters

The project uses avro-maven-plugin to generate code and kafka-schema-registry-maven-plugin to register a schema on confluent.

*Please note*
For this project I am running confluent on a docker conatainer locally. More info on how to this can be found at https://docs.confluent.io/5.5.0/quickstart/ce-docker-quickstart.html

If you do not change an defaults this should work as it is. 

In this project I am using this schema to emit (marvel-chaacter-broker) and receive (marvel-character-receiver) info marvel character info.
