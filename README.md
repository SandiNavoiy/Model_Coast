Дипломный проект 
Тема -прогноз цен на товары из представленой выборки.
Выборка представлена в файле csv_data.csv.
Для начала работы необходимо разархивировать в туже папку файл csv_data.zip
В начале работы необходимо:
1. Установить и поднять виртуальное окружение командой python -m venv venv
2. Сделать апгрейд python.exe -m pip install --upgrade pip
3. Установить зависимости командой pip install -r requirements.txt
4. В корень проекта необходимо положить файл database.ini с параметрами для подключения к БД. 
   По умолчанию программа подключается к базе данных 'postgres' Пример содержания .ini файла:
   [postgresql]
host=localhost
user=postgres
password=1
port=5432
5. Запуск проекта осуществляется из файла main.py
Стэк
- python 
- postgresql