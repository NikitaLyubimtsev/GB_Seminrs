# Инструкция по работе с Git

Git это программа для контроля версий.

## Создание нового репозитория

Что бы создать новый репозиторий (инициализировать) нужно ввести команду:

    git init

## Проверка актуального состояния репозитория

Для того что бы проверить в каком состоянии находиться репозиторий необходимо ввести команду:

    git status

Для добавления файла в репозиторий необходимо ввести команду:

    git add <name_file>

    git commit
    git commit -m "message"
    git comit -am "message"

    git diff
    git diff <hash1> <hash2>

    git checkout <hash>

    git log
    git log --oneline
    git log --all
    git log --all --oneline
