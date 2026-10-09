Первый вывод таблицы с VSZ и RSS, прилагаю скриншот 

<img width="778" height="356" alt="image" src="https://github.com/user-attachments/assets/1bd36629-e31e-457e-b89b-25bd2e06d2a1" />

Здесь видны сколько памяти есть и сколько занято 

Прилагаю скриншот до mmap 

<img width="614" height="67" alt="image" src="https://github.com/user-attachments/assets/6db0afaf-198b-48c6-bbad-e4652d8cb608" />

И после 

<img width="592" height="53" alt="image" src="https://github.com/user-attachments/assets/73358427-1081-4d79-9abf-7385818d2c3c" />

Ну потому что оно просто зарезервировала пространство для него и отправилась в спящий режим 
Выделено — не значит занято это значит, что память даётся, но физически выделяется только когда в неё реально пишут
