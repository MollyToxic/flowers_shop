# project
 
1) для инициализации гит репозитория команда git init
2) git status - посмотреть изменения
3) git add (название файла или ., чтобы добавить все) 
4) git commit -m "какое то сообщение"
    1) --amend исправить последний коммит
5) git branch - посмотреть ветки
6) git branch <имя>- создать новую ветку
7) git checkout <имя> - перейти на ветку
8) git checkout -b <имя> создать новую ветку и перейти на неё
9) git merge - объединить ветки. нужно находится в целевой . параметр это название ветки которую вливаем
10) git reset - сбросит изменения к последнему коммиту
    1) --hard - к последнему коммиту

1) git remote - работа с удаленным репозиторием.
    1) git remote -v - посмотерть удаленные репозитории
    2) git remote add <имя> ссылка
    3) git pull <имя репы> <имя ветки> - забрать изменения
    4) git push <имя репы> <имя ветки> - отпраивить изменения 