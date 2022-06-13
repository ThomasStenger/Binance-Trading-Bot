# Binance-Trading-Bot
Another project I worked on during my studies together with a work group. 

We wanted to explore how different crypto-curriences are correlated during bull & bear cycles. 
Identifying this relationship early enough in the cycle might help to define a trading strategy. 
Using trading data provided by Binance we set up a trading bot that acts on these correlations identified.

The project entails following phases of the big data value chain:
1) Sources - Binance Batch and Streaming Data
2) Ingestion - Rest API Call for Batch and Binance Producer for Streaming
3) Storage - Hadoop HDFS for Batch and Apache Kafka for Streaming
4) Processing - Apache Spark 
5) Serving - MariaDB
