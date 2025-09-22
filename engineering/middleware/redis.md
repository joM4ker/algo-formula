# Redis

## PubSub和MQ的区别

1. PubSub的消息不持久化，消费者不在线就会被丢弃
2. PubSub无消费确认机制
3. PubSub只支持广播模型，不支持点对点模型（只有一个消费者接收到消息）

## 