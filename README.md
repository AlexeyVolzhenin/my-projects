# my-projects

# Базовые команды git 

## Проверка работоспособности и версии git 

```bash
git --version    
```

## Настройка git с помощью настройки имени и почты

```bash
git config --global user.name "My Name"
git config --global user.email "myemail@example.com"
```
## Проверка настроек

```bash
git config --list
```

## Проверка текущего статуса репозитория
``` bash
git status
```

## Проверка всех логов (история коммитов)

```bash
git log
```

## Проверка удаленных подключений

```bash
git remote
```


## Добавление файла в отслеживаемое состояние

```bash
git add name_of_file
```

## Подтверждение изменений всех файлов в отслеживаемом состоянии
```bash 
git commit =m "my message of thos commit"
```
## Отправка локального репозитория на удаленный репозиторий

Отправка на удаленный репозиторий, который мы назвали origin, текущего репозитория по ветке main
```bash
git push -u origin main
```