1. Инициализируем локальный проект с помощью команды:

	- git init

2. Создаем файл README.md 

	- touch README.md

3. Индексируем файл 

	- git add README.md

4. Коммитим 

	- git commit -m "Initial commit"

5. Подключаем удаленный репозиторий github 

	- git remote add origin https://github.com/Nirwash/AstonIntensive1.git

6. Пушим на гитхаб 

	- git push -u origin master
	
7. Переключаемся на ветку master, делаем некоторые изменения, коммитим и пушим на гитхаб

	- git checkout master
	- git add README.md
	- git commit -m "5th commit from master branch"
	- git push 
	
8. Делаем еще один коммит в мастер ветку и пушим на гитхаб.

9. Сливаем ветки

	- git merge newBranch