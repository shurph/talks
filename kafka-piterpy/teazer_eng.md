Date: 2019-10-17

# Title

Building a microservices-based application using Kafka and Django


# About speaker

Nikolay worked with a lot of apps and projects during the Software Engineer career. He had a chance to start new ones, to complete good ones, to carry about and to abandon legacy ones. And there were a lot of chances to transfer monolithic apps to a microservice architecture. It's not only about Python-only applications but about quite heterogeneous applications, too. ‘Heterogeneous’ not only in terms of programming languages but in terms of a whole technology stack in general. During these funny adventures, Nikolay had to deal with various approaches and solutions. Some of these solutions (and decisions, so) made an indelible impression on Nikolay and on the teams in which he worked.

Now Nikolay seeks to share his happiness and pain about those discoveries and studies.


# Abstracts

Everything is glorious, beautiful, and carefree when your app has to face only with a listless trickle of data from the outside world.
But we all know that the world around is unpredictable. Requirements are changing unprecedentedly and dramatically.

Once you may face a fact that business requires a lot from your tiny-and-beauty app. Might these be requirements for fault tolerance or for performance? Might it be some requirement for a data bandwidth? Who knows?

After all, a business might promise your a hug waterfall of data!

All these challenges can be addressed in different ways. In our case we choose Kafka. And Kafka is promising us that it can process up to 2 million records per second.

So, we tried to painlessly inject Kafka technologies into a project based on Django microservices. Kafka is used here as a data exchange bus. It might help us to cope with the emerging whirlpool of microservice hell.  Especially we hope to this approach because we already added in our environment a few services made using aiohttp, Golang, and some other tech. Hope Kafka can handle the distribution of data brooks between these ‘a-little-bit-heterogenous’ microservices.

In the end, when you have Kafka in your hands, everything around you looks like a stream.


TAGS: Microservices, Apache Kafka, Django, Avro, Confluent Schema Registry, Kafka Connectors, Debezium, PostgreSQL, Kafka Streams, confluent-kafka, python-kafka, pykafka, aiokafka.

