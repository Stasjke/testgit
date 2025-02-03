git init  Если вы находитесь в правильном каталоге, но он не является репозиторием, выполните

git remote add origin [link]  подключить к проекту гит

 git reset [file]  - убрать файл из stage 
 git reset --hard - отменяет последние изменения до последнего коммита
-git push origin master
-git branch - название ветки
-git remote -v ( ссылка на репозиторий )


.gitignore файл указывает что не будет отслеживаться git 

порядок действий при изменениях :

1.git status  - для проверки изменений


2.git add[files]  - добавляет файлы в stage (git add .)
3.git commit -m "comment"  (прочитать коммент можно при помоши git log)
4.git log / git log --oneline  (подробная информация / краткая информация о comment)
5. git push [rep_link] [branch_name] -  

