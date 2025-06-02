# УГ5. Межсайтовые запросы с сервера

### **Описание угрозы**

Злоупотребление открытым URL-парсером для доступа к внутренним ресурсам.

### **Задаваемые ценные ресурсы**

Внутренние сервисы (Prometheus, метрики).

### **Угрозы**

Обход межсетевых экранов, утечка конфигурации.

### **Возможные сценарии**

SSRF из модуля агрегации (К05).

### **Потенциальные последствия**

Разведка сети, подготовка к дальнейшим атакам.

### **Меры по защите**

Валидация URL, блокировка внутренних диапазонов.

### **Связи**

[У4](../../uyazvimosti/perechen-uyazvimostei-sistemy/u4.-otsutstvie-proverki-celostnosti-dannykh-ot-agentov.md); [С3](../../scenarii-atak/perechen-scenariev-atak/s3.-ssrf-dlya-skanirovaniya-vnutrennei-seti.md); [К04](../../struktura-sistemy/komponenty-sistemy/k04.-kommunikaciya-mezhdu-servisami.md), [К05](../../struktura-sistemy/komponenty-sistemy/k05.-modul-sbora-i-agregacii-dannykh.md)
