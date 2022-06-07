 # 1. Создать внешний репозиторий с названием JSON.
 
  _Перехожу на `github`, создать новый репозиторий, добавляю название, сохраняю._
 
 # 2. Клонировать репозиторий JSON на локальный компьютер.

  git clone  `https://github.com/Ilyamrkl/JSON.git`

 # 3. Внутри локального JSON создать файл “new.json”.
 
   cd TXT
   
   touch new.json

# 4. Добавить файл под гит.

    git add .

 # 5. Закоммитить файл.

    git commit -m 'Create new.json'

 # 6. Отправить файл на внешний GitHub репозиторий.

    git push

 # 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

    vim new.json
  
    _перехожу в режим редактирования'ins'заполняю необходимую информацию_
  
 # 8. Отправить изменения на внешний репозиторий.

    git commit -am 'Update new.json' && git push

# 9. Создать файл preferences.json
 
     touch preferences.json
 
 # 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

    vim preferences.json
    
    `перехожу в режим редактирования'ins'заполняю необходимую информацию`

 # 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

    vim skils.json
    
    `перехожу в режим редактирования'ins'заполняю необходимую информацию`

 # 12. Отправить сразу 2 файла на внешний репозиторий.

    git push

    
 # 13. На веб интерфейсе создать файл bug_report.json.

    веб интерфейс Add file - Create new file 

 # 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

   `коммит Create bug_report.xml и сохранить`

 # 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 
    `редактирую файл/заполняю необходимую информацию`

 # 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
    коммит Update bug_report.txt и сохранение Commit changes
 
 # 17. Синхронизировать внешний и локальный репозиторий JSON

    git push 

