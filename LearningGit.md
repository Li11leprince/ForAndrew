1. Создать файл LearningGit.md  touch LearningGit.md
В него нужно заносить каждый пункт задачи и соответствующее решение
    1. Закомитить   git add .; git commit -m "Add learninggit file"
    2. Запушить git push
2. Создать ветку main на основе master  git branch main
3. Создать ветку dev на основе main git checkout main; git branch dev
4. Удалить ветку master git branch -D master
5. Перенести изменения в remote репозиторий
- git push --all
- change the default branch on github
- git push origin --delete master 
6. Переименовать dev в develop  git branch -m develop
7. Обновить remote репозиторий git push origin :dev develop
8. Сделать ветку experiment/git-merge   git branch experiment/git-merge (based on the main branch)
9. Изменить удалить первую строчку README.md
10. Закомитить  git commit -m "Change first line"
11. Добавить новую строчку в конец файла // контент произвольный
12. Закоммитить
13. Запушить
14. Переключиться на ветку develop
15. Изменить первую строчку README.md
16. Добавить новую строку в в конец файла README.md// контент произвольный
17. Закоммитить и запушить
18. Сделать Pull Request(Merge Request) из ветки experiment/git-merge в develop
19. Локально смержить ветку develop в experiment/git-merge и разрешить конфликты
20. Закоммитить и запушить
21. Убедиться, что нет конфликтов
22. Смержить Merge Request
