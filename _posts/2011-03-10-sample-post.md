---
layout: post
title: Sample Post
description: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
modified: 2013-05-31
tags: [sample post]
published: true
---

Below is just about everything you'll need to style in the theme. Check the source code to see the many embedded elements within paragraphs.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Body text

Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

![Kitteh](http://placekitten.com/200/300)
{: .pull-right}

*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times <cite>(That’s a citation)</cite>. <u>Underline</u>. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and <abbr title="cascading stylesheets">CSS<abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

### Nested unordered Lists

* Item one
    * sub item one
    * sub item two
    * sub item three
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

Syntax highlighting via Pygments

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

Non Pygments code example

    <div id="awesome">
        <p>This is great isn't it?</p>
    </div>
    
### Prism code highlighting

This site will override the jekyll deafaults and use a different syntax highlighter

{% prism javascript %}
var hw = 'hello world!';
{% endprism %}


{% prism css linenos=4 %}
* {
  margin: 0;
  padding: 0;
}

html, body { height: 100%; }

body {
  font-family: Helvetica, Arial, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  font-weight: 300;
  background-color: #fdfdfd;
}

h1, h2, h3, h4, h5, h6 { font-size: 100%; font-weight: 400; }

a         { color: #2a7ae2; text-decoration: none; }
a:hover   { color: #000; text-decoration: underline; }
a:visited { color: #205caa; }

/* Utility */

.wrap:before,
.wrap:after { content:""; display:table; }
.wrap:after { clear: both; }
.wrap {
  max-width: 800px;
  padding: 0 30px;
  margin: 0 auto;
  zoom: 1;
}
{% endprism %}
## Buttons

Make any link standout more when applying the `.btn` class.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>
