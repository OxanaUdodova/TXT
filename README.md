# TXT
 1. Создать внешний репозиторий c названием TXT.

Создала репозиторий <https://github.com/OxanaUdodova/TXT>

2. Клонировать репозиторий TXT на локальный компьютер.

`git clone https://github.com/OxanaUdodova/TXT.git`

 3. Внутри локального TXT создать файл “new.txt”.

`touch new.txt`


 4. Добавить файл под гит.

`git add .`

 5. Закоммитить файл.

`git commit -m "add new.txt"`

 6. Отправить файл на внешний GitHub репозиторий.

`git push`

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

`nano new.txt`

    new:
     name: Udodova Oxana Sergeevna
     age: '35'
     pet: '1'
     salary: '50000'

*Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)*

 8. Отправить изменения на внешний репозиторий.

`git add . >>  git commit -m "modify new.txt" >> git push`

 9. Создать файл preferences.txt
 
`touch preferences.txt`

 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

`nano preferences.txt`

    preferences:
        favor_film: Harry Potter
        favor_serial: none
        favor_food: none
        favor_season: spring
        country: Italy

*Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)*

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

`nano skills.txt `

    skills:
    - Базовая теория (Что такое тестирование, багрепорты, документация, виды,
    методы, направления тестирования и т.п.) SDLC, STLC
    - Что такое клиент-серверная архитектура
    - HTTP Методы запросов на сервер
    - Коды ответов HTTP сервера
    - Структуры HTTP запросов и ответов
    - Что такое JSON, XML. Их структура
    - Тестирование API через Postman (JS, автотесты API)
    - Снятие и чтение логов c внешнего сервера
    - Снифинг http web трафика через Charles и Fiddler
    - 'Dev Tools веб браузеров (Google Chrome, FireFox)
    - 'VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
    - Мобильное тестирование
    - 'Особенность iOS, Android, гайдлайны
    - Сборка iOS приложений на XCode
    - Сборка Android приложений на Android Studio
    - ADB (управление андройд девайсами)
    - Настройка прокси и vpn на iOS и Android
    - Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и
    Android
    - Командная строка (terminal) Linux (копирование, создание, просмотр,
    перемещение файлов на серверах без графического интерфейса)
    - Основы bash скриптинг, автоматизация рутинных задач на сервере
    - Доступ к удалённым серверам
    - Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)
    - База данных Postgres (установка, настройка и использование)
    - Нереляционная база данных Redis (установка, настройка и использование)
    - Нагрузочное тестирование в Jmeter
    - Методология разработки Scrum
    - Python (Изучение основ. Создание клиент серверного приложения)

*Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)*

 12. Сделать коммит в одну строку.

`git add . >> git commit -m "add 2 file"`

 13. Отправить сразу 2 файла на внешний репозиторий.

`git push`

 14. На веб интерфейсе создать файл bug_report.txt.

`Add file >> Create new file`

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`Commit changes`

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

    bug_report:
      Bug_id: 2
      Title: "Add widget” button is not working on device
      Severity: high
      Priority: low
      Environment: Honor 8x JSN-L21 Android 10.0.0260
      Precondition: Clear the app from running
      Step_To_Reproduce: 1)Open app; 2)Click “Add Widget” button
      Actual_Result: 'Nothing happens, button is not working, widget is not created on any page'
      Expected_Result: Widget creation window appears/widget created

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`Commit changes`

 18. Синхронизировать внешний и локальный репозиторий TXT

`git pull`
