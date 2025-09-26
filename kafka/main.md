# 01.왜 Kafka를 공부를 시작했는가?

> 보상 트랜잭션을 구현하기 위해서(정확히는 Coreography SAGA을 구현하기 위해)
> DDD 이론을 배우다가 Aggregate를 나누는 기준 중 하나가 Event라는 말을 듣고 EDA -> Message/queue로 넘어가서(?) 기억이 가물가물함

일단, Kafka를 이용해서 보상 트랜잭션을 구현하는 것이 목적임

# 02. 준비물(지식) / 진행과정

-   Kafka Broker

    -   Design
    -   Opeartion
    -   Security

-   Zookeeper 또는 KRatf Mode로 동작하는 Controller

-   Kafka Client API<Node.js의 경우 KafkaJS>

    -   Outbox 패턴 구현
    -   EoS 구현

-   Kafka Connect API

    -   학습중...

-   Kafka Streams<일단 보류>
