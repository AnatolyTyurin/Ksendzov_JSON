1. Создать внешний репозиторий c названием JSON. – “done”
2. Клонировать репозиторий JSON на локальный компьютер.–

git clone https://github.com/AnatolyTyurin/Ksendzov_JSON.git

3. Внутри локального JSON создать файл “new.json”. - touch new.json
4. Добавить файл под гит. – git add new.json
5. Закоммитить файл. – git commit –m “add hw task1”
6. Отправить файл на внешний GitHub репозиторий. – git push
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

vim new.json

{

        "first_name":"Anatoly",

        "last_name":"Tyurin",

        "age":35,

        "pets":"-",

        "desired salary":"USD 1000"

}

11. Отправить изменения на внешний репозиторий. –
git commit -am "add text to new.json”
git push
12. Создать файл preferences.json - touch preferences.json
13. В файл preferences.json добавить информацию о своих предпочтениях - (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

vim new.json

{

        "favourite film":"Existenz",

        "favourite TV series":"Breaking Bad",
        
        "favourite food":"mama's homemade food",
        
        "favourite season":"summer",
        
        "desired country to visit":"State of Maine, the USA"

}

14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

vim skills.json

{

        "knowledge to learn":{
                "basic testing theory":[
                        "QA,QC,testing",
                        "bug reports",
                        "testing documentation",
                        "types and methods of testing",
                        "SDLC",
                        "STLC"
                ],
                "HTTP":[
                        "client-server architecture",
                        "HTTP methods of requests",
                        "HTTP server response codes",
                        "Structures of HTTP requests and responses"
                ],
                "data interchange format":[
                        "JSON",
                        "XML"
                ],
                "API":[
                        "Postman",
                        "JS",
                        "API autotests"
                ],
                "sniffing":[
                        "Charles",
                        "Fiddler"
                ],
                "DevTools":[
                        "Google Chrome",
                        "FireFox"
                ],
                "VPN":[
                        "General info",
                        "Tool options"
                ],
                "Mobile testing":[
                        "IOS",
                        "Android",
                        "XCode",
                        "Android Studio",
                        "ADB",
                        "Proxy and vpn settings on iOS and Android",
                        "Sniffing traffic using Charles and Fiddler on IOS and Android"
                ],
                "Linux Terminal":[
                        "Copying, creating, viewing, moving files and etc.",
                        "Base of Bash scripting",
                        "Access to remote servers"
                ],
                "SQL":[
                        "Create, Delete, Drop, Insert Into, Select, From, Where, Join",
                        "PostgreSQL",
                        "Redis"
                ],
                "Load testing":"Jmeter",
                "Development methodology":"SCRUM",
                "Programming language":"Base of Python"
}

15. Отправить сразу 2 файла на внешний репозиторий. – 

$ git add . && git commit -am "adding preferences.json and skills.json" && git push

16. На веб интерфейсе создать файл bug_report.json. – “done”
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. – “done”
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. – “done”
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе. – “done”
