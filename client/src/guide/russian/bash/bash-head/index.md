---
title: Bash Head
localeTitle: Голова баша
---
## Команда Bash: голова

Голова используется для печати первых десяти строк (по умолчанию) или любой другой суммы, указанной в файле или файлах. Кошка используется для последовательного чтения файла и печати его на стандартный вывод. т.е. распечатывает все содержимое всего файла. - это не всегда необходимо, возможно, вы просто хотите проверить содержимое файла, чтобы убедиться, что он правильный, или убедитесь, что он действительно не пуст. Команда head позволяет просматривать первые N строк файла.

если вызывается больше, чем на файл, отображаются первые десять строк каждого файла, если не указано конкретное количество строк. Выбор отображения заголовка файла является необязательным, используя параметр ниже

### использование

```bash
head [options] [file_name(s)] 
```

Наиболее часто используемые опции:

*   `-n N` , выводит первые N строк файла (ов)
*   `-q` , не распечатывает заголовки файлов
*   `-v` , всегда печатает заголовки файлов

### пример

```bash
head file.txt 
```

Распечатывает в терминале первые десять строк файла file.txt (по умолчанию)

```bash
head -n 7 file.txt 
```

Печать в терминале первых семи строк файла .txt

```bash
head -q -n 5 file1.txt file2.txt 
```

Распечатайте в терминале первые 5 строк файла file1.txt, а затем первые 5 строк файла file2.txt

### Дополнительная информация:

*   [Википедия](https://en.wikipedia.org/wiki/Head_(Unix))