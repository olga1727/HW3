# Работа с Git

Git - распределенная система контроля версий, имеющая как локальные, так и удаленные репозитории.

СЕМИНАР 1

git init - инициализация локального репозитория

git status - информация о текущем состоянии репозитория

git add - добавить файл или файлы к следующему коммиту

git version - проверка установленной версии Git

git commit -m "message" - создание коммита

git log - вывод на экран истории всех коммитов с их хеш-кодами

git checkout - переход от одного коммита к другому

git checkout master - вернуться к актуальному состоянию и продолжить работу

git diff - вывод разницы между текущим файлом и законченным файлом

СЕМИНАР 2

git branch - вывести список всех имеющихся веток

git branch <branch_name> - создать новую ветку
 
git branch -d <branch_name> - удалить слитую ветку

git checkout <branch_name> - перейти на другую ветку

git merge <branch_name> - слияние веток

СЕМИНАР 3

git log - - graph - список коммитов с визуализацией межу ними

git log --graph - лог коммитов с визуализацией межу ними

git clone - она не только загружает все изменения, но и пытается слить  все ветки на локальном компьютере и в удаленном репозитории

git push - отправить свою версию репозитория во внешний репозиторий

git pull - позволяет скачать всё из текущего репозитория и автоматически сделать merge с нашей версией

git pull request - команда для предложения изменений (запрос на вливание изменений в репозиторий)