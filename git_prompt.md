# Git prompt
- git --version - проверка версии Git
- git config --global user.name “danila” - создание имени для Git
- git config --global user.email “email.ru” - создание email для Git
- git config --global core.autocrlf input
- git config --global core.safecrlf warn
- git config --global core.quotepath off
- git config --global init.defaultBranch main

- git add имя файла - добавление файла в отслеживаемые
- git commit -m "Подпись коммита" - создание и подпись коммита
- git status - проверка статуса
- git log --oneline - история коммита
- git add -А - добавление нескольких файлов в отслеживаемые
- git checkout хеш - переключение между коммитами
- git checkout - - возвращение к последнему коммиту
  
- git remote add origin ссылка на папку удалённого репозитория - связывание удаленного и локального репозиториев 
- git push -u origin main - отправка в удаленный репозиторий

Чтобы создать копию чужого проекта на GitHub, нужно нажать кнопку Fork на странице проекта

Чтобы клонировать удалённый репозиторий на компьютер, нужно скопировать ссылку по кнопке Code и затем выполнить в терминале команду git clone ссылка-на-репозиторий. После клонирования не забыть перейти в новую папку командой cd имя-папки

- git checkout -b имя-новой-ветки - создание новой ветки и переключение на нее
- git checkout имя-ветки - переключение между ветками
-  git merge имя-сливаемой-ветки - слияние веток (находясь в ветке, куда сливаем)
-    

