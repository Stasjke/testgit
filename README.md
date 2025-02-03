git init  Если вы находитесь в правильном каталоге, но он не является репозиторием, выполните

git remote add origin [link]  подключить к проекту гит

 git reset [file]  - убрать файл из stage 
 git reset --hard - отменяет последние изменения до последнего коммита
-git push origin master
-git branch - проверка веток
-git remote -v ( ссылка на репозиторий )
.gitignore файл указывает что не будет отслеживаться git 


порядок действий при изменениях :
1.git status  - для проверки изменений
2.git add[files]  - добавляет файлы в stage (git add .)
3.git commit -m "comment"
4.git log / git log --oneline  (подробная информация / краткая информация о comment)
5. git push [rep_link] [branch_name] -  

/*-git push origin master
//
git branch develop - создали ветку develop
git checkout [name_branch] переключение на ветку другую
перенос изменений из веток в другие:
1.
git pull request  на github 
git pull [rep_link] [branch_name] 
git pull origin master - для загрузки файлов из github
git branch -D [develop]  удаление ветки [develop]

2.
git merge [branch] 
git merge feature/main-page */