# Table of contents

* [Модель угроз](README.md)

## Структура системы

* [Компоненты системы](struktura-sistemy/komponenty-sistemy/README.md)
  * [К01. Физический сервер и гипервизор](struktura-sistemy/komponenty-sistemy/k01.-fizicheskii-server-i-gipervizor.md)
  * [К02. Виртуальная машина для веб-приложения и API](struktura-sistemy/komponenty-sistemy/k02.-virtualnaya-mashina-dlya-veb-prilozheniya-i-api.md)
  * [К03. База данных и кэширование](struktura-sistemy/komponenty-sistemy/k03.-baza-dannykh-i-keshirovanie.md)
  * [К04. Коммуникация между сервисами](struktura-sistemy/komponenty-sistemy/k04.-kommunikaciya-mezhdu-servisami.md)
  * [К05. Модуль сбора и агрегации данных](struktura-sistemy/komponenty-sistemy/k05.-modul-sbora-i-agregacii-dannykh.md)
  * [К06. Модуль оценки отелей (LLM-интеграция)](struktura-sistemy/komponenty-sistemy/k06.-modul-ocenki-otelei-llm-integraciya.md)
  * [К07. Взаимодействие компонентов](struktura-sistemy/komponenty-sistemy/k07.-vzaimodeistvie-komponentov.md)
  * [К08. Безопасность и мониторинг](struktura-sistemy/komponenty-sistemy/k08.-bezopasnost-i-monitoring.md)
  * [К09. Документация и поддержка](struktura-sistemy/komponenty-sistemy/k09.-dokumentaciya-i-podderzhka.md)

## Угрозы

* [Перечень угроз системы](ugrozy/perechen-ugroz-sistemy/README.md)
  * [УГ1. Нарушение аутентификации API](ugrozy/perechen-ugroz-sistemy/ug1.-narushenie-autentifikacii-api.md)
  * [УГ2. Нарушение авторизации на уровне объектов](ugrozy/perechen-ugroz-sistemy/ug2.-narushenie-avtorizacii-na-urovne-obektov.md)
  * [УГ3. Избыточное потребление ресурсов](ugrozy/perechen-ugroz-sistemy/ug3.-izbytochnoe-potreblenie-resursov.md)
  * [УГ4. Компрометация хранилищ данных (НСД к конкретной части)](ugrozy/perechen-ugroz-sistemy/ug4.-komprometaciya-khranilish-dannykh-nsd-k-konkretnoi-chasti.md)
  * [УГ5. Межсайтовые запросы с сервера](ugrozy/perechen-ugroz-sistemy/ug5.-mezhsaitovye-zaprosy-s-servera.md)
  * [УГ6. Утечка конфиденциальных данных](ugrozy/perechen-ugroz-sistemy/ug6.-utechka-konfidencialnykh-dannykh.md)
  * [УГ7. Инъекция команд и данных](ugrozy/perechen-ugroz-sistemy/ug7.-inekciya-komand-i-dannykh.md)
  * [УГ8. Снижение целостности кэша](ugrozy/perechen-ugroz-sistemy/ug8.-snizhenie-celostnosti-kesha.md)
  * [УГ9. Нарушение доступности](ugrozy/perechen-ugroz-sistemy/ug9.-narushenie-dostupnosti.md)
  * [УГ10. Подмена данных модели AI](ugrozy/perechen-ugroz-sistemy/ug10.-podmena-dannykh-modeli-ai.md)
  * [УГ11. Утечка секретов](ugrozy/perechen-ugroz-sistemy/ug11.-utechka-sekretov.md)

## Уязвимости

* [Перечень уязвимостей системы](uyazvimosti/perechen-uyazvimostei-sistemy/README.md)
  * [У1. Отсутствие изоляции виртуальных сетей (VLAN)](uyazvimosti/perechen-uyazvimostei-sistemy/u1.-otsutstvie-izolyacii-virtualnykh-setei-vlan.md)
  * [У2. Доступ к консоли гипервизора через HTTP без 2FA](uyazvimosti/perechen-uyazvimostei-sistemy/u2.-dostup-k-konsoli-gipervizora-cherez-http-bez-2fa.md)
  * [У3. Отсутствие мониторинга температуры сервера](uyazvimosti/perechen-uyazvimostei-sistemy/u3.-otsutstvie-monitoringa-temperatury-servera.md)
  * [У4. Отсутствие проверки целостности данных от агентов](uyazvimosti/perechen-uyazvimostei-sistemy/u4.-otsutstvie-proverki-celostnosti-dannykh-ot-agentov.md)
  * [У5. Отсутствие заголовка X-Content-Type-Options](uyazvimosti/perechen-uyazvimostei-sistemy/u5.-otsutstvie-zagolovka-x-content-type-options.md)
  * [У6. Отсутствие шифрования SNMP-трафика](uyazvimosti/perechen-uyazvimostei-sistemy/u6.-otsutstvie-shifrovaniya-snmp-trafika.md)
  * [У7. Кэширование учетных данных в браузере](uyazvimosti/perechen-uyazvimostei-sistemy/u7.-keshirovanie-uchetnykh-dannykh-v-brauzere.md)
  * [У8. Устаревшие библиотеки (Django < 4.2, пакеты ML без патчей)](uyazvimosti/perechen-uyazvimostei-sistemy/u8.-ustarevshie-biblioteki-django-less-than-4.2-pakety-ml-bez-patchei.md)
  * [У9. Отсутствие шифрования Redis‑трафика (нет TLS)](uyazvimosti/perechen-uyazvimostei-sistemy/u9.-otsutstvie-shifrovaniya-redis-trafika-net-tls.md)
  * [У10. Открытые административные интерфейсы (Django Admin без 2FA)](uyazvimosti/perechen-uyazvimostei-sistemy/u10.-otkrytye-administrativnye-interfeisy-django-admin-bez-2fa.md)
  * [У11. Недостаточное логирование аутентификации (нет записи неудачных попыток)](uyazvimosti/perechen-uyazvimostei-sistemy/u11.-nedostatochnoe-logirovanie-autentifikacii-net-zapisi-neudachnykh-popytok.md)
  * [У12. Отсутствие блокировки IP после 5 неудачных попыток входа](uyazvimosti/perechen-uyazvimostei-sistemy/u12.-otsutstvie-blokirovki-ip-posle-5-neudachnykh-popytok-vkhoda.md)
  * [У13. Серверное включение подробного дебаг‑режима (DEBUG=True)](uyazvimosti/perechen-uyazvimostei-sistemy/u13.-servernoe-vklyuchenie-podrobnogo-debag-rezhima-debug-true.md)
  * [У14. Неограниченный доступ к модели ML через API (нет авторизации)](uyazvimosti/perechen-uyazvimostei-sistemy/u14.-neogranichennyi-dostup-k-modeli-ml-cherez-api-net-avtorizacii.md)

## Сценарии атак

* [Перечень сценариев атак](scenarii-atak/perechen-scenariev-atak/README.md)
  * [С1. SQL‑инъекция для эксфильтрации пользовательских данных](scenarii-atak/perechen-scenariev-atak/s1.-sql-inekciya-dlya-eksfiltracii-polzovatelskikh-dannykh.md)
  * [С2. DoS‑атака на поиск отелей](scenarii-atak/perechen-scenariev-atak/s2.-dos-ataka-na-poisk-otelei.md)
  * [С3. SSRF для сканирования внутренней сети](scenarii-atak/perechen-scenariev-atak/s3.-ssrf-dlya-skanirovaniya-vnutrennei-seti.md)
  * [С4. Перехват и модификация сообщений RabbitMQ](scenarii-atak/perechen-scenariev-atak/s4.-perekhvat-i-modifikaciya-soobshenii-rabbitmq.md)
  * [С5. Подделка ответов AI‑модели](scenarii-atak/perechen-scenariev-atak/s5.-poddelka-otvetov-ai-modeli.md)
  * [С6. Кража секретов из контейнеров Docker](scenarii-atak/perechen-scenariev-atak/s6.-krazha-sekretov-iz-konteinerov-docker.md)
  * [С7. Эксплуатация CSRF в административной панели Django](scenarii-atak/perechen-scenariev-atak/s7.-ekspluataciya-csrf-v-administrativnoi-paneli-django.md)
  * [С8. Утечка пользовательских данных через непрозрачный бэкап](scenarii-atak/perechen-scenariev-atak/s8.-utechka-polzovatelskikh-dannykh-cherez-neprozrachnyi-bekap.md)
