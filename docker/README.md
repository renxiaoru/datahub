# Docker Images
The easiest way to bring up and test Data Hub is using Data Hub [Docker](https://www.docker.com) images 
which are continuously deployed to [Docker Hub](https://hub.docker.com/u/keremsahin) with every commit to repository.

* [**datahub-gms**](gms): [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/keremsahin/datahub-gms)](https://cloud.docker.com/repository/docker/keremsahin/datahub-gms/)
* [**datahub-frontend**](frontend): [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/keremsahin/datahub-frontend)](https://cloud.docker.com/repository/docker/keremsahin/datahub-frontend/)
* [**datahub-mce-consumer**](mce-consumer): [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/keremsahin/datahub-mce-consumer)](https://cloud.docker.com/repository/docker/keremsahin/datahub-mce-consumer/)
* [**datahub-mae-consumer**](mae-consumer): [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/keremsahin/datahub-mae-consumer)](https://cloud.docker.com/repository/docker/keremsahin/datahub-mae-consumer/)

Above Docker images are created for Data Hub specific use. You can check subdirectories to check how those images are
generated via [Dockerbuild](https://docs.docker.com/engine/reference/commandline/build/) files or 
how to start each container using [Docker Compose](https://docs.docker.com/compose/). Other than these, Data Hub depends
on below Docker images to be able to run:
* [**Kafka and Schema Registry**](kafka)
* [**Elasticsearch**](elasticsearch)
* [**MySQL**](mysql)

## Prerequisites
You need to install [docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/).

## Quickstart
If you want to quickly try and evaluate Data Hub by running all necessary Docker containers, you can check 
[Quickstart Guide](quickstart).