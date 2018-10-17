### HTML 浏览器去解释语言然后转换成内容
### update?
> css all the design things, you use css to talk to people
> html, you talk to the browser
> javascript, behavior
> first page of a website is called - index page
> so index.html

>to get the head-body structure of html, input html, then enter

> <a> = anchor tag  href = add an anchor here
  <br> = break
  <small> - small print
  <h1> = heading 1
  <article> = 故名思议，可以表示论坛帖子、杂志或新闻文章、博客、用户提交的评论、交互式组件，或者其他独立的内容项目。它的主要语义为表示自己是一个独立的内容结构。每一个<article>元素内部结构都应该是相似的，比如都应该包含一个头标题(h1-h6元素)等。 HTML5 new tag
  <nav> = navigation
  <aside> = complementary information, goes with? HTML5 new tag
  <ul> = unnumbered list
  <li> = list item, a list if a band of things. Usually used in navigation item
  <ol> = ordered list, 有序号的
  <section> would wrap around article, page within a page
  <em> = emphasis, text here will be displayed in Italics.
  <img src="" alt=""/>  src = source, alt = alternative. if the image doesn't show up, the alternative text shows up instead
  <figure>
  <figcaption>
  <header> is not the top of the page, is a collection of heads,
  <footer> however is the bottom part of the page
>css 的文件叫做 stylesheet


### 合理利用 global class he .class，可以减少代码冗余
### id 一般适用于，javascript指定对象的动作

## Your css always come last. Cuz you are overriding other layout.

## Html5 main 和 body的区别

- A block element, has width, height, margin, e.g. article
- The opposite: inline element: doesn’t support height, margin, has return before and after it, no physical properties


## For responsive interface - mobile first - Why? It's easier, you just need to add up things gradually


## bootstrap is a css library

## what is bootstrapCDN?

## two types of containers: container and container-fluid

##
>class="col-12 col-md-6 teal"
class="col-12 col-md-6 orange"
class="col-12 col-lg-4 red"

## chrome 右键，inspector

## if you want to group a piece of content, don't go <row>, go <column>, cuz <row> has some space

## col-order is very important, cuz if you are showing sth on mobile, sometimes the pic should not go first, so then you may want to change order

## .bg-light{
  background: purple !important // !important you can override the style in bootstrap
}

# use inspector to 选择你用的bootstrap现成element，然后去找他们的style，然后你就可以override他们拉 by !important

## col-3 任何设备上都是3；   col-sm-4 大于sm的时候，变成4，
> col-3 col-sm-4 col-md-5 col-lg-6 后面的一直override前面的
> 这就是为什么要mobile first，因为从小往大递增，每次都override 前面的，后面没有的话就inherit最后的那个。 顺序不同的话会break
