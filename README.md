# GitHub_dz
JSON
 4. Создать внешний репозиторий c названием JSON.	<====>
  Зайти на личную страницу GitHub, нажать на кнопку "New", в "Repository name" написать название файла "JSON", отметить "Public", отметить "Add a README file" и нажать "Create repository"
 5. Клонировать репозиторий JSON на локальный компьютер.	<====> 
 Зайти в репозиторий "JSON", нажать кнопку "Code" и скопировать ссылку в формате HTTPS; заходим в GitBash и вводим git clone https://github.com/Mikel8913/GitHub_dz.git
 6. Внутри локального JSON создать файл “new.json”.	<====> touch new.json
 7. Добавить файл под гит.	<====> git add new.json; git status 
 8. Закоммитить файл.	<====> git commit -m "fourth commit"
 9. Отправить файл на внешний GitHub репозиторий.	<====> git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.	<====> 
 vim new.json; нажать "i"; написать
 {
  "name" : "Kozlov Mikhail Aleksandrovich",
  "age" : 32,
  "number of pets" : 0,
  "income" : 300
 }
 нажать "Esc" :wq
 11. Отправить изменения на внешний репозиторий.	<====> git add new.json; git status; git commit -m "fourth commit"; git push
 12. Создать файл preferences.json 	<====> touch preferences.json 
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.	<====> 
 vim preferences.json; нажать "i"; написать
 {
  "Favorite movies":"Alone at home,The Green Mile,Escape from Shawshank",
  "Favorite TV Shows":"Vikings,White collar,Game of thrones", 
  "Favorite food":"Pizza,Meat steak,Mushroom soup",
  "Favorite time of the year":"Summer",
  "The country you would like to visit":"Norway"
 }
 нажать "Esc" :wq
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON	<====>  
 touch sklls.json; vim sklls.json; нажать "i"; написать 
 {
             "skills":"Git Bash, GitHub, Postman, Charles, Android Studio,
              Python,DevTools, SQL, Fidler, Jmeter, Scrum, mobile testing"
 }
 нажать "Esc" :wq
 15. Отправить сразу 2 файла на внешний репозиторий.	<====> git add . ; git status; git commit -m "fifth commit"; git push
 16. На веб интерфейсе создать файл bug_report.json.	<====> 
 открыть GitHub; открыть репозиторий "JSON"; нажать на кнопку "Add file" выбрать "Create new file"; написать название файла "bug_report.json" и нажать "Commit new file"
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	<====> открыть файл "bug_report.json", нажать карандаж "edit this file" внести изменения; нажать "Commit changes"
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.	<====> открыть файл "bug_report.json", нажать карандаж "edit this file"; написать 
 {
    "timestamp": 1510417124782,
    "status": 500,
    "error": "Internal Server Error",
    "exception": "com.netflix.hystrix.exception.HystrixRuntimeException",
    "message": "ApplicationRepository#save(Application) failed and no fallback available.",
    "path": "/application"
 }

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	<====> нажать "Commit changes"
 20. Синхронизировать внешний и локальный репозиторий JSON	<====> в GitBash  написать git pull



XML
 21. Создать внешний репозиторий c названием XML.	<====> 
  Зайти на личную страницу GitHub, нажать на кнопку "New", в "Repository name" написать название файла "XML", отметить "Public", отметить "Add a README file" и нажать "Create repository"
 22. Клонировать репозиторий XML на локальный компьютер.	<====>
 Зайти в репозиторий "XML", нажать кнопку "Code" и скопировать ссылку в формате HTTPS; заходим в GitBash и вводим git clone https://github.com/Mikel8913/GitHub_dz.git
 23. Внутри локального XML создать файл “new.xml”.	<====> touch new.xml
 24. Добавить файл под гит.	<====> git add new.xml; git status 
 25. Закоммитить файл.	<====> git commit -m "the 8th commit"
 26. Отправить файл на внешний GitHub репозиторий. 	<====> git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.	<====>
  vim new.xml; нажать "i"; написать
 <?xml version="1.0" encoding="UTF-8" ?>
 <root>
   <name>Mikhail Aleksandrovich</name>
   <age>32</age>
   <income>350</income>
   <number_of_pets>0</number_of_pets>
 </root>
 нажать "Esc" :wq
 28. Отправить изменения на внешний репозиторий.	<====> git add new.xml; git status; git commit -m "the 8th commit"; git push
 29. Создать файл preferences.xml	<====> touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.	<====>
 vim preferences.xml; нажать "i"; написать
 <?xml version="1.0" encoding="UTF-8" ?>
 <root>
   <Favorite_movies>Alone at home,The Green Mile,Escape from Shawshank</Favorite_movies>
   <Favorite_TV_Shows>Vikings,White collar,Game of thrones</Favorite_TV_Shows>
   <Favorite_food>Pizza,Meat steak,Mushroom soup</Favorite_food>
   <Favorite_time_of_the_year>Summer</Favorite_time_of_the_year>
   <The_country_you_would_like_to_visit>Norway</The_country_you_would_like_to_visit>
 </root>
 нажать "Esc" :wq
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML.		<====>
 touch sklls.xml; vim sklls.xml; нажать "i"; написать 
  <?xml version="1.0" encoding="UTF-8" ?>
 <skills>Git Bash, GitHub, Postman, Charles, Android Studio,Python,DevTools, SQL, Fidler, Jmeter, Scrum, mobile testing</skills>
 нажать "Esc" :wq
 32. Сделать коммит в одну строку.	<====> git add . && git commit -m "ninth commit"
 33. Отправить сразу 2 файла на внешний репозиторий.	<====> git push
 34. На веб интерфейсе создать файл bug_report.xml.	<====>	открыть GitHub; открыть репозиторий "XML"; нажать на кнопку "Add file" выбрать "Create new file"; написать название файла "bug_report.xml" и нажать "Commit new file"
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	<====> открыть файл "bug_report.xml", нажать карандаж "edit this file" внести изменения; нажать "Commit changes"
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.	<====>   открыть файл "bug_report.xml", нажать карандаж "edit this file"; написать 
  <?xml version="1.0" encoding="UTF-8" ?>
 <root>
    <timestamp>1510417124782</timestamp>
    <status>500</status>
    <error>Internal Server Error</error>
    <exception>com.netflix.hystrix.exception.HystrixRuntimeException</exception>
    <message>ApplicationRepository#save(Application) failed and no fallback available.</message>
    <path>/application</path>
 </root>
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	<====> нажать "Commit changes"
 38. Синхронизировать внешний и локальный репозиторий XML	<====> в GitBash  написать git pull


TXT
 1. Создать внешний репозиторий c названием TXT.	<====>
 Зайти на личную страницу GitHub, нажать на кнопку "New", в "Repository name" написать название файла "TXT", отметить "Public", отметить "Add a README file" и нажать "Create repository"
 2. Клонировать репозиторий TXT на локальный компьютер.		<====>
 Зайти в репозиторий "TXT", нажать кнопку "Code" и скопировать ссылку в формате HTTPS; заходим в GitBash и вводим git clone https://github.com/Mikel8913/GitHub_dz.git
 3. Внутри локального TXT создать файл “new.txt”.	<====> touch new.txt
 4. Добавить файл под гит.	<====> git add new.txt; git status 
 5. Закоммитить файл.	<====>  git commit -m "the eleventh commit"
 6. Отправить файл на внешний GitHub репозиторий.	<====> git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.	<====>
 vim new.xml; нажать "i"; написать
 Name  Mikhail Aleksandrovich,
 age  32,
 number of pets 0,
 income 350
 нажать "Esc" :wq
 8. Отправить изменения на внешний репозиторий.		<====> git add new.txt; git status; git commit -m "the eleventh commit"; git push
 9. Создать файл preferences.txt	<====> touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.	<====>
 vim preferences.txt; нажать "i"; написать
 Favorite movies: Alone at home,The Green Mile,Escape from Shawshank.
 Favorite TV Shows: Vikings,White collar,Game of thrones. 
 Favorite food: Pizza,Meat steak,Mushroom soup.
 Favorite time of the year: Summer.
 The country you would like to visit: Norway.
 нажать "Esc" :wq
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT		<====>
 touch sklls.txt; vim sklls.txt; нажать "i"; написать 
 Skills: Git Bash, GitHub, Postman, Charles, Android Studio, Python, DevTools, SQL, Fidler, Jmeter, Scrum, mobile testing.
 12. Сделать коммит в одну строку.	<====> git add . && git commit -m "twelve commit"
 13. Отправить сразу 2 файла на внешний репозиторий.	<====> git push
 14. На веб интерфейсе создать файл bug_report.txt.	<====> открыть GitHub; открыть репозиторий "TXT"; нажать на кнопку "Add file" выбрать "Create new file"; написать название файла "bug_report.txt" и нажать "Commit new file"
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	<====> открыть файл "bug_report.txt", нажать карандаж "edit this file" внести изменения; нажать "Commit changes"
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.	<====> открыть файл "bug_report.txt", нажать карандаж "edit this file"; написать 
 timestamp : 1510417124782,
 status : 500,
 error : Internal Server Error,
 exception : com.netflix.hystrix.exception.HystrixRuntimeException,
 message : ApplicationRepository#save(Application) failed and no fallback available,
 path : /application
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	<====> нажать "Commit changes"
 18. Синхронизировать внешний и локальный репозиторий TXT	<====> git pull
