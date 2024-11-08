# myfile

![Bash](https://ih1.redbubble.net/image.3460508448.1739/st,small,507x507-pad,600x600,f8f8f8.u1.jpg)

Это программа с функционалом для работы с файлами, которая будет выполнять пользовательские команды.

### Возможности

Данный проект имеет следующий функционал. 

- **ls [path]**               выводит список всех файлов и директорий для `path`
>Example: ls C:\Users\argynsagash\Documents\
- **ls_py [path]**            выводит список файлов с расширением `.py` в `path`
>Example: ls_py C:\Users\argynsagash\Documents\
- **is_dir [path]**           выводит `true`, если `path` это директория, в других случаях `false`
>Example: is_dir C:\Users\argynsagash\Documents\     
>Example: is_dir C:\Users\argynsagash\Documents\file.txt
- **define [path]**           выводит `директория` или `файл` в зависимости от типа `path`
>Example: define C:\Users\argynsagash\Documents\file.txt
- **readmod [path]**          выводит права для файла в формате `rwx` для текущего пользователя
>Example: readmod C:\Users\argynsagash\Documents\file.txt
- **setmod [path] [perm]**    устанавливает права для файла `path`
>Example: setmod C:\Users\argynsagash\Documents\file.txt rwx
- **cat [path]**              выводит контент файла
>Example: cat C:\Users\argynsagash\Documents\file.txt
- **append [path]**           добавляет строку `# Autogenerated line` в конец `path`
>Example: append C:\Users\argynsagash\Documents\file.txt
- **bc [path]**               создает копию `path` в директорию `/tmp/${date}.backup` где, date - это дата в формате `dd-mm-yyyy
>Example: bc C:\Users\argynsagash\Documents\file.txt
>Example: bc C:\Users\argynsagash\Documents\`
- **greplong [path]**         выводит самое длинное слово в файле
>Example: greplong C:\Users\argynsagash\Documents\file.txt
- **help**                    выводит список команд и их описание
>Example: help
- **exit**                    завершает работу программы
>Example: exit

### Запуск

    java  MyFile

### Контакты разработчика

Ниже найдете список ссылок для связи с автором.

| Платформа    | Ссылка                      | Отвечу за |
| -------------|:---------------------------:|----------:|
| Почта        | [Ссылка](argyn.sagash@gmail.com) | 24 часа   |
| Telegram     | [Ссылка](https://t.me/argynsagash) | 20 мин     |
