# Git_JSON

## JSON
4. Создать внешний репозиторий c названием JSON.
>Git_JSON
5. Клонировать репозиторий JSON на локальный компьютер.
>git clone git@github.com:vv-vasilyev08/Git_JSON.git
6. Внутри локального JSON создать файл “new.json”.
>touch new.json
7. Добавить файл под гит.
>git add new.json
8. Закоммитить файл.
>git commit -m "add first file"
9. Отправить файл на внешний GitHub репозиторий.
>git push
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
>cat >> new.json  
>{  
>"Full name": "Лучший Пухляш Неотразимый",  
>"Age": 22,  
>"Number of pets": 5,  
>"Future desired salary": 120000  
>}  
>CTRL+D
11. Отправить изменения на внешний репозиторий.
>git add . ; git commit -m "changes json file" ; git push
12. Создать файл preferences.json
>touch preferences.json
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
>cat >> preferences.json  
>{  
>"Favorite movie": "На основе реальных событиях",  
>"Favourite TV show": "Нету",  
>"Favorite food": "Овощное рагу",  
>"Favorite time of year": "Лето",  
>"Country to which. would like to visit": "Не знаю"  
>}  
>CTRL+D
14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
>cat >>  skills.json  
>{  
>"Skills": "Linux, Bash, Git, GitHub, API, HTTP/HTTPS, Web testing, Mobile testing, Proxy, VPN, SQL, JMeter"  
>}  
>CTRL+D
15. Отправить сразу 2 файла на внешний репозиторий.
>git add . ; git commit -m "add two files" ; git push
16. На веб интерфейсе создать файл bug_report.json.
>Создать файл в GitHub bug_report. json
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>Файл bug_report. json закоммитить в GitHub
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
>Модифицировать в GitHub файл bug_report. json
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>Сделать коммит bug_report. json
20. Синхронизировать внешний и локальный репозиторий JSON
>git fetch  
>git pull
