# Homework
## Gitbash
### by Soldatenko Vitali
1. Для просмотра где я используется команда `pwd`
2. Создание папки `mkdir`
3. Зайти в папку `cd`*название папки*
4. ~
5. ~
6. Cоздание файлов команды `touch` и `cat >`
7. ~
8. Для вывода содержимого папки команда `ls`
9. Для открытия текстового файла команда `vim` *имя файла*
10. Для входа в режим редактирования жмем **I**, для выхода **esc**
11. Для сохранения:
      * Жмем клавишу `:`
      * пишем `wq`
      * Жмем `enter`
12. Для выхода на уровень выше `cd ..`
13. Перемещение с помощью команды `mv` *название файла*     *куда переместить*
14. Копирование файла с помощью команды `cp`  *название файла*    *куда переместить*
15. Для поиска файла команда `find` и опция `-name` *для поиска файла по имени*
16. Для просмотра содержимого файла в реальном времени команда `tail` с опцией `-f`
17. Для вывода первых строк текстового файла команда `head` с указанием количества строк, например `-3`
18. Для вывода последних строк текстового файла команда `tail` с указанием количества строк, например `-4`
19. Для просмотра содержимого длинного файла команда `less`
20. Вывести дату и время команда `date`
21. Для отправки запросов на сервер команда `curl`, с различными опциями, например `-v` выведет максимально полную информацию о сервере.
22. Скрипты можно писать 3 способами:
    * Писать команду в строку, отделяя команды `;`
    * Создать файл и в нем писать скрипт, первая строка должно начинаться с команды `#!/bin/bash` и с каждой новой строки вводим новую команду. Для запуска используем команду `./название файла`. При возниковении ошибки, используем команду `chmod` для допуска к выполнению данному файлу.
    * С созданием переменных. Допустим команда `сom1=$(mkdir dir_1)`  `com2=$(touch file{1..3})`. Далее даем команду на выполнение комманд `echo $com1 $com2`.
    
