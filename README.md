# Lesson 3

## Git: работа с удаленным репозииторием

### Склонировать удаленный репозиторий в текушую директорию
```
git clone <url>
```
Пример: ```git clone https://github.com/Bulvinkoln/SEM_Origin_01.07.2022.git```


### Просмотр удалённых репозиториев
```
git remote
```

### Добавление удалённого репозитория
```
git remote add <remote-name> <url>
```
Пример: ```git remote add origin https://github.com/Bulvinkoln/SEM_Origin_01.07.2022.git```


### Получение данных с удаленного репозитория (не применяя их в локальную ветку)
```
git fetch <remote-name>
```
Пример: ```git fetch origin```


### Получить данные с удаленного репозитория и применить их в локальную ветку
```
git pull <remote-name>
```
Пример: ```git pull origin```


### Отправить локальные изменения в удаленный репозиторий (для новой локальной ветки)
```
git push -u <remote-name> <branch_name>
```
Пример: ```git push -u origin lesson_3```

### Отправить локальные изменения в удаленный репозиторий (для ветки, которая уже существует в удаленном репозитории)
```
git push <remote-name> <branch-name>
``` 
Пример: ```git push origin lesson_3```