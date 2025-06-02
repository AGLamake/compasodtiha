# УГ4. Компрометация хранилищ данных (НСД к конкретной части)

### **Описание угрозы**

Несанкционированный доступ или изменение в БД/Redis.

### **Задаваемые ценные ресурсы**

PostgreSQL-таблицы, кэш Redis.

### **Угрозы**

SQL-инъекции, утечка учётных данных, отсутствует шифрование.

### **Возможные сценарии**

Использование уязвимости У4 для чтения дампов.

### **Потенциальные последствия**

Раскрытие персональных данных, утрата целостности.

### **Меры по защите**

Шифрование бэкапов, ограничение прав, применение патчей.

### **Связи**

[У4](../../uyazvimosti/perechen-uyazvimostei-sistemy/u4.-otsutstvie-proverki-celostnosti-dannykh-ot-agentov.md), [У9](../../uyazvimosti/perechen-uyazvimostei-sistemy/u9.-otsutstvie-shifrovaniya-redis-trafika-net-tls.md), [У8](../../uyazvimosti/perechen-uyazvimostei-sistemy/u8.-ustarevshie-biblioteki-django-less-than-4.2-pakety-ml-bez-patchei.md); [С1](../../scenarii-atak/perechen-scenariev-atak/s1.-sql-inekciya-dlya-eksfiltracii-polzovatelskikh-dannykh.md), [С8](../../scenarii-atak/perechen-scenariev-atak/s8.-utechka-polzovatelskikh-dannykh-cherez-neprozrachnyi-bekap.md)
