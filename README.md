
# task-for-croc
## Автор решения 
Полетаева Дина Кирилловна

почта: amgoize@gmail.com

telegram: @amgoize

## Описание реализации

Проект собран с помощью Maven.

Для преобразования JSON в Java-обьект в проекте присутствуют три сущности: Order, Item< Category.

Для обработки JSON файла используется библиотека Jackson.

Класс JsonReader содержит метод для чтения из JSON-файла, преобразование его в Java-объекты, также обрабатывает ошибки.

Класс CategoriesWriter преобразует объект MostPopularCategories, используемый для хранения самых поплурных категорий, в формат JSON с использованием.

Класс OrdersAnalyzer определяет самые популярнные категории.

## Инструкция по сборке и запуску решения

Нужно зайти в директорию проекта task-for-croc

Запустить в терминале следующую команду: java -jar target/report.jar

Или скачаьб архив проекта, разархивировать

Открыть его в IntellijIdea, запустить класс Main


