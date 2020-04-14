# Вы можете встроить NeuroStartUp в ваши приложения с помощью следующих сниппетов (кусочков) кода.

* JavaScript:
```
<script src="https://localhost/neuro.sdk.min.js"></script>
```
* Java (Maven):
```
<dependency>
  <groupId>neuro</groupId>
  <artifactId>sdk</artifactId>
  <version>1.0.0</version>
</dependency>
```
* iOS (добавьте код в ваш Podfile):
```
platform :ios, '8.0'
pod "neuro-ios-sdk"
```
# **GIT** - *распределённая система контроля версий*

# КЛЮЧЕВЫЕ ФУНКЦИИ GIT:
1. Создание новых версий файлов (фиксация изменений);
1. Откат изменений (возврат к предыдущим версиям);
1. Работа над параллельными изменениями;
1. Работа в команде;
1. Анализ истории и авторства изменений;

## УСТАНОВКА
[Для Windows](https://git-scm.com/download/win)

[Для Mac](https://git-scm.com/download/mac)


## ОБЩАЯ СХЕМА РАБОТЫ
1. Создание локального репозитория для проекта;
1. Добавление файлов (изменённых) в список отслеживания (stage area
или index);
1. Фиксация изменений в файлах (commit).

### СОЗДАНИЕ РЕПОЗИТОРИЯ
Репозиторий создаётся в конкретном каталоге с помощью команды:
```
$ git init
Initialized empty Git repository in C:/project/.git/
```
### ДОБАВЛЕНИЕ ФАЙЛОВ
Git будет следить только за теми файлами, которые вы добавили в «список
отслеживаемых».
Cделать это можно с помощью команды:
```
$ git add index.html
```
где index.html – это имя добавляемого файла.

### ФИКСАЦИЯ ИЗМЕНЕНИЙ (КОММИТ)
Для фиксации изменений используется команда git commit (после
этого откроется редактор для указания комментария). В редакторе nano
нужно будет нажать клавиши Ctrl + O, Ctrl + X для записи и выхода из
редактора (см. сокращения).

```
$ git commit
[master (root-commit) 4ad7e09] Первоначальная версия
4 files changed, 14 insertions(+)
create mode 10064 README.md
create mode 10064 css/style.css
create mode 10064 index.html
create mode 10064 js/app.js
```
### СПРАВКА
Вся справка по командам предоставляется самим Git:
* git – краткая справка по git;
* git help <command> – справка по конкретной команде git

![логотип Заказчика](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)


