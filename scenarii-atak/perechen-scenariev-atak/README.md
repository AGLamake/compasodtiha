# Перечень сценариев атак

1. [С1. SQL‑инъекция для эксфильтрации пользовательских данных](s1.-sql-inekciya-dlya-eksfiltracii-polzovatelskikh-dannykh.md)\
   Через уязвимые поля фильтрации отелей злоумышленник получает весь список пользователей.
2. [С2. DoS‑атака на поиск отелей](s2.-dos-ataka-na-poisk-otelei.md)\
   Автоматизированный «флуд» API‑endpoint приводит к падению сервера (без rate‑limit).
3. [С3. SSRF для сканирования внутренней сети](s3.-ssrf-dlya-skanirovaniya-vnutrennei-seti.md)\
   Используя открытый URL‑парсер, атакующий достаётся до метрик Prometheus на хосте.
4. [С4. Перехват и модификация сообщений RabbitMQ](s4.-perekhvat-i-modifikaciya-soobshenii-rabbitmq.md)\
   Атакующий внедряет ложные задачи на рассылку, уведомления и парсинг.
5. [С5. Подделка ответов AI‑модели](s5.-poddelka-otvetov-ai-modeli.md)\
   Путём манипуляции параметрами модели формируется завышенный рейтинг низкокачественных отелей.
6. [С6. Кража секретов из контейнеров Docker](s6.-krazha-sekretov-iz-konteinerov-docker.md)\
   Пропуск через уязвимость объёма docker.sock позволяет читать SECRET\_KEY и credentials.
7. [С7. Эксплуатация CSRF в административной панели Django](s7.-ekspluataciya-csrf-v-administrativnoi-paneli-django.md)[\
   ](s7.-ekspluataciya-csrf-v-administrativnoi-paneli-django.md)Без защиты CSRF токеном администратор вынужденно выполняет непредвиденные действия.
8. С[8. Утечка пользовательских данных через непрозрачный бэкап](s8.-utechka-polzovatelskikh-dannykh-cherez-neprozrachnyi-bekap.md)\
   Не зашифрованные dump‑файлы PostgreSQL скачиваются и анализируются.
