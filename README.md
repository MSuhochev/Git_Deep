# Git_Deep
For home works to Git
объединяем ветки майн и мастер
гит отказывается их мержить выдавая "fatal: refusing to merge unrelated histories"
используем флаг --allow-unrelated-histories
ветки объединились
удаляем локальную ветку мастер - git branch -d master
удаляем ветку мастер из внешнего репо - git push origin --delete master
