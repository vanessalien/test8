# Команды Git
## Создание репозитория на локальном компьютере
```
git config --global user.name ""
```
```
git config --global user.email ""
```
>залогиниться
```
pwd
```
>показывает текущую папку
```
ls -la
```
>показывает содержимое папки
```
cd "путь к папке"
```
>указывает путь к папке
```
git init
```
>создает репозиторий из текущей папки
## Запись изменений в репозиторий
```
git add .
```
>добавляет файлы из репозитория в индекс
```
git commit -m ""commit1
```
>сохраняет текущие изменения (добалвяет коммит)
```
git status
```
>показывает состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)
```
git log
```
>показывает историю коммитов
```
git clone https://github.com/YourLoginOnGithub/GitName.git
```
>клонирует удаленный репозиторий в одноименную директорию
## Перенос репозитория на удаленный компьютер
```
git remote add origin https://github.com/YourLoginOnGithub/GitName.git
```
>подключает локальный репозиторий к удаленному
```
git push -u origin main
```
>переносит локальный репозиторий на удаленный компьютер
## Работа с ветками
```
git branch -M main
```
>создает основную ветку
```
git checkout -b BranchName
```
>создает новую ветку и осуществляет переход к ней
```
git checkout BranchName
```
>осуществляет переход между ветками
```
git branch
```
>показывает список веток и текущую ветку
```
git merge BranchName
```
>сливает текущую ветку с указанной
```
git branch -d BranchName
```
>удаляет указанную ветку
