# Авторизация
```
git config --global user.name " "
```
```
git config --global user.email " "
```
# Инициализация GIT репозитория
```
git init
```
# Добавляем в индекс файл
```
git add README.md
```
# Создать commit
```
git commit -m "name"
```
# Cоздать ветку
```
git branch -M main
```
# Подключение к репозиторию
```
git remote add origin ссылка
```
# Проверить подключение к репозиторию
```
git push -u origin main
```
# Создать новый commit
```
git commit -s "name"
```
# Создать новую ветку
```
git branch -S name
```
# Перейти к основной ветви
```
git checkout main
```
# Слиять ветви
```
git merge name
```
# Удалить ветвь name
```
git branch -d name
```
# Привезать и преобразовть источник
```
git pull --rebase origin main
```
# Передать изменение в репозиторий
```
git push origin main
```