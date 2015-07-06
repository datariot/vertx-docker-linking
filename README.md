# vertx-docker-example
Send / Receive with Docker and Vert-x

This example uses docker-compose.

perform a ```mvn package docker:build``` for each of the sub-modules.

```docker-compose up``` will bring up each verticle.

```docker logs [name]``` will show the log of the verticle. The reciever should start receiving "news".