# ProjectWork2019Neiro
Проектная работа 2019 - Нейроинтерфейс

Ссылка на проект: https://project.spbstu.ru/mod/opd/view.php?pid=4&rid=18

# Работа с GitHub
1. Начало работы

Настройка:
git config --global user.email "you@example.com"

git config --global user.name "Your name"

git config --global core.editor notepad

Заходим на https://github.com/RazuvaevDD/ProjectWork2019Neiro , жмем кнопку Fork 

git clone https://github.com/!!!ТВОЙ ЛОГИН!!!/ProjectWork2019Neiro

cd ProjectWork2019Neiro

git remote add upstream https://github.com/RazuvaevDD/ProjectWork2019Neiro

git fetch upstream

git checkout -b feature

2. Отправка изменений с компьютера на свой репозиторий 

git status

git add VS

git commit

git push origin feature

3. Чтобы послать Pull request нужно зайти в https://github.com/RazuvaevDD/ProjectWork2019Neiro и нажать кнопку New pull request

4. Следите за главным репозиторием. Если он ушел вперед, то нужно обновить свой репозиторий. Для этого выполняем
последовательность команд:

git checkout master

git pull upstream master

git checkout feature

git rebase master

# Описание и указания к работе

1. Соблюдаем правила оформления отсюда (https://vk.com/doc68214078_474918649?hash=f56f1f25b0f0ec572c&dl=50ac88b3984861fbfb) 
2. IDE: Visual Studio 2017 Community Edition с установленным Qt Visual Studio Tools 5.12.1 
3. Версия SDK 8.1 
4. Разрядность QT 32 бита
5. Обязательно пишем комментарии желательно на английском языке, но не нужно переусердствовать в этом. Достаточно краткого описания к 
каждой функции и пояснения в некоторых сложных на ваш взгляд местах
6. Стараемся писать по человечески! Нам это еще показывать... (избегайте изобретения велосипедов)
7. Используем header guards которые предлагает нам Visual Studio, т.е pragma once
8. Пожалуйста, пишите комментарии к коммитам на нормальном английском языке. (избегайте 20 коммитов c комментарием update main.cpp)

Будет дополняться...
