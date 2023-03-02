# Создание туториал по GIT

**git init** - позволяет из нашей папки сделать репозиторий.

```
Репозиторий - это папака в которой настроен контроль версий.
```

**git status** - информация о текущем состоянии.

**git add** - добавляет содержимое рабочего каталога.

```
данная команда используется после добавления файлов
```

**git commit -m "messag"** - создание коммита. 

**git log** - журнал изменений, также позволяет увидеть количество сохрарений.

*Переход от одного коммита к другому:*

**git chekout**

**git switch**

**git checkout master** - позволяет вернуться к актуальному состоянию и продолжить работать.

**git diff** - позволяет увидеть разницу между текущи фйлом и закоммиченным файлом.

**gif commit --amend -m "messag"** - внесение изменений в последний коммит.


# Краткая инструкция по MarkDown

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:

> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
> return shell_exec("echo $input |
$markdown_script");

## Заголовки

## Исходный код

## Таблицы

