# Office-expense-tracker
## Бердник Любовь. Номер группы: 153502
***Целью данного проекта является создание программного продукта, который позволял бы обрабатывать информацию о покупках фирмы, вести учет расходов.***
### В рассматриваемой предметной области можно выделить следующие основные сущности: 
+ **Department** – содержит информацию об отделе, уникальный идентификационный номер и количество сотрудников. 
+ **Expense** – содержит информацию о названии, уникальном идентификационном номере, какому отделу принадлежит данная трата, 
+ **Permission** – список разрешенных действий в приложении. 
+ **Account** – аккаунт сотрудника с информацией о разрешениях (yправление программой от лица различных пользователей с различными правами доступа). 
+ **Manager** – сотрудник, который может видеть данные, может изменять данные с запросом на подтверждение.
+ **Moderator** – сотрудник, который может видеть данные, может изменять данные с запросом на подтверждение, может отклонять данные.
+ **Administrator** – сотрудник, который имеет доступ ко всем функциям приложения: изменение данных без запроса подтверждения, подтверждение/отклонение изменений, управление аккаунтами.
### Функционал приложения:
+ ***Вход в систему*** (логин и пароль)
+ ***Ввод и редактирование данных***
+ ***Статистический учет данных***
+ ***Графическое представление данных*** (круговая диаграмма расходов каждого отдела фирмы)
+ ***Возможность определить общую сумму и сравнивать покупки***
+ ***Хранение информации в базе данных:***
- Список отделов
- Информация о каждом отделе (название, кол-во сотрудников)
- Список расходов для каждого отдела
- Информация о каждой покупке (название, описание, сумма, предельная сумма)
