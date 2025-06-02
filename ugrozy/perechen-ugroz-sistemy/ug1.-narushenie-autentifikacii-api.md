# УГ1. Нарушение аутентификации API

### **Описание угрозы**

Злоумышленник получает несанкционированный доступ к API.

### **Задаваемые ценные ресурсы**

REST API, данные пользователей, административные функции.

### **Угрозы**

кража сессий, brute-force, перехват токенов.

### **Возможные сценарии**

отсутствие блокировки по IP ([У12](../../uyazvimosti/perechen-uyazvimostei-sistemy/u12.-otsutstvie-blokirovki-ip-posle-5-neudachnykh-popytok-vkhoda.md)) + нет 2FA в админке ([У10](../../uyazvimosti/perechen-uyazvimostei-sistemy/u10.-otkrytye-administrativnye-interfeisy-django-admin-bez-2fa.md)).

### **Потенциальные последствия**

утечка личных данных, изменение конфигураций.

### **Меры по защите**

внедрение 2FA, rate-limit, мониторинг неудачных попыток (У11).

### **Связи**&#x20;

[У2](../../uyazvimosti/perechen-uyazvimostei-sistemy/u2.-dostup-k-konsoli-gipervizora-cherez-http-bez-2fa.md), [У10](../../uyazvimosti/perechen-uyazvimostei-sistemy/u10.-otkrytye-administrativnye-interfeisy-django-admin-bez-2fa.md), [У11](../../uyazvimosti/perechen-uyazvimostei-sistemy/u11.-nedostatochnoe-logirovanie-autentifikacii-net-zapisi-neudachnykh-popytok.md), [У12](../../uyazvimosti/perechen-uyazvimostei-sistemy/u12.-otsutstvie-blokirovki-ip-posle-5-neudachnykh-popytok-vkhoda.md); [С2](../../scenarii-atak/perechen-scenariev-atak/s2.-dos-ataka-na-poisk-otelei.md), [С7](../../scenarii-atak/perechen-scenariev-atak/s7.-ekspluataciya-csrf-v-administrativnoi-paneli-django.md)
