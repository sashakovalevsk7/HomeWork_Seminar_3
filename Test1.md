Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
>Действительно

# **Git** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## **СОЗДАНИЕ КОММИТОВ**

Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

Ветки в Git

## ***СОЗДАНИЕ ВЕТКИ***

>как все сложно
>>но очень интересно
>>>спасибо вам)

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## ***Слияние веток***
![картинку](https://yt3.ggpht.com/ytc/AMLnZu-o3Ur1RkFUr9gZNu0RbIlMdNqwse9LTZ_GuzGjHQ=s900-c-k-c0x00ffffff-no-rj)

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Добавление картинок
Для того, что бы добавить **картинку**,надо:
![картинка](https://memepedia.ru/wp-content/uploads/2017/07/1429794583_343353562.png)

## Добавление ссылок
Для того, что бы добавить **ссылку**,надо:
[Инструкция](https://www.amazon.com)

## Добавление списков и цитат
* ненумерованные списки задаются тремя фигурами
* первый
+ второй
- третий 
что бы добавить *цитату* используем знак ">"
>Чем умнее человек, тем легче он признает себя дураком

что бы добавить *цитату в цитате*,надо:
>я
>>ты
>>>мы 