# User Profiles API
This project covers each stage of the data engineering pipeline, from data ingestion to processing to storage. The project uses a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra while everything is containerized using Docker for ease of deployment and scalability.


This project is designed with the following components:

**Data Source:** randomuser.me API was used to generate random user data for this data pipeline.
**Apache Airflow:** Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
**Apache Kafka and Zookeeper:** Used for streaming data from PostgreSQL to the processing engine (Apache Spark).
**Control Center and Schema Registry:** Helps in monitoring and schema management of Kafka streams.
**Apache Spark:** For data processing with master and worker nodes.
**Cassandra:** Where the processed data is ultimately stored.


**Resources:** Composed from tutorial ["Realtime Data Streaming"](https://www.youtube.com/watch?v=GqAcTrqKcrY) by Yusuf Ganiyu