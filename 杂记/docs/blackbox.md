## BlackBox 260724 需求

### 代码解读

实际上需要修改的是消息的 Key

`kafkaProducerService.sendSimpleMessage(topic, objectMapper.writeValueAsString(message));`

1. 确认`ImageLibraryUpdateKafkaMessage`包含电芯维度字段（确认是否是 `cellCode`）
2. 修改 `message.setPor`



## 补充

**DTO （Data Transfer Object，数据传输对象）**：在 Java 中是一个普通 Java 对象，里面只包含私有属性字段，以及公用的 Getter 和 Setter 方法