# GNL

Цель проекта
--
Этот проект о функции, которая возвращает строку, прочитанную с файлового дескриптора. Также данный проект знакомит со статическими переменными.

Почему get_next_line важен?
--
Данные проект знакомит со статическими переменными, файловыми дескрипторами и чтению файлов в C.

Обязательная часть
--
Вызов функции get_next_line() должен позволить прочитать одну строку из файла, используя файловый дескриптор.
Данная функция должна вернуть прочитанную строку. Если произошла ошибка, или нечего читать, то должна возращать NULL

Бонусная часть
--
Использовать для get_next_line() только одну статическую переменную.
Сделать так, чтобы get_next_line() смог одновременно работать с несколькими файловыми дескрипторами одновременно.

Программа читает по одной строке за раз. Если ее вызывать в цикле, программа будет читать весь файл или заданное количество строк (по циклу).
Функция использует параметр BUFFER_SIZE, который представляет собой количество байтов, которые будут считываться из файла.

Более подробно в задании (находится в этом репозитории - en.subject.pdf)
