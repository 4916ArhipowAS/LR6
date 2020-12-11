Сделал форк с GitHub

Скачиваем проект на пк

![](Image/1.jpg)

Переходим в каталог проекта

![](Image/2.jpg)

Запрашиваем изменения с GitHub после добавления файла

![](Image/3.jpg)

Получаем историю ветки

![](Image/4.jpg)

Получаем список веток

![](Image/5.jpg)

Переходим в ветку branch1

![](Image/6.jpg)

Получаем историю ветки

![](Image/7.jpg)

Получаем информацию о внесённых изменениях

![](Image/8.jpg)

Переходим в ветку master

![](Image/9.jpg)

Сливаем ветку branch1 с веткой master

![](Image/10.jpg)

Получаем информацию о конфликтах

![](Image/11.jpg)

Добавляем изменённый вручную файл mergefile.txt

![](Image/12.jpg)

Смотрим статус

![](Image/13.jpg)

Коммитим внесённые изменения

![](Image/14.jpg)

Удаляем ветку branch1

![](Image/15.jpg)

Добавляем файл Change_1.txt

![](Image/16.jpg)

Коммитим 

![](Image/17.jpg)

Добавляем файл Change_2.txt

![](Image/18.jpg)

Коммитим

![](Image/19.jpg)

Делаем хардрезет одного коммита

![](Image/21.jpg)

Создаём ветку report

![](Image/22.jpg)

Список коммитов

![](Image/23.jpg)

Фото редактора

![](Image/24.jpg)

Лог команд

git config --global user.name "4916_Arhipow_A_S"

git config --global user.email explorers2016@yandex.ru

git clone https://github.com/4916ArhipowAS/LR6

cd LR6

git pull

git log

git branch

git checkout branch1

git log

git log -p

git checkout master

git merge branch1

git status

git add mergefile.txt

git status

git commit -m "Commit changes"

git branch -d branch1

git add Change_1.txt

git commit -m "Change_1_txt"

git add Change_2.txt

git commit -m "Change_2.txt"

git reset --hard HEAD~1

git checkout -b report

git log 

git push --all https://github.com/4916ArhipowAS/LR6

git add Image

git commit -m "Added file Image"

git push --all https://github.com/4916ArhipowAS/LR6
