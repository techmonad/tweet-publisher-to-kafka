
About
-----

### Pre-Requisites for this project
#### Kafka Setup
i) [Download](http://kafka.apache.org/downloads.html) the Kafka-0.10.0.1 or latest version  and unzip it.

ii) Run the following command.
    Start zookeeper & Kafka:
    
         $ bin/zookeeper-server-start.sh config/zookeeper.properties 
         $ bin/kafka-server-start.sh config/server.properties
         
-----------------------------------------------------------------------
### Getting Started:
-----------------------------------------------------------------------

 Clone and run the code:

        $ git clone git@github.com:techmonad/tweet-publisher-to-kafka.git
        $ cd tweet-publisher-to-kafka
        $ env "twitter4j.oauth.consumerKey=*****************" bash
        $ env "twitter4j.oauth.consumerSecret=**************" bash
        $ env "twitter4j.oauth.accessToken=*****************" bash
        $ env "twitter4j.oauth.accessTokenSecret=***********" bash
        $ sbt run
