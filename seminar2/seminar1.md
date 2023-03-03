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

# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с
обратной стороны.

## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале
каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более
удобный способ: ставим по три апострофа (на букве Ё) до и после
кода. Также можно указать язык исходного кода.

```HTML
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count" class="publ
isher-nav-color" data-nav="conversation">
 <span class="comment-count">0 комментариев</
span>
 <span class="comment-count-placeholder">Комм
ентарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logou
t">
 <a href="#" class="dropdown-toggle" data-toggl
e="dropdown">
 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```

## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.

# Инлайн код

Для вставки кода внутри предложений нужно заключать этот
код в апострофы (на букве Ё). Пример: `<html class="ie
no-js">`.

Если внутри кода есть апостроф, то код надо обрамить
двойными апострофами: ``There is a literal backtick (`)
here.``

### Горизонтальная черта

`hr` создается тремя звездочками или тремя дефисами.

***

# Какя-то информация для теста