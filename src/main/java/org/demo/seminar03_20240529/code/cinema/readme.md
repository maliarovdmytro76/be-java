### Техническое задание: "Система управления кинотеатром"

#### Цель:
Создать систему управления кинотеатром, которая включает в себя различные сущности, такие как фильмы, сеансы, пользователи и билеты. Система должна демонстрировать использование полиморфизма и интерфейсов.

#### Описание задачи:
1. **Фильмы**: Создать иерархию классов для фильмов с различными жанрами.
2. **Сеансы**: Управление расписанием сеансов различных фильмов.
3. **Пользователи**: Различные типы пользователей (администраторы и зрители) с соответствующими ролями и правами.
4. **Билеты**: Продажа билетов на сеансы, отображение информации о билетах.

#### Требования:
1. **Интерфейсы и классы:**
   - Создать интерфейс `Film` с методами для получения названия фильма и его жанра.
   - Создать несколько классов, реализующих интерфейс `Film`, для разных жанров (например, `ActionFilm`, `ComedyFilm`, `DramaFilm`).
   - Создать интерфейс `User` с методами для получения имени пользователя и его роли.
   - Создать классы, реализующие интерфейс `User`, для разных типов пользователей (например, `AdminUser`, `ViewerUser`).
   - Создать класс `Session`, представляющий сеанс, который содержит фильм, время и количество доступных билетов.
   - Создать класс `Ticket`, представляющий билет, который содержит информацию о пользователе, сеансе и месте.



2. **Полиморфизм:**
   - Использовать полиморфизм для обработки различных типов фильмов и пользователей.
   - Демонстрировать полиморфное поведение при работе с коллекциями фильмов и пользователей.

3. **Функциональность:**
   - Создание, редактирование и удаление сеансов (доступно только администраторам).
   - Просмотр списка доступных сеансов и покупка билетов (доступно всем пользователям).
   - Просмотр информации о купленных билетах.

