Вторая строка
Третяя строка
Четвёртая строка с конфликтом
Конфликтная четвёртая строка

To remove the last commit from git, you can simply run git reset --hard HEAD^ If you are removing multiple commits from the top, you can run git reset --hard HEAD~2 to remove the last two commits. You can increase the number to remove even more commits.
