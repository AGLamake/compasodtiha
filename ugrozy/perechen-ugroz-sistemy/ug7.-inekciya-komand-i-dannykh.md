# УГ7. Инъекция команд и данных

### **Описание угрозы**

Выполнение неподготовленных команд на сервере и БД.

### **Задаваемые ценные ресурсы**

Система, интерпретатор команд, БД.

### **Угрозы**

SQLi, оболочечные инъекции.

### **Возможные сценарии**

SQL-инъекция в фильтрах поиска.

### **Потенциальные последствия**

Полное захват системы, эксфильтрация данных.

### **Меры по защите**

Подготовленные выражения, санитайзинг, WAF.

### **Связи**

[У5](../../uyazvimosti/perechen-uyazvimostei-sistemy/u5.-otsutstvie-zagolovka-x-content-type-options.md), [У8](../../uyazvimosti/perechen-uyazvimostei-sistemy/u8.-ustarevshie-biblioteki-django-less-than-4.2-pakety-ml-bez-patchei.md); [С1](../../scenarii-atak/perechen-scenariev-atak/s1.-sql-inekciya-dlya-eksfiltracii-polzovatelskikh-dannykh.md)
