# kafka-wikimedia-springboot
Project for send and receive Wikimedia Content in realtime. Using Kafka as Message Broker and Mysql database.

<p align"center">
  <img src="https://snipboard.io/EV3x9o.jpg"/>
</p>


## Description of Project

Simple Example of Microservices with Kafka to produce and consume a large amount of Data. 

## Functionalities

:bell: Event-Driven Microservices using Spring boot and Kafka.

:bell: Message/Event Producer subscribed.

:bell: Message/Event Consumer subscribed.

:bell: MySql Database for store the data.


## Tools and technologies used:
  1. Java 17+

  2. Spring boot

  3. Spring Data Jpa

  4. Microservices

  5. Kafka

  6. Maven

  7. Mysql database

  8. IntelliJ IDEA


## Steps and Requirements to build and run the Project

**1. Clone the application.**
```bash
git clone https://github.com/SergioRuyDev/kafka-wikimedia-springboot.git
```
**2. Use the terminal to go inside of the folder kafka_2.13-3.3.1 and run in two diferents tabs, the commands below.**
```bash
bin/zookeeper-server-start.sh config/zookeeper.properties
bin/kafka-server-start.sh config/server.properties
```
**4. In Kafka-consumer-wikimedia project, edit the application.properties for your MySql Config Details.**
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/wikimedia
spring.datasource.username= your username
spring.datasource.password= your password
```

**4. In your prefered IDE run in sequence as a Java application the classes below.**
```bash
SpringBootProducerApplication
SpringBootConsumerApplication
```

