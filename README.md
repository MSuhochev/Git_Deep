# Git_Deep
For home works to Git
объединяем ветки майн и мастер
гит отказывается их мержить выдавая "fatal: refusing to merge unrelated histories"
используем флаг --allow-unrelated-histories
ветки объединились
<<<<<<< HEAD
удаляем локальную ветку мастер - git branch -d master
удаляем ветку мастер из внешнего репо - git push origin --delete master

Второе домашнее задание по курсу делаем в этом же файле
<<<<<<< HEAD
вносим второе изменение в файл для домашнего задания 2
<<<<<<< HEAD
вносим 3-е изменение в файл для домашнего задания 2
=======
>>>>>>> parent of a0b2262 (finally commit to first  home work)
=======
>>>>>>> parent of baff331 (second commit to home work 2)
=======
>>>>>>> parent of 3909438 (third commit to home work 2)
