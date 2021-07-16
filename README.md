# Web-технологии

В данном репозитории хранятся все презентации для освоения дисциплины 
"Web-технологии". Презентации сделаны на движке [Shower](https://shwr.me/).
Посмотреть все презентации можно по [ссылке](https://LoveSolaristics.github.io/shower-presentation/prepared/index.html).


## Содержание

1. Основы web-технологий;
2. [Структура HTML-документа](https://LoveSolaristics.github.io/shower-presentation/prepared/2.html);

## Локальный запуск

Для локального запуска необходим [Node.js](https://nodejs.org/en/).

Вы можете скачать репозиторий в виде zip-архива,
либо клонировать этот репозиторий с помощью командной строки.

Далее необходимо установить зависимости:
```
npm install
```
А затем выполнить команду для возможности редактирования слайдов
с поддержкой автоматической перезагрузки изменений:
```
npm start
```
После внесения изменений можно получить чистую копию слайдов в папке `prepared`
с помощью команды:
```
npm run prepare
```