1. Составить запрос на добавление записи в таблицу
2. Составить запрос на изменение записи в таблице
3. Составить запрос на удаление записи в таблице

1) lNSERT INTO table(row1, row2)
   VALUES ('test1', 'test2')

2) CHANGE table SET row1=test11
   WHERE row1=test1

3) DROP FROM table WHERE id=1
