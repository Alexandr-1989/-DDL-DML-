Задание 1  
  
1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.  
1.2. Создайте учётную запись sys_temp.  
1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)  
1.4. Дайте все права для пользователя sys_temp.  
1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)  
1.6. Переподключитесь к базе данных от имени sys_temp.  
Для смены типа аутентификации с sha2 используйте запрос:  
  
ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';  
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.  
1.7. Восстановите дамп в базу данных.  
1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)  
Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.  

  Ответ:  
  1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.  
  <img width="941" height="351" alt="Screenshot_7" src="https://github.com/user-attachments/assets/a53f640f-53b8-43a2-922c-6b0a3659d0fb" />  
  1.2. Создайте учётную запись sys_temp.  
  1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)   
<img width="724" height="580" alt="Screenshot_9" src="https://github.com/user-attachments/assets/1f13ee1f-b35f-4ca4-b7c2-2cb5031acbdb" />  
 1.4. Дайте все права для пользователя sys_temp.  
 <img width="712" height="435" alt="Screenshot_10" src="https://github.com/user-attachments/assets/3cb9798a-2b99-4ada-9d67-b8eb43323fc7" />  
 1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)   
 <img width="3144" height="402" alt="Screenshot_14" src="https://github.com/user-attachments/assets/3227d8c0-63da-4d86-93c3-d5f15b58e7b6" />  
 1.6. Переподключитесь к базе данных от имени sys_temp.   
 <img width="707" height="394" alt="Screenshot_13" src="https://github.com/user-attachments/assets/bf73df8a-e359-4239-8127-1b15ef52bab3" />  
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.  
<img width="1087" height="529" alt="Screenshot_11" src="https://github.com/user-attachments/assets/b7b466f0-a1f8-4204-85fa-386124ff68ed" />  
1.7. Восстановите дамп в базу данных.    
<img width="563" height="84" alt="Screenshot_16" src="https://github.com/user-attachments/assets/a68ba306-ade2-4644-b699-434104db05c7" />  
1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)  
<img width="673" height="653" alt="Screenshot_15" src="https://github.com/user-attachments/assets/bbaa04e2-01e9-4bd8-9167-910e8cad2a2d" />  
  
Задание 2  
Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)  
  <img width="1185" height="482" alt="Screenshot_12" src="https://github.com/user-attachments/assets/72b0d921-9b44-460d-ae82-0db6b66b8f3c" />  

Название таблицы | Название первичного ключа customer | customer_id  

  Ответ :  
  


