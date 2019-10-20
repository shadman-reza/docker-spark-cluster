# Docker Spark

Docker images to:
* Setup a standalone [Apache Spark](https://spark.apache.org/) cluster

Dependencies
* OpenJDK [8-Alpine]

## Using Docker Compose

docker-compose up --scale spark-worker=[N] -d

where N is number of workers needed to run