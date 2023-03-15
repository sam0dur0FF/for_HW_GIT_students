# Instructions on working with Markdown

## Highlighting the text

To highlight the text in cursive add star symbol (*) or underscore (_) on both sides.

For example:

*hello* or _hello_

To highlight the text in bold add double star (**) or double underscore (__) symbol on both sides. 

For example: 

**wow** or __wow__

Alternatives ways of highlighting are needed to use both methods at the same time.

For example:

_This is an **example**_

## Lists

To add unnembered lists, use stars.
To add unnumbered lists, you have to add star symbols (*) or plus symbol (+).

For example:

* Element 1
* Element 2
* Element 3
+ Element 4

To add numbered lists, you have to add numbers.

For example:

1. Element 1
2. Element 2
3. Element 3


## Working with images

To add an image to the text, you have to type the following:

![Hello, this is an image](photo-1575936123452-b67c3203c357.jfif)

## Links 

To create an inline hyperlink, you must use parentheses immediately after the closing square. Inside them, you need to put a URL. It is also possible to place a title enclosed in quotation marks in them, which will be displayed on hover, but this item is not required.

For example: 

[Example that you can click](https://gb.ru/lessons/305202 "Unnecassary comment/hint")

When creating a tolerable hyperlink, instead of the target address, the second pair of square brackets is used, inside which a label is placed, the link identifier (id).

## Working with tables

Creating tables requires a title and alignment settings (second line). Alignment is specified with a colon. Columns are set by vertical sticks (|)

For example: 

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Mandatory require a title and alignment settings (second line). Alignment is specified with a colon. Columns are set by vertical sticks (|)

External vertical sticks (|) are optional, and it is not required to fit the columns to the same size. You can use the styles described above.

For example:

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Quotes

To indicate quotes use the greater-than sign (>). It can be inserted both before each line of a quotation, and only before the first line of a paragraph. Markdown syntax also allows you to create nested quotes (quotes within quotes). Additional levels of quotation marks (">") are used to mark them up. Quotes in Markdown can contain all sorts of markup elements.

For example:

> Это пример цитаты,
> в которой перед каждой строкой
> ставится угловая скобка.

> Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
> Второй параграф.

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования

## Git clone

This command allows you to clone an external repository to our PC. You need to type: *git clone address of the repository that we copy to our PC/*.

## Git pull

This command allows you to download everything from the current repository and automatically do merge with our version. 

## Git push

This command allows us to send our version of the repository to an external repository. REQUIRES AUTHORIZATION on an external repository. 

## Git pull request

How to make a pull request:

* Fork the repository

* Clone YOUR version of the repository

* Create a new branch and make changes to IT

* Commit changes (make commits)

* Submit your version to your GitHub

* On the GitHub site, click the pull request button

## Conclusion

![GIF](FrayedImprobableElephant-max-1mb.gif)