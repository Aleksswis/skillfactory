1.создайте файл INFO.md с помощью команды echo "text" > INFO.md 2. Создайте файл file-feature-1.txt с произвольным содержимым (например, текст из предыдущей главы) и зафиксируйте его в Git. : echo "text" > file-feature-1.txt . зафиксировать его в Git: git add .   git commit -am "text"
3. создайте файл file-feature-2.txt с другим содержимым : echo "text" > file , измените файл file-feature-1.txt : vi file . зафиксировать  в Git: git add .   git commit -am "text"
4. создайте file-feature-3.txt (произвольный текст) : echo "text" > file  и удалите file-feature-1.txt: rm file .
5. Редактирование файла INFO.md : vi file 

