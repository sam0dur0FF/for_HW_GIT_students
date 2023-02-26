# for_HW_GIT_students
Для 3 ДЗ по курсу "Знакомство с контролем версий"

# Инструкция по работе с GIT

## Введение

**Git** — это система контроля версий, которая помогает отслеживать историю изменений в файлах. 

## GIT команды

* _git init_ 
команда *git init* создает git репозиторий в текущей папке

* _git add_
команда *git add* добавляет файл в список отслеживаемых (индексируемых) файлов

* _git status_
Команда *git status* отображает состояние рабочего каталога и раздела проиндексированных файлов

* _git log_
Команда которая перечисляет коммиты, сделанные в репозитории в обратном к хронологическому порядке

## Что такое коммит и коммитить?

По-английски commit значит «фиксировать». Коммиты разбивают процесс разработки, состоящий из большого количества правок, на отдельные шаги. То есть коммит — это некое логически завершенное изменение внутри проекта и понятная (в том числе и другим разработчикам) точка, к которой можно вернуться, если возникнут какие-то проблемы.

* _git commit_
Команда которая фиксирует состояния проекта на текущий момент времени.

## Что такое ветвление?

Ветка в Git — это последовательность коммитов. С технической точки зрения ветка — это указатель или ссылка на последний коммит в этой ветке. По умолчанию, имя основной ветки в Git — master. Каждый раз, когда создается новый коммит, указатель ветки master автоматически передвигается на него.

* _git branch_ 
команда для управления ветками.

# Работа с удаленными репозиториями

Удаленный репозиторий – это версии вашего проекта, сохраненные на удаленном сервере. Доступ к репозиторию на таком сервере может осуществляться по интернету или по локальной сети.

1.После регистрации на сайте GitHub вы перейдете в свой профиль 

2.Нажмите + > New repository в командной панели вверху страницы

3.Заполните основные свойства будущего репозитория:

* В поле Repository name введите имя вашего будущего репозитория.

* Установите флажок Initialize this repository with a README, чтобы в дальнейшем вы имели возможность сразу клонировать репозиторий на свой компьютер.

* Нажмите Create repository