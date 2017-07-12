### Kafka REST

This is a place holder for all the confluent configurations needed to setup a single instance of kafka, zookeeper, kafka-rest and connector-s3

#### Kafka configs
[server.properties](https://github.com/dhawangayash/confluent_s3_rest_json_serialization/blob/master/server.properties)

#### Kafka-rest configs
[kafka-rest.properties]()

#### Connector S3 Configs
Connector for S3 in stand alone mode requires ```./bin/connect-standalone ./etc/kafka-connect-s3/worker.properties ./etc/kafka-connect-s3/quickstart-s3.properties ```

- [worker.properties](https://github.com/dhawangayash/confluent_s3_rest_json_serialization/blob/master/worker.properties)
- [quickstart-s3.properties](https://github.com/dhawangayash/confluent_s3_rest_json_serialization/blob/master/quickstart-s3.properties)