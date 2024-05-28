1.Переходим в рабочую папку:

$ cd C:

2.Создаем новую папку NEWREPOZIT:

$ mkdir NEWREPOZIT

3. Переходим в созданную папку:

$ cd NEWREPOZIT

4. Создаем новый локальный репозитарий:

$ git init

5. Создаем файл описания README.md

$ touch README.md

6. Добавляем эту инструкцию в файл README.md

7. Добавляем\подключаем файлы в  репозитарий  делаем первый коммит:

$ git add -A
$ git commit -m "Первый коммит"

8. Подключим удаленный репозитарий.Перейдите на https://github.com и войдите в свой аккаунт. Нажмите кнопку New repository (Новый репозиторий).
   На открывшейся странице введите имя репозитория (Repository name) и нажмите кнопку Create repository. 
   В своем локальном репозитории теперь выполните команду:
 
 $ git remote add NEWREPOZIT https://github.com/username/myproject.git
  
 9. Отправим все наши изменения на удаленный репозитарий:

$ git push -u origin master