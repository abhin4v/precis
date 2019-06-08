---
date: 2019-06-05
tags: documentation demo
---

# Precis Demo

It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com).

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

As Kanye West said:

> We're living the future so
> the present is our past.

I think you should use an `<addr>` element here instead.

And this is a horizontal rule.

-----------------------

## Code

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`. You can also add a block of code:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Task Lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Tables

You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|:`

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

You can see the [Markdown source](https://raw.githubusercontent.com/abhin4v/precis/master/demo-note.md) of this note too.