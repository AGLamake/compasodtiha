# УГ2. Нарушение авторизации на уровне объектов

### **Описание угрозы**

Доступ к чужим записям (отели, бронирования).

### **Задаваемые ценные ресурсы**

Записи БД, конфиденциальные отзывы.

### **Угрозы**

Отсутствие проверки прав (логика авторизации сломана).

### **Возможные сценарии**

Прямой доступ к ID чужих записей через API.

### **Потенциальные последствия**

Утрата доверия пользователей, GDPR-штрафы.

### **Меры по защите**

Внедрение Object-Level Permissions, тесты.

### **Связи**

[У5](../../uyazvimosti/perechen-uyazvimostei-sistemy/u5.-otsutstvie-zagolovka-x-content-type-options.md), [У8](../../uyazvimosti/perechen-uyazvimostei-sistemy/u8.-ustarevshie-biblioteki-django-less-than-4.2-pakety-ml-bez-patchei.md); [С1](../../scenarii-atak/perechen-scenariev-atak/s1.-sql-inekciya-dlya-eksfiltracii-polzovatelskikh-dannykh.md)
