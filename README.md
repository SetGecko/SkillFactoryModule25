### 25.7 Entity Framework Core

* Создайте проект с использованием Entity Framework Core и реализуйте схему Базы данных с помощью классов. За тему данного проекта возьмите электронную библиотеку, в которой существуют пользователи и книги. У пользователя обязательно должны присутствовать поля Имя и Email, а у книги — Название и Год выпуска.

* Для каждой из моделей в приложении создайте собственный класс-репозиторий (например, UserRepository и BookRepository), в которых опишите следующие действия: выбор объекта из БД по его идентификатору, выбор всех объектов, добавление объекта в БД и его удаление из БД. А также специфичные методы: обновление имени пользователя (по Id) и обновление года выпуска книги (по Id).

* Реализуйте с помощью одной из связей возможность получения книги «на руки» пользователем (для этого придется удалить таблицы из БД, либо воспользоваться EnsureDeleted). А также придумайте, как можно добавить в книгу автора и жанр книги.

* С помощью полученных знаний дополните репозитории методами, которые позволят совершать следующие действия:

    - Получать список книг определенного жанра и вышедших между определенными годами.
    - Получать количество книг определенного автора в библиотеке.
    - Получать количество книг определенного жанра в библиотеке.
    - Получать булевый флаг о том, есть ли книга определенного автора и с определенным названием в библиотеке.
    - Получать булевый флаг о том, есть ли определенная книга на руках у пользователя.
    - Получать количество книг на руках у пользователя.
    - Получение последней вышедшей книги.
    - Получение списка всех книг, отсортированного в алфавитном порядке по названию.
    - Получение списка всех книг, отсортированного в порядке убывания года их выхода.








