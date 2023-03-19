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
	
7. Добавляем новую ветвь и сразу переходим на нее

	- git checkout -b newBranch
	
8. Создаем новый файл Hello.txt

	- touch Hello.txt
	
9. Редактируем файлы Hello.txt и README.md, индексируем и коммитим

	- git add Hello.txt
	- git add README.md
	- git commit -m "Second commit"
	
10. Пушим на гитхаб с созданием новой ветки

	- git push origin newBranch