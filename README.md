# Выпускной проект по SQL
«SQL – Анализ базы данных сервиса для чтения книг по подписке»
Описание проекта
Коронавирус застал мир врасплох, изменив привычный порядок вещей. В свободное время жители городов больше не выходят на улицу, не посещают кафе и торговые центры. Зато стало больше времени для книг. Это заметили стартаперы — и бросились создавать приложения для тех, кто любит читать.


Компания решила быть на волне и купила крупный сервис для чтения книг по подписке.
Цели проекта: проанализировать базу данных. В базе данных информация о книгах, издательствах, авторах, а также пользовательские обзоры книг. Эти данные помогут сформулировать ценностное предложение для нового продукта.<br><br>
Описание данных:<br>

*Таблица books*<br>
Содержит данные о книгах:<br>
- book_id — идентификатор книги;<br>
- author_id — идентификатор автора;<br>
- title — название книги;<br>
- num_pages — количество страниц;<br>
- publication_date — дата публикации книги;<br>
- publisher_id — идентификатор издателя.<br>

*Таблица authors* <br>
Содержит данные об авторах: <br>
- author_id — идентификатор автора; <br>
- author — имя автора. <br>

*Таблица publishers* <br>
Содержит данные об издательствах:<br>
- publisher_id — идентификатор издательства;<br>
- publisher — название издательства;<br>

*Таблица ratings*<br>
Содержит данные о пользовательских оценках книг:<br>
- rating_id — идентификатор оценки;<br>
- book_id — идентификатор книги;<br>
- username — имя пользователя, оставившего оценку;<br>
- rating — оценка книги.<br><br>

*Таблица reviews*<br>
Содержит данные о пользовательских обзорах на книги:<br>

- review_id — идентификатор обзора;<br>
- book_id — идентификатор книги;<br>
- username — имя пользователя, написавшего обзор;<br>
- text — текст обзора.<br>
