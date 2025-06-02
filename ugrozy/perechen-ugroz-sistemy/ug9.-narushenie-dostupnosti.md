# УГ9. Нарушение доступности

### **Описание угрозы**

отказ сервисов из-за атак или отказа компонентов.

### **Задаваемые ценные ресурсы**

все сервисы (Django, БД, RabbitMQ).

### **Угрозы**

DoS, отказ оборудования.

### **Возможные сценарии**

флуда запросами к API, перегрев сервера.

### **Потенциальные последствия**

недоступность сервиса, убытки.

### **Меры по защите**

мониторинг, автоскейлинг, резервирование.

### **Связи**

[У1](../../uyazvimosti/perechen-uyazvimostei-sistemy/u1.-otsutstvie-izolyacii-virtualnykh-setei-vlan.md), [У3](../../uyazvimosti/perechen-uyazvimostei-sistemy/u3.-otsutstvie-monitoringa-temperatury-servera.md); [С2](../../scenarii-atak/perechen-scenariev-atak/s2.-dos-ataka-na-poisk-otelei.md)
