Пункт 2. Представлен в файлах server.py и client.py 2. Модифицировать простой эхо-сервер таким образом, чтобы при подключении клиента создавался новый поток, в котором происходило взаимодействие с ним. Новые потоки для каждого клиента создаются тут результат подключения клиентов
![image](https://user-images.githubusercontent.com/90391164/138724291-2e6ceba4-2fb5-47fd-a11a-bb01f882554d.png)
![image](https://user-images.githubusercontent.com/90391164/138724312-a6ab7e04-da70-4249-9d66-d6037e552710.png)
![image](https://user-images.githubusercontent.com/90391164/138724336-f988ef0b-abc9-49cb-9879-f8ac0c4f8b58.png)

3.	Реализовать простой чат сервер на базе сервера аутентификации. Сервер должен обеспечивать подключение многих пользователей одновременно, отслеживание имен пользователей, поддерживать историю сообщений и пересылку сообщений от каждого пользователя всем остальным. Чат реализован на TCP сокетах О клиентах следующие данные: информация об IP клиента хранится в зашифрованном виде, логин, пароль тоже в зашифрованном виде Они хранятся построчно в csv файле история сообщений хранится в файле .csv Регистрация клиента файл регистрации - clients.csv
![image](https://user-images.githubusercontent.com/90391164/138724423-e9ab2730-d755-40c7-9952-c671ed3ad1e1.png)
![image](https://user-images.githubusercontent.com/90391164/138724447-6a1daa89-1837-4f44-9d3c-7c8eb68c10f9.png)

История сообщений
![image](https://user-images.githubusercontent.com/90391164/138724506-45cde6df-090c-4a40-aec8-18b702603aaa.png)

Очистка логов очищается сам файл логов и консоль командой clear log
![image](https://user-images.githubusercontent.com/90391164/138724552-6f38c5f2-06d0-45a1-8568-1aca286d6554.png)
![image](https://user-images.githubusercontent.com/90391164/138724569-3b663e59-2358-4c4f-882f-53f9f63bf444.png)

Очистка файла идентификации выполняется командой clear file
![image](https://user-images.githubusercontent.com/90391164/138724618-00e3a2d1-0f6e-4825-9841-59454f2c8fb9.png)
![image](https://user-images.githubusercontent.com/90391164/138724635-0e690892-22f6-410b-851d-1435e9838e62.png)
