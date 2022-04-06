## Парсеры

Первый парсер(whats-new) - выводит список на статьи в табличном виде о нововведениях в Python и справочную информацию об авторах и редакторах этих статей;

Второй парсер(latest_versions) - собирает и скачивает архив с документацией Python в виде таблицы: номера, статусы (in development, pre-release, stable и так далее) и ссылки на документацию;

Третий парсер(download) - скачивает архив с документацией Python на ваш локальный диск;

Четвёртый парсер(pep) - парсит данные обо всех документах PEP.

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
`git clone https://github.com/AigulParamonova/bs4_parser_pep.git`

Установите и активируйте виртуальное окружение (Windows):
`python -m venv venv`
`source venv/Scripts/activate`

Обновить менеджер пакетов:
`python -m pip install --upgrade pip`

Установить зависимости:
`pip install -r requirements.txt`

## Управление через командную строку:
Пример вызова справки:
`python main.py -h `

Позиционные аргументы:
`{whats-new,latest-versions,download} Режимы работы парсера`
                        
Опциональные аргументы:
` -h, --help   show this help message and exit`
`  -c, --clear-cache     Очистка кеша`
`  -o {pretty,file}, --output {pretty,file} Дополнительные способы вывода данных`

## Технологии:
- Python 3
- Django
- Git

