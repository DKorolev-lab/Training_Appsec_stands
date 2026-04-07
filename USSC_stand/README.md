## 🛡️Эксплуатация USSC Stand
### Развертывание
1. docker build -t ussc_stand .
2. docker run -d --name USSC_stand -p 80:80 ussc_stand
#### Настройка:
1. Откройте в браузере http://<ваш-ip>/install.php

## 🔍 Задание:
### Client-side уязвимости (минимум 10 различных, например):
1. Межсайтовый скриптинг (XSS)
2. Подделка межсайтовых запросов (CSRF)
3. Clickjacking
4. DOM-based уязвимости

## Server-side уязвимости (минимум 10 различных, например):
1. SQL-инъекции
2. Небезопасная десериализация
3. XXE-инъекции
4. SSRF
5. RCE
6. LFI/RFI
