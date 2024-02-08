# Тестовое задание на вакансию “Специалист по тестированию ПО"
## Задание 1. Написание тестовой документации для страницы "Новостройки" сайта "Этажи".

* [Чек-лист](https://docs.google.com/spreadsheets/d/1-WCAW7-YrCMSKZ_VfWastpFOy7m9n_n1RQGOGASilAw/edit?usp=sharing)
* [Тест-кейс](https://docs.google.com/spreadsheets/d/1qFwTlCA1Pk21Ltr9TXovvgkQVnXj6nslW2eC-nQWLPk/edit?usp=sharing)
* [Список дефектов](https://docs.google.com/spreadsheets/d/1J2U8_1tdEXdF9UGfiuCiELYMXj9RnQ5AlK0Mm3bPCXU/edit?usp=sharing)
* [Баг-репорт](https://github.com/TatyanaKonysheva/Etagi/issues/1)
  
## Задание 2. Написание SQL запросов для таблицы customers.

  1. Запрос на вывод города и номера телефона клиентов с фамилией "Попов":

    SELECT city, phone
    FROM customers
    WHERE fio LIKE '%Попов%';
  
  1. Запрос на подсчет количества клиентов из Тюмени:
     
    SELECT COUNT(*)
    FROM customers
    WHERE city = 'Тюмень'
