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





