# XML
 21. Создать внешний репозиторий c названием XML: create a new repository
 22. Клонировать репозиторий XML на локальный компьютер: git clone git@github.com:valeriia888/XML.git
 23. Внутри локального XML создать файл “new.xml”: touch new.xml
 24. Добавить файл под гит: git add new.xml
 25. Закоммитить файл: git commit -m "added xml file"
 26. Отправить файл на внешний GitHub репозиторий:   git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). 
Всё написать в формате XML:
cat >>  new.xml
<?xml version = "1.0"?>
<information-about-me>
    <name>Lanchinskaia Valeriia</name>
    <age>25 years</age>
    <number-of-pets>two</number-of-pets>
    <future-desired-salary>2000$</future-desired-salary>
</information-about-me>

ctrl+c
или открыть new.json с помощью Visual code
28. Отправить изменения на внешний репозиторий: git add . && git commit -m "added  information about me in xls format" && git push
29. Создать файл preferences.xml: touch preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:
cat >> preferences.xml
<?xml version = "1.0"?>
<my-preferences>
    <my-favorite-movie>The intern</my-favorite-movie>
    <my-favorite-series>The friennds</my-favorite-series>
    <my-favorite-season>autumn</my-favorite-season>
    <country-I-would-like-to-visit>Norway</country-I-would-like-to-visit>
</my-preferences>

ctrl+c
или открыть new.json с помощью Visual code

31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML: 
touch skils.xml && cat >> skils.xml
<?xml version = "1.0"?>
<skils>
    <skil>Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC</skil>
    <skil>What is a client-server architecture</skil>
    <skil>HTTP Methods of requests to the server</skil>
    <skil>Structures of HTTP requests and responses</skil>
    <skil>What is JSON, XML. Their structure</skil>
    <skil>API testing via Postman (JS, API autotests)</skil>
    <skil>Removing and reading logs from an external server</skil>
    <skil>Sniffing http web traffic via Charles and Fiddler</skil>
    <skil>Dev Tools of web browsers (Google Chrome, FireFox)</skil>
</skils>

ctrl+c
или открыть new.json с помощью Visual code
 32. Сделать коммит в одну строку: git commit -m skils.xml "added information about my skils in xml format" && git commit -m preferences.xml "added information about my preferences in xml format"
 33. Отправить сразу 2 файла на внешний репозиторий: git push preferences.xml skils.xml
 34. На веб интерфейсе создать файл bug_report.xml:  add file button
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе: commite new file 
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML: edit
<?xml version = "1.0"?>
<bug-report>
    <ID>1</ID>
    <Reporter>Valeriia Lanchinskaia</Reporter>
    <Severity>tweak</Severity>
    <Priority>normal</Priority>
    <Status>accepted</Status>
    <Product-Build>2.1.1</Product-Build>
    <Reproducibility>always</Reproducibility>
    <Platform>Google Chrome 91.0.4472.124</Platform>
    <OS-Version>10*64 </OS-Version>
    <OS>Windows</OS>
    <Summary>The 404 error is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer</Summary>
    <Description>The 404 error is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer</Description>
    <Steps-To-Reproduce>1. Open the site https://prom.ua/ua/ 
    2. Scroll down the page to the footer.
    3. Click the "Про prom.ua" link.
    4. Click the "Микола Палієнко" link.
    5. Pay attention to the 404 error</Steps-To-Reproduce>
    <Actual-result>The 404 error is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer</Actual-result>
    <Expected-result>The information about selected person is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer</Expected-result>
    <Additional-Information>Video https://drive.google.com/file/d/1SNhHpTTgxswxR6CtnqGxYQRTIJ0X0Waa/view?usp=drivesdk</Additional-Information>
    <Attached-Files>https://drive.google.com/file/d/16rH-U0oI1kh_vhvnuM18WsmwPFCctaRx/view?usp=sharing$</Attached-Files>
</bug-report>

ctrl+c
или открыть new.json с помощью Visual code
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе: commite new file
 38. Синхронизировать внешний и локальный репозиторий XML: git pull
