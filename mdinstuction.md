# Инструкция для работы с MarkDown

## Выделение текста

Чтобы выделить текст курсивом необходимо еобрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *Вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо его обрамить двойными звездосками (**) или знаком двойного подчеркивания (__). Например **Вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать эти два способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

Чтобы добавить ненумерованные списки, еобхдимо пункты выделить звездочкой (*) или знаком (+). Например, вот так:
Например, вот так:
* Элемент 1
* Элемент 2
+ Элемент 3


Чтобы доавить нумерованные списки, необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы вставить изобрадение в текст, достаточно написать следующее: ![Фото](foto.jpg)

## Ссылки

Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка"). Это — [без title]
(http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.

[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short

Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.


## Работа с таблицами

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



## Добавление разметки MarkDown

## Заголовки

## Таблицы