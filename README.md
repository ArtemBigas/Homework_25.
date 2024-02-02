# Homework_25.
Server and Client TCP single-threaded chat. With PostgreSQL database connection
The MakeSockert() function on the server and client creates a Socket and establishes communication. All functions responsible for network communication are located in PostgreSQL.cpp
All functions responsible for working with the PostgreSQL database are located in
Instructions: 1) Start the Server.
2) Launch the Client and register the user.
3) The server accepts this data.
4) Register another user through the Server.
5) Log in to the server and start a chat, press “1”, the Server will start waiting for a message from the Client
6) Authorize another user on the Server and press “1”.
7) To end the chat, send the message end.

Interaction with the database.
1) registration upon registration
2) check during authorization
3)chat recording
4) display message history

Server and Client TCP однопоточный чат.С подключением базы PostgreSQL
Функция MakeSockert() на сервере и клиенте создает Сокет и организует связь. Все функции, отвечающие за связь по сети расположены в PostgreSQL.cpp
Все функции отвечающие за работу с базой PostgreSQL находяться в
Инструкция: 1)Запустить Сервер. 
2)Запустить Клиент и зарегистрировать пользователя. 
3)Сервер принимает эти данные. 
4)Зарегистрировать другого пользователя через Сервер. 
5)Авторизоваться на сервере и начать чат,клавиша "1", Сервер начнет ждать сообщение от Клиента 
6)Авторизовать на Сервере другого пользователя и нажать "1". 
7)Для окончания чата, отправить сообщение end.

Взаимодействие с базой.
1)запись при регистрации
2)проверка при авторизации
3)запись чата
4)вывод истории сообщений

