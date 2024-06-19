**Commands to Execute**

This project creates infrastructure for the flink e-commerce use-case.
The Docker compose contains the following ::
- Kafka
- Postgres
- Elastic Search

The Python job _main.py_ generates events and ingests into kafka

_Pre-Requisite_

- Python 3
- Docker Desktop
- Any IDE (PyCharm or vscode)

_Docker_
- docker compose up -d

_Python_ 
- pip install faker
- pip install simplejson
- pip install confluent_kafka

_Kafka_
- broker port is 9092
- kafka-topics --list --bootstrap-server broker:9092
- _test ingestion on kafka #_>
  kafka-console-consumer --topic financial_transactions --bootstrap-server broker:9092

_Postgres_
- psql -U postgres (password:: postgres)
- \l to list tables

_Elastic Search_
- will be available on port 5601




