# Шпаргалка по форматированию описания проекта в Git (markdown)

## Курс Яндекс.Практикум

[Основы Git](https://practicum.yandex.ru/git-basics/?from=catalog)

Курс дает первичные и _базовые_ знания в рамках работы с **Git репозиторием**

---

Создаем папку проекта
```
mkdir git_reference
```

По умолчанию git init создаёт ветку master, где будут размещаться коммиты. Задать имя дефолтной ветки можно с помощью команды git config --global init.defaultBranch main.

Git init — команда для создания нового репозитория в системе управления версиями Git. 4 Она создаёт в директории пустой подкаталог .git, где будет храниться информация об истории коммитов, тегах и ходе разработки проекта. 

```
git init
```

Далее необходимо создать репозиторий в GtHub и связать его с локальным командой
```
git remote add origin git@github.com:atagankin/git_reference.git
```

Второй вариант - это клонирование репозитория из GitHub
```
git clone git@github.com:atagankin/git_reference.git
```