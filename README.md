# В данном ридми файле будет краткий конспект по настройке и работе с git и github
## 01 Настройка окружения и знакомство с командной строкой
### В данной теме почти весь материал посвящён настройке git на PC. Основным знанием данной темы является [шпаргалка](https://practicum.yandex.ru/trainer/git-basics/lesson/fe0bcd71-f592-423b-bb81-27c37a6a115b/ "Базовые команды git") в пятом пункте.
## Тема 1 Введение.
### Краткое содержание модуля:
 - создадим Git-репозиторий, добавим в него файлы и сделаем свой первый коммит;
 - познакомимся с GitHub — самой популярной платформой для хранения IT-проектов и командной работы над ними;
 - научимся синхронизировать локальный репозиторий, который хранится у нас на компьютере, с удалённым — тем, который я заведу на GitHub;
 - изучим понятия хеш, лог, HEAD и другие — они помогут вам ориентироваться в коммитах;
узнаем, как работать с изменениями и правильно оформлять коммиты.

## Тема 2 Первый коммит.
### Ключевые слова для первого коммита
#### git init, git add, git status, git commit -m, git push, git log.
 
## Тема 3 Работа с GitHub.
### Что такое GitHub GitHub — платформа для хранения IT-проектов и совместной работы над ними с использованием Git. По сути, это сайт, куда можно загрузить файлы своего проекта для обмена с другими людьми. Далее идёт подробная инструкция для регистрации и установки соединения с удалённым репозиторием.

### Файл README.md используется для создания описание для ваших проектов на github.(Данную работы я также выполняю в файле формата md для наглядности). Также используя шпаргалку из данного урока - [ссылка](https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/ "Шпаргалка по readme")
### В теме три также проходит знакомство с командной строкой и установка Git Bash на PC. 
### Основные операции с файлами через командную строку:
- touch для создания файла(формат файла указывается после его названия через точку)
- mkdir для создания директории
- cp позволит копировать файлы($ cp что_копируем куда_копируем)
- mv вырезает файл(синтаксис аналогичен cp)
- cat вводится, чтобы прочитать файл($ cat myfile.txt # распечатали содержимое файла myfile.txt)
- rm, rmdir, rm -r данные команды используются для удаления файлов и папок(rm удаляет файл, rmdir - папку, rm -r удалит папку со всеми элементами внутри)
### Эффективная работа с командной строкой показана в заключительном уроке темы 3
### Выполнение нескольких команд в одну строку выполняется через разделение двумя амперсандами
### Использование собственной памяти терминала(буфера) осуществляется нажатием на клавиатуре стрелки вверх
### С помощью tab происходит автозаполнение(позволяет не заучивать все команды и сокращать заполнения путей)
### Команды для быстрой навигации и другие базовые команды консоли содержатся в теме 5 вот [ссылка](https://practicum.yandex.ru/trainer/git-basics/lesson/fe0bcd71-f592-423b-bb81-27c37a6a115b/ "Шпаргался по базовой работе с консолью") для удобства.
## Тема 4 Синхронизация репозиториев.
### Основные команды:
- git init инициализирует папку в репозиторий
- git status показывает текущие состояние репозитория
- git add позволяют "отслеживать" изменённые файлы(git add . - сразу все файлы)
- git commit(git commit -m, если нужно присвоить коммиту название)
- git log позволяет вывести историю коммитов

## Знакомство с GitHub
### GitHub — платформа для хранения IT-проектов и совместной работы над ними с использованием Git.
### Далее в теме 4 урок 1-3 показано создание и привязка к GitHub профилю SSH ключа.
### Команды работы с удалённым репозиторием:
- git push позволяет отправить изменения на удалённый репозиторий
- git pull скачивает изменения с удалённого репозитория
### В пятом уроке мы подходим к функционалу и полезному применению файла README.md и практическому его использованию в уроке 6


