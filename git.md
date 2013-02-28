## Краткие сведения и ссылки на материалы по системе контроля версий git

### Программное обеспечение

* Клиент для всех популярных платформ может быть найден на официальном сайте <http://git-scm.com/downloads>
* GUI надстройка может быть найдена на официальном сайте

### Основные команды

* Настройка git
    * Изменить имя пользователя: git config --global user.name "\<Name\>"
    * Изменить адрес электронной почты: git config --global user.email "\<Mail\>"
* Получение помощи
    * Справка по команде: git help \<command\>
* Работа с репозиторием
    * Создать локальный репозиторий: git init
    * Клонировать репозиторий: git clone ssh://git@github.com:gennadiychistyakov/programming-practice-book.git
    * Просмотр тегов удаленных репозиториев: git remote
    * Добавить удаленный репозиторий: git remote add \<tag\> \<link to .git\>
    * Влить данные на удаленный репозиторий: git push \<tag\>
    * Забрать данные с удаленного репозитория: git pull \<tag\>
* Работа с файлами
    * Добавить файлы в stage: git add \<files\>
    * Удалить файлы из stage: git reset HEAD \<files\>
    * Удалить файлы из репозитория: git rm \<files\>
    * Вернуть состояние файла в момент последней транзацкии: git checkout -- \<files\>
* Транзацкии
    * Сделать commit: git commit -m "\<Description\>"
    * Сделать повторный commit: git commit --amend
* Получение информации о состоянии репозитория
    * Просмотреть статус файлов: git status

### Материалы

* Наиболее полное руководство по git - цифровая версия книги ProGit (доступна не только онлайн версия, но и версии в форматах pdf, ePub, mobi)
    * Английская версия <http://git-scm.com/book>
    * Русская версия <http://git-scm.com/book/ru>
* Краткая статья по базовым командам <http://blog.nsws.ru/rabota-s-git-dlya-nachinayushhix.html> 
* Визуальная справка по командам git <http://marklodato.github.com/visual-git-guide/index-en.html> (русская версия <http://marklodato.github.com/visual-git-guide/index-ru.html>)

### Упражнения

* Основные операции в git <http://try.github.com/levels/1/challenges/1>
* Упражнения на ветвления <http://pcottle.github.com/learnGitBranching/>

### Репозитории

* Удобным сервисом для хранения удаленных репозиториев является портал github
    * Ссылка на github <https://github.com>
    * Ссылка на репозиторий programming-practice-book <https://github.com/gennadiychistyakov/programming-practice-book>
    * Ссылка на репозиторий с этой справкой <https://github.com/gennadiychistyakov/git-materials>