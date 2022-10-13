# GR_3371
Привет!
# **Инструкция для работы с Git и удалёнными репозиториями**
---
### ***Что такое Git?***
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире. Последней версией на 06.10.2022 является (в версии для Windows) Git 2.37.3.

## **Подготовка репозитория**
Для создание репозитория необходимо выполнить команду **git init** в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка **.git**)

## **Создание коммитов**
* *Git add*

Для добавления измений в коммит используется команда **git add**. Чтобы использовать команду **git add** напишите **git add <имя файла>**

* *Просмотр состояния репозитория*

Для того, чтобы посмотреть состояние репозитория используется команда **git status**. Для этого необходимо в папке с репозиторием написать **git status**, и Вы увидите были ли измения в файлах, или их не было.

* *Создание коммитов*

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду **git commit**. Выполняется она так: **git commit -m "<сообщение к коммиту>**. Все файлы для коммита должны быть ДОБАВЛЕНЫ и сообщение к коммиту писать ОБЯЗАТЕЛЬНО.

## **Перемещение между сохранениями**
Для того, чтобы перемещаться между коммитами, используется команда **git checkout**. Используется она в папке с пепозиторием следующим образом: **git checkout <номер коммита>**

В конце перемещения НЕОБХОДИМО вернуться в конец ветки **master**.

## **Журнал изменений**
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда **git log**. Для этого достаточно выполнить команду **git log** в папке с репозиторием

## **Ветки в Git**
* *Создание ветки*

Для того, чтобы создать ветку, используется команда **git branch**. Делается это следующим образом в папке с репозиторием: **git branch <название новой ветки>**

* *Слияние веток*

Для того чтобы дабавить ветку в текущую ветку используется команда **git merge**

* *Удаление веток*

Для удаления ветки ввести команду **git branch -d 'name branch'**

## **Сравнение текущего состояния с коммитом**
Для того, чтобы просмотреть изменения в текущей версии по сравнению с последним коммитом, используется команда **git diff**. Для использования изменения в тексте должны быть сохранены заранее.

## **Решение конфликтов**
Для решения конфликтов, возникающих при слиянии веток, необходимо принять один из вариантов, предлагаемых Visual Studio Code или другой программой, при работе в которой возникли противоречия. Кроме того, существует множество других инструментов, помогающих разрешить возникшие конфликты как автоматически, так и в ручном режиме.

## **Работа с удаленными репозиториями**
* *Клонирование репозитория*

Для клонирования удаленного репозитория, то есть создания его копии на своем компьютере для дальнейшей работы с ним, служит команда **git clone <ссылка на репозиторий>**.

* *Загрузка изменений из удаленного репозитория*

Для загрузки изменений из клонированного удаленного репозитория на свой компьютер служит команда **git pull**

* *Загрузка изменений в удаленный репозиторий* 

Для загрузки произведенных изменений со своего компьютера на удаленный репозиторий служит команда **git push**
