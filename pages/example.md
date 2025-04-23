---
title: Example Page
nav: Example
nav_order: 1
---

Write pages in Markdown.

## Heading Two 

Any text with no empty lines between will become a paragraph.
Leave an blank line between headings and paragraphs.
Font can be *Italic* or **Bold**.
Code can be highlighted with `backticks`.

Hyperlinks look like this [GitHub Help](https://help.github.com/).

### Lists 

A bullet list is created using `*`, `+`, or `-`, like:

- dog
- cat
- muffin

A numbered list is created using a number + `.`, like:

1. one
2. two
6. three
2. four

Horizontal rule:

--------------

> A block quote.
> Is like this.
{:.blockquote}

### A Table

| header | column a | column b |
| --- | --- | --- |
| dogs | 3 | 6 |
| cats | 3 | 6 |
| muffins | 15 | 30 |
{:.table .table-striped}

## Use Includes to Add Features

{% include accordion.html title1="Example Accordion" text1="Some Content" title2="Section two" text2="Hey there!" title3="Section three" text3="This is more info" %}

{% include figure.html img="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/VAN_CAT.png/480px-VAN_CAT.png" alt="white cat" caption="Example figure, I found this [Cat image on Wikimedia](https://commons.wikimedia.org/wiki/File:VAN_CAT.png)." %}

{% include card.html text="Some interesting text" header="Example card" %}

{% include alert.html text="This is an example alert!" color="success" align="center" %}
