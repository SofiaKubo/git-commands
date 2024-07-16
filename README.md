# Git Commands



### Базовые команды для командной строки


|              Command       |                                Description                        |
|----------------------------|-------------------------------------------------------------------|
| `pwd`                      | Показать путь к текущей директории, указать текущее местоположение|
| `ls`                       | Отобразить содержимое в текущей папке                             |
| `ls ~`                     | Отобразить содержимое в домашней директории                       |
| `cd имя_папки`             | Перейти в указанную папку                                         |
| `cd ..`                    | Перейти на уровень выше, в родительскую папку                     |
| `cd ~`                     | Перейти в домашнюю директорию                                     |
| `cd /`                     | Перейти в корневую директорию                                     |
| `touch имя_файла`          | Создать файл с указанным именем в текущей папке                   |
| `cp имя_файла /имя_папки`  | Скопировать файл с указанным именем в указанную папку             |
| `mv имя_файла /имя_папки`  | Переместить файл с указанным именем в указанную папку             |
| `cat имя_файла`            | Распечатать, прочитать содержимое текстового файла                |
| `rm имя_файла`             | Удалить указанный файл                                            |
| `rmdir имя_папки`          | Удалить указанную папку, если она пуста                           |
| `rm -r имя_папки`          | Удалить указанную папку со всем её содержимым                     |


### Инициализация Git-репозитория


    
|                  Command      |                       Description                       |
|-------------------------------|---------------------------------------------------------|
| `git init`                    | Инициализировать локальный Git-репозиторий              |
| `rm -rf .git`                 | Отменить "разгитить" отслеживание в папке               |
| `git status`                  | Проверить текущее состояние репозитория                 |



### Добавление и фиксирование изменений



|                  Command             |                      Description                        |
|--------------------------------------|---------------------------------------------------------|
| `git add имя_файла`                  | Подготовить файл к сохранению, к коммиту                |
| `git add --all`                      | Подготовить к сохранению все файлы в репозитории        |
| `git add .`                          | Подготовить к коммиту текущую папку и все файлы в ней   |
| `git commit -m "текст сообщения"`    | Зафиксировать изменения, выполнить коммит               |
| `git log`                            | Просмотреть историю коммитов                            |
| `git remote add`                     | Привязать удаленный репозиторий к локальному репозиторию|
| `git remote -v`                      | Проверить, что репозитории связаны                      |
| `git push`                           | Отправить изменения на удаленный репозиторий            |
| `git clone`                          | Скопировать проект на локальный компьютер               |





