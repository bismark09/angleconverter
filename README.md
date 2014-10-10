Преобразователь угл-код
==============

#### Путь проектирование  

* Построение аналитической модели
* Перевод на вычислительные методы  в целочисленной форме 
* Построение модели в блоках DSP Builder 
* Моделирование, тестирование, сравнение результатов с первыми пунктами
* Ручное описание модели на Verilog HDL

email:  yuri@filatov.pro

Документы:
1.[Выкладки хода разработки аналитической модели](https://github.com/bismark09/angleconverter/blob/master/developmentModelKPU.md)

![SIN COS](/images/sincos.PNG)
Format: ![SIN COS](url)


Вопросы:
1. Грубый отсчет - определяет угловое положение до360 угл. град(с достоверностью до 0.4 угл. град.) 
- что значит с достоверностью, это +- 0.4, или  шаг разрешающей способности АЦП?

2. 







Syntax guide

Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.
Headers

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

*You **can** combine them*

Lists
Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

Ordered

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

Images



Links




Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

Inline code

I think you should use an
`<addr>` element here instead.

GitHub Flavored Markdown


Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```


Task Lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

Tables

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

