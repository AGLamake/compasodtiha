# УГ6. Утечка конфиденциальных данных

### **Описание угрозы**

раскрытие PII, секретов, резервных копий.

### **Задаваемые ценные ресурсы**

дампы БД, файлы конфигурации, логи.

### **Угрозы**

скачивание нешифрованных бэкапов, кэширование в браузере.

### **Возможные сценарии**

эксплойты [У7](../../uyazvimosti/perechen-uyazvimostei-sistemy/u7.-keshirovanie-uchetnykh-dannykh-v-brauzere.md) и [У13](../../uyazvimosti/perechen-uyazvimostei-sistemy/u13.-servernoe-vklyuchenie-podrobnogo-debag-rezhima-debug-true.md) для получения файлов.

### **Потенциальные последствия**

компрометация аккаунтов, штрафы.

### **Меры по защите**

шифрование, удаление DEBUG, CSP, заголовки безопасности.

### **Связи**

[У7](../../uyazvimosti/perechen-uyazvimostei-sistemy/u7.-keshirovanie-uchetnykh-dannykh-v-brauzere.md), [У11](../../uyazvimosti/perechen-uyazvimostei-sistemy/u11.-nedostatochnoe-logirovanie-autentifikacii-net-zapisi-neudachnykh-popytok.md), [У13](../../uyazvimosti/perechen-uyazvimostei-sistemy/u13.-servernoe-vklyuchenie-podrobnogo-debag-rezhima-debug-true.md); [С6](../../scenarii-atak/perechen-scenariev-atak/s6.-krazha-sekretov-iz-konteinerov-docker.md), [С8](../../scenarii-atak/perechen-scenariev-atak/s8.-utechka-polzovatelskikh-dannykh-cherez-neprozrachnyi-bekap.md)
