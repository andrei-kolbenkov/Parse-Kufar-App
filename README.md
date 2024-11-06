# Parse-Kufar-App

Приложение состоит из:
1. Парсинг товаров с сайта в базу данных Postgres, либо в файл CSV
2. Django приложение с HTML шаблонами для отображения каталога товаров.
  - Функция регистрации, входа/выхода, позволяющая админам редактировать информацию о товаров на главной странице
  - Реализация пагинации страниц
  - Использование debug toolbar для отслеживания запрос к базе данных

The application consists of:
1. Parsing products from the site into a Postgres database or a CSV file
2. Django application with HTML templates for displaying a product catalog.
  - Registration, login/logout function, allowing admins to edit product information on the main page
  - Implementation of page pagination
  - Using debug toolbar to track database queries
