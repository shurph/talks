
- как мигрировать avro схемы?
  - поднимать нового консюмера, настроеного на новый топик, поднимать нового продюсера с новым топиком, гасить старого продюсера и ждать пока старый консюмер разгребет старый топик?
- как мигрировать avro схемы с **zero-downtime**?
  - никогда не удалять филды?
  - 

https://www.slideshare.net/ToddPalino/enterprise-kafka-kafka-as-a-service



Круиз контроль и контрольный канал: 
    
https://www.linkedin.com/pulse/in-depth-kafka-message-queue-principles-mukesh-kumar/
https://engineering.linkedin.com/blog/2017/08/open-sourcing-kafka-cruise-control
https://engineering.linkedin.com/blog/2019/02/introducing-kafka-cruise-control-frontend
https://habr.com/ru/post/332448/

https://github.com/prepor/clj-kafka/blob/master/src/ru/prepor/clj_kafka/elastic.clj

Масштабирование Кафки:
https://engineering.linkedin.com/kafka/running-kafka-scale



https://habr.com/ru/company/sberbank/blog/353608/


https://softwaremill.com/using-kafka-as-a-message-queue/


https://towardsdatascience.com/getting-started-with-apache-kafka-in-python-604b3250aa05

http://activisiongamescience.github.io/2016/06/15/Kafka-Client-Benchmarking/

https://blog.datasyndrome.com/a-tale-of-two-kafka-clients-c613efab49df

https://habr.com/ru/post/332448/

Философия
=========


http://pedlib.ru/Books/6/0343/6_0343-87.shtml

Предельные экзистенциальные беспокойства


Ялом (Yalom, 1980) выделил четыре предельных экзистенциальных беспокойства, они связаны со смертью, свободой, изоляцией и бессмысленностью. 

Свобода. Люди «обречены на свободу» (Sartre, 1956, р. 631). Люди живут не в хо рошо устроенной и структурированной Вселенной. Не существует никакой надежной основы, поддерживающей существование. Скорее, имеются недостаточно высокий уро вень структурированности и «отсутствие твердой земли под ногами», которые порож дают тревогу и страх. Свободные люди также обречены на ответственность. Они ответ ственны не только за придание миру значения (смысла), но и за свою жизнь, за свои действия и неудачи при совершении действий. Второй экзистенциальный конфликт — это конфликт между столкновением людей с отсутствием опоры и свободой и их стрем лением к обретению основы и структуры.
