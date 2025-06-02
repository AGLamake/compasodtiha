# УГ8. Снижение целостности кэша

### **Описание угрозы**

Злоумышленник портит кэшированные данные.

### **Задаваемые ценные ресурсы**

Содержимое Redis.

### **Угрозы**

Подмена ключей, перезапись.

### **Возможные сценарии**

Доступ к Redis через нешифрованный канал ([У9](../../uyazvimosti/perechen-uyazvimostei-sistemy/u9.-otsutstvie-shifrovaniya-redis-trafika-net-tls.md)).

### **Потенциальные последствия**

Некорректные ответы пользователям, ошибочные рекомендации.

### **Меры по защите**

Включить TLS, авторизацию.

### **Связи**

[У9](../../uyazvimosti/perechen-uyazvimostei-sistemy/u9.-otsutstvie-shifrovaniya-redis-trafika-net-tls.md); [С4](../../scenarii-atak/perechen-scenariev-atak/s4.-perekhvat-i-modifikaciya-soobshenii-rabbitmq.md)
