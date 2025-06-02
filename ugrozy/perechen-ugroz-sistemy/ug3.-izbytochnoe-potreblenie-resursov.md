# УГ3. Избыточное потребление ресурсов

### **Описание угрозы**

Злоумышленник или система используют слишком много CPU/RAM/дисков.

### **Задаваемые ценные ресурсы**

Вычислительные ресурсы сервера, пропускная способность сети.

### **Угрозы**

DoS-флуд, несанкционированный майнинг.

### **Возможные сценарии**

Массовые запросы к API без rate-limit.

### **Потенциальные последствия**

Деградация производительности, отказ сервисов.

### **Меры по защите**

Внедрить rate-limiting, квоты, автошкалу масштабирования.

### **Связи**

[У1](../../uyazvimosti/perechen-uyazvimostei-sistemy/u1.-otsutstvie-izolyacii-virtualnykh-setei-vlan.md), [У12](../../uyazvimosti/perechen-uyazvimostei-sistemy/u12.-otsutstvie-blokirovki-ip-posle-5-neudachnykh-popytok-vkhoda.md); [С2](../../scenarii-atak/perechen-scenariev-atak/s2.-dos-ataka-na-poisk-otelei.md); [К01](../../struktura-sistemy/komponenty-sistemy/k01.-fizicheskii-server-i-gipervizor.md), [К02](../../struktura-sistemy/komponenty-sistemy/k02.-virtualnaya-mashina-dlya-veb-prilozheniya-i-api.md)
