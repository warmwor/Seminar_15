# Начало работы с GIT

## Начальные команды

### Для регистрации GIT необходимо:
1. **git config --global user.name ""Bogdan""**
2. **git config --global user.email ""@mail.ru""**

### Для перехода в папку для инициации:
1. cd`/Desktop
2. git init

### Для создания новой папки используют команду:

**mkdir my-project**

### Переход в папку:

**cd my-project**

### Команда _*pwd*_ - отразит полностью директорию, где находится тиницированная папка.

### Создание файла с текстом:

**echo "Some text" > file.txt**

### Просмотр списка файлов в папке:

**ls**

### Чтение файла:

**cat file.txt**

### Удаление файла:

**rm file.txt**

### Для отображения скрытых файлов в папке используется следующая команда:

**ls -Force**

или

**ls -la**

### При просмотре статуса GIT используется (подготовка к сохранению изменений в репозиторий):

**Git status**

### Команда для подготовки файлов перед commit, т.е. сохранение всех изменений:

**git add .** 

### Чтобы сохранить конкретный файл перед commit используют:

**git add ./<file name>**

### Для записи изменений в репозитории прописывают:

**git commit -m "message"**

### Для отображения всех commit необходима команда:

**git log**

### Переход на определенную версию проекта осуществляется следующим образом:

**git checkout <commit hash>**

### Переход на определенную ветку проекта осуществляется следующим образом:

**git checkout <branch name>**

### Узнать тип параметры файла:

**git cat-file -t <первые символы SHA1>**

**git cat-file -p <первые символы SHA1>**

## Ветки в git

### Для создания ветки и перехода в неё существует команда:

**git branch checkout -b <название ветки>**

### Переименование происходит:

**git branch checkout -m <название ветки>**

### Удалить ветку возможно так(кроме текущей):

**git branch -d <название ветки>**

### Переименовать ветку:

**git branch -m main**

### Слияние веток(после перехода в текущую ветку):

**git merge <feature branch name>**

## Changes from local repository

## Changes from github to local
