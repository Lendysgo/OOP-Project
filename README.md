# Telegram Bot 
Этот бот предназначен для управления задачами и предоставляет базовый набор команд.
## Команда   
[Ярослав](https://github.com/Lendysgo)     
[Арсений](https://github.com/arsbars24)    

Этот проект собран с помощью утилиты Apache Maven.  
[Бот](https://t.me/manageres_bot) отвечает на команды пользователя и возвращет ему точно такую же строку    
## Команды бота:   
/start: Запускает бота и приветствует пользователя.     
/help: Возвращает информацию о доступных командах и их использовании.   

### Задача 2
Цель задачи: Разработать простой блокнот для записей, с возможностью добавлять, изменять и удалять записи.

Планы на развитие:
Расширение блокнота с поддержкой категорий и тегов для записей.
Добавление возможности делиться записями с другими пользователями.
Внедрение функции напоминаний и уведомлений для записей.

Примеры диалога:

П: /help  
Б: Привет я простой бот для записей, можешь записывать в меня всё что угодно,
а еще удалять и редактировать записи. Ежедневник в твоем распоряжении.  
П: /table  
Б: Вот ваши записи  
1….  
2….  
3….  
(каждая запись с отступом \n)  
П: /add 1  
Б: Добавьте свою первую запись  
П:(Пользователь вносит запись)  
Б: Запись внесена! ^_^  
  
П: /del 1  
Б: Первая запись удалена  
   
П: /edit 1  
Б: Вот текст записи: Пример текста записи  
Б: Можете вводить изменения в нём  
П: (внесение изменений)  

