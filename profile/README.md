# Пространство для студентов и преподавателей кафедры "Прикладная Математика"

## Работа с репозиториями

1. Основная ветка main или master
2. Каждое изменение после инициализации репозитория должно быть в рамках отдельной git ветки.
3. Мерж (merge) ветки в основную ветку осуществляется через создание [Pull Request (PR)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
4. После создание PR, нужно добавить несколько [reviewers](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review) из числа группы.
5. Если всё хорошо, PR принимается и осуществляется merge. Если есть какие-то коментарии и замечания, их нужно учесть.

## Commit convention
1. Language: English
2. Naming: verb-subject-details
3. Forbidden to use meaningless names and same names for series of commits
#### Bad examples
    fix
    aaaaa
    minor bugfix
#### Good examples
    added commit convention to README
    fixed a bug in image proccessing module

## Branch naming
You should name your branch this way: \*issue number\*\_\*feature name\*
#### Example
    1_commit_convention
