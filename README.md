# springboot-kafka-wikimedia

This project demonstrates the use of spring boot and apache kafka. It helps to read a huge amount of real time stream data from wikimedia to the database. 
The kafka producer helps to read stream data from wikimedia, it writes the data to the kafka broker. The kafka consumer helps to consume the real time stream 
data from the broker and writes to the database.

## Tools and Technologies
- Programming Language: Java
- Runtime JDK 11
- Database: MySQL
- SQL Viewer or GUI: MySQL Workbench
- IDE: IntelliJ, Eclipse or Spring Tool Suite
- Lombok
- Apache Kafka
- Wikimedia stream data url: https://stream.wikimedia.org/v2/stream/recentchange
