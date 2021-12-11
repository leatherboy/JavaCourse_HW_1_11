Задача - написать инструмент, позволяющий сравнивать две таблицы из двух разных баз данных по заданному набору полей.

Параметры на входе:
- данные для подключения к БД 1, БД 2, 
- имя таблицы 1 и таблицы 2, 
- набор полей (строка, разделение полей через запятую) по которым требуется провести сравнение. 

Требуется вернуть true, если содержимое таблиц эквивалентно по заданному набору полей, вернуть false иначе.