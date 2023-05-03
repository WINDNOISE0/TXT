TXT
 
 1. Создать внешний репозиторий c названием TXT.

 2. Клонировать репозиторий TXT на локальный компьютер.
 $ git clone https://github.com/WINDNOISE0/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
 # cd TXT
 # cat > new.txt

 4. Добавить файл под гит.
 $ git init
 $ git add .

 5. Закоммитить файл.
 $ git commit -m "Created new file"

 6. Отправить файл на внешний GitHub репозиторий.
 $ git remote add origin https://github.com/WINDNOISE0/TXT.git
 $ git branch -M main
 $ git push -u origin main

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 # nano new.txt
 Name: Yaroslav
 Sername: Yaroslavov\n
 Patronymic: Yaroslavovich\n
 Age: 25\n
 Count home pets: 1\n
 Future expected salary: 1000$+\n

 8. Отправить изменения на внешний репозиторий.
 $ git push -u origin main

 9. Создать файл preferences.txt
 # cat > preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 # nano preferences.txt
 favorite movie: fear and loathing in las vegas
 favorite TV-show: none
 favorite food: delicious
 favorite season: summer
 country which I want visit: Spain

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 # nano sklls.txt
 will studys skills: Bash terminal, Git system of control version, SQL, Postman, Jmeter, AndroidStudio, Charles, DB  Browser, Fiddler

 12. Сделать коммит в одну строку.
 $ git add .
 $ git commit -m "Add two files"

 13. Отправить сразу 2 файла на внешний репозиторий.
 $ git push -u origin main

 14. На веб интерфейсе создать файл bug_report.txt.

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 number ID:1
 Title: Link 'create new account' Global Menu isn't open when clicking
 Seveity: critical
 Priority:hight
 STR:
   1: Open link
   2:Tap to button 'create new account'
  Expected Result:"Registration's window is opened,
  Actual Result":"nothing happens, link isn't opened

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 18. Синхронизировать внешний и локальный репозиторий TXT
 $ git pull
 
