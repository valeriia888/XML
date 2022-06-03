# XML
 21. Создать внешний репозиторий c названием XML: create a new repository
 22. Клонировать репозиторий XML на локальный компьютер: git clone git@github.com:valeriia888/XML.git
 23. Внутри локального XML создать файл “new.xml”: touch new.xml
 24. Добавить файл под гит: git add new.xml
 25. Закоммитить файл: git commit -m "added xml file"
 26. Отправить файл на внешний GitHub репозиторий:   git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML: cat >>  new.xml
28. Отправить изменения на внешний репозиторий: git add . && git commit -m "added  information about me in xls format" && git push
29. Создать файл preferences.xml: touch preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:
cat >> preferences.xml
31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML: 
touch skils.xml && cat >> skils.xml
 32. Сделать коммит в одну строку: git commit -m skils.xml "added information about my skils in xml format" && git commit -m preferences.xml "added information about my preferences in xml format"
 33. Отправить сразу 2 файла на внешний репозиторий: git push preferences.xml skils.xml
 34. На веб интерфейсе создать файл bug_report.xml:  add file button
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе: commite new file 
 36. На веб интерфейсе модифицировать файл bug_report.xml,добавить баг репорт в формате XML: edit
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе: commite new file
 38. Синхронизировать внешний и локальный репозиторий XML: git pull
