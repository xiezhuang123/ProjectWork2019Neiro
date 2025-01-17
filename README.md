﻿# ProjectWork2019Neiro
Проектная работа 2019 - Нейроинтерфейс

[Ссылка на проект](https://project.spbstu.ru/mod/opd/view.php?pid=4&rid=18)

# Работа с GitHub
## 1. Начало работы

### Настройка:
  1. Вводим в git bash:
  ```
    $ git config --global user.email "you@example.com"
    $ git config --global user.name "Your name"
    $ git config --global core.editor notepad
  ```
  2. Заходим на [страницу проекта](https://github.com/RazuvaevDD/ProjectWork2019Neiro) , жмем кнопку Fork 
  3. Вводим в git bash:
  ```
    $ git clone https://github.com/!!!ТВОЙ_ЛОГИН!!!/ProjectWork2019Neiro
    $ cd ProjectWork2019Neiro
    $ git remote add upstream https://github.com/RazuvaevDD/ProjectWork2019Neiro
    $ git fetch upstream
    $ git checkout -b feature
  ```
  4. Открываем проект и пытаемся его собрать. В случае ошибки необходимо в обозревателе решений выделить решение "NeiroApp" и с помощью правой кнопки мыши "Отчистить решение".

## 2. Отправка изменений с компьютера на свой репозиторий 
```
  $ git status
  $ git add VS
  $ git commit
  $ git push origin feature
```
## 3. Отправка изменений в основной репозиторий

Необходимо зайти на [страницу проекта](https://github.com/RazuvaevDD/ProjectWork2019Neiro) и нажать кнопку New pull request

## 4. Следите за главным репозиторием. Если он ушел вперед, то нужно обновить свой репозиторий. 
Для этого выполняем последовательность команд:
```
  $ git checkout master
  $ git pull upstream master
  $ git checkout feature
  $ git merge master
  $ git push origin feature
```
# Описание и указания к работе

1. Соблюдаем правила оформления [отсюда](https://vk.com/doc68214078_474918649?hash=f56f1f25b0f0ec572c&dl=50ac88b3984861fbfb) 
2. IDE: Visual Studio 2017 Community Edition с установленным плагином Qt Visual Studio Tools 5.12.1 
3. Версия SDK 8.1 
4. Разрядность QT 32 бита
5. Обязательно пишем комментарии желательно на английском языке, но не нужно переусердствовать в этом. Достаточно краткого описания к каждой функции и пояснения в некоторых сложных на ваш взгляд местах
6. Стараемся писать по человечески! Нам это еще показывать... (избегайте изобретения велосипедов)
7. Используем header guards которые предлагает нам Visual Studio, т.е pragma once
8. Пожалуйста, пишите комментарии к коммитам на нормальном английском языке. (избегайте 20 коммитов c комментарием update main.cpp)

Продолжение следует...
