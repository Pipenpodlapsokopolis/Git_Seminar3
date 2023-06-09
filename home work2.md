# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
**Git** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для **создание репозитория** необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для **добавления измений** в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы **посмотреть состояние репозитория** используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы **создать коммит**(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

### Перемещение между сохранениями
Для того, чтобы **перемещаться между коммитами**, используется команда *git checkout*. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*

### Журнал изменений
Для того, чтобы **посмтреть все сделанные изменения** в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы **создать ветку**, используется команда *git branch*. Делается это следующим образом : в папке с репозиторием: *git branch <название новой ветки>*

### Слияние веток

Для того чтобы **дабавить ветку** в текущую ветку используется команда *git merge <name branch>*

### Удаление веток
Для **удаления ветки** ввести команду "git branch -d 'name branch'"
## Pабота с изображениями
![xexexexe)](https://avatars.dzeninfra.ru/get-zen_doc/1907878/pub_635d0391088a2c0d4d1cd833_635d039363d4707849faa167/scale_1200)

![kapodaster](https://cdn.iportal.ru/news/2015/99/preview/373040953a4a814a9f983988a24f4a2b06e70980_1280_853_c.jpg)
## Цитаты и списки

**Нумированные** списки офориляются так:

1. Первый

2. Второй

3. Третий

**Ненумированные** списки офориляются так:

- Первый

- Второй

- Третий

или

+ Первый

+ Второй

+ Третий

или

* Первый

* Второй

* Третий

git pull
Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией

git push
При первом её использовании нужна авторизация.
Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

Как настроить совместную работу

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории.

GitHub при создании нового репозитория подскажет, как это можно сделать

4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с удаленного репозитория”
6. Выкачать (pull) актуальное состояние из удалённого репозитория

pull request

- команда для предложения изменений

- запрос на вливание изменений в репозиторий

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изме

Как сделать pull request (по шагам):

- Делаем fork (ответвление) репозитория
- Делаем git clone СВОЕЙ версии репозитория
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request