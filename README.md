# courseproj-5

Программа для создания новой таблицы suppliers в БД northwind, связи ее с уже имеющимися таблицами, а также вывода нужных данных из БД. Таблица содержит юридическую информацию о поставщиках и id поставляемой продукции, которая ссылается на таблицу products. Модуль fill_suppliers_in_db.py содержит скрипт для создания таблицы, ее связей и заполнения таблицы из исходного файла suppliers.json. Модуль main.py содержит функции для вывода в формате json краткой информации о продукте и категории продукции из БД по запрошенному id продукта или категории. Директория sql-export_pages содержит файлы с sql-командами для вывода нужных данных из БД. Файл northwind_dump.sql содержит sql-команды для создания итоговой БД вместе с таблицей suppliers.