# 28.02
# socket IO
1. Где используется. 
Используется в приложениях, работающих в режиме реального времени.
2. Схема использования.
клиент - сервер
4. Что за связь дуплексная и при чём здесь она?
Дуплексный канал связи – это система связи, когда передача возможна в обоих направлениях канала электросвязи. Иными словами, это способ передачи данных, при котором адресат и адресант меняются ролями, субъекты взаимно активны и работают в единых направлениях связи. Она включается когда клиент имеет Socket IO в браузере, а сервер также интегрировал пакет Socket IO.
4. На каких языках есть данная реализация бибилиотеки? 
JavaScript, C++, Swift, Dart, Python, .Net
5. Отличия websocket от socketIO(кратенько)?
В отличие от WebSocket, Socket.IO позволяет транслировать сообщение всем подключенным клиентам. Например, если вы пишете приложение для чата и хотите уведомить всех подключенных клиентов о том, что к чату присоединился новый пользователь, вы можете легко передать это сообщение всем за один раз.
6. Что такое  long-polling?
это самый простой способ поддерживать постоянное соединение с сервером, не используя при этом никаких специфических протоколов
7. Что такое  Broadcasting?
8. Что такое  Multiplexing?
Пространства имен позволяют разделить логику вашего приложения по одному общему соединению. Это может быть полезно, например, если вы хотите создать канал администратора, к которому могут присоединиться только авторизованные пользователи.
9. Динамические пространства имен, что это для чего?
Пространства имён применяются в окружениях с многочисленными пользователями, распределенными по нескольким командам или проектам. Пространства имён не нужно создавать, если есть кластеры с небольшим количеством пользователей (например, десяток пользователей). Пространства имён имеет смысл использовать, когда необходима такая функциональность.

