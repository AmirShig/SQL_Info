# SQL_Info

Анализ и статистика данных по школе 21.

## Введение

В этом проекте вы закрепите свои знания SQL, создав базу данных со значениями о Школе 21 и написав процедуры и функции для получения и изменения информации.

### Таблицы

- Peers (Ник пира, День рождения)
- Tasks (Название задания, Название задания-условия входа, Максимальное количество XP)
- P2P (ID, ID проверки, Ник проверяющего пира, Статус P2P проверки, Время)
- Verter (ID, ID проверки, Статус проверки Verter'ом, Время)
- Checks (ID, Ник пира, Название задания, Дата проверки)
- TransferredPoints (ID, Ник проверяющего пира, Ник проверяемого пира, Количество переданных пир поинтов за всё время)
- Friends (ID, Ник первого пира, Ник второго пира)
- Recommendations (ID, Ник пира, Ник пира, к которому рекомендуют идти на проверку)
- XP (ID, ID проверки, Количество полученного XP)
- TimeTracking (ID, Ник пира, Дата, Время, Состояние)

## Глава III

### Часть 1. Создание базы данных

Напишите скрипт *part1.sql*, создающий базу данных и все таблицы, описанные выше. Добавьте в скрипт процедуры для импорта и экспорта данных для каждой таблицы из файла/в файл с расширением *.csv*. В каждую таблицу добавьте как минимум по 5 записей.

### Часть 2. Изменение данных

Создайте скрипт *part2.sql*, в который добавьте процедуры и триггеры для изменения данных.

### Часть 3. Получение данных

Создайте скрипт *part3.sql*, в который добавьте процедуры и функции для получения данных.

### Дополнительно. Часть 4. Метаданные

Создайте отдельную базу данных для тестирования процедур. Создание и заполнение этой базы данных, а также написанные процедуры, внесите в файл *part4.sql*.