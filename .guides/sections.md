---
title: Introduction
files:
  - action: open
    path: "#cmd: bash .guides/restore.sh intro,index.html"
    panel: 0
layout: 2-panels-tree

---
#Introduction 

1. Open **index.html** file from **Filetree** panel.
1. Write something! For example: `Hello! My name is …`
1. Save the file.
1. Click ![Preview](.guides/img/preview.png) on the right side of the menu

Have you ever wondered how the worldwide web works? Of course you have! Today you will learn how to make web sites so you too can contribute to building it. Websites are written using **HTML**, which stands for **HyperText Markup Language**. You will find out more about it as you build your page.

---
title: What are web pages?
files:
  - action: open
    path: "#cmd: bash .guides/restore.sh first_page,index.html"
    panel: 0
layout: ""

---
The web browser is a special program that knows how to interpret text files written using **HTML language**. We haven’t added any **HTML** yet, we simply put in some text, but the browser doesn’t care! As long as you give it an .html file, it will do its best to show you the file as best as it can understand it.

This is very useful: even when a website contains errors, the browser will try to figure out how to show it to you anyway.

**How can we view these files?**

When you type in the address in your browser, your request gets passed along to a computer which is always turned on and configured to allow you to see the pages that live inside it. This computer is called a server. When it receives a request from your computer, it looks for all the necessary files: the .html file and sends you that with anything else that the page needs, like images and videos.

#Can I have this page please?

![](.guides/img/diagram_screenshot.png)
Here you go.
---
title: What is HTML?
files: []

---
**HTML** is a **markup** language - it means that it is used to describe what things are.

Even though the browser will try to display things as best as it can, it helps it to know what these things are.

To tell browser that, we use `tags`.

Tags look like this: `<p>This is some text.</p>`

`<p>` is short for **paragraph**.

There is an opening tag which is this: `<p>` and a matching closing one with a forward slash: `</p>`. The browser knows that anything in between the two tags is a paragraph of text.

Tags can have attributes, which are bits of useful information about the element. Let’s have a look at the link tag:

`<a href="http://codeclub.org.uk">Visit CodeClub website</a>`

`<a>` stands for anchor, which is what links used to be called.

It also has the opening tag: `<a>` and the closing tag: `</a>` but we added an attribute to the opening one: `<a href="http://codeclub.org.uk">`

`href` is the attribute, and `http://codeclub.org.uk` is its value.
`href` stands for *hypertext reference*. A text that linked to other texts was once named *hypertext*, because it could have images, and sounds, and could link to other texts. That made it a little bit different to plain text.
href tells the browser where the link should take you to, and the text in between the tags will be visible as a link.
---
title: Summary
files: []

---
We already know `<p>` and `<a>`.

Here are some other HTML tags:

`<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` - headings  
`<hr>` - horizontal rule  
`<div>` - a box for grouping things  
`<ol>` - ordered list  
`<ul>` - unordered list  
`<li>` - list item  


`<img>` - a special element, which unlike others doesn’t have a closing tag. We use it for putting the images in.  

There are also some tags that we will always use in HTML documents, and they are:

`<html>` - tells the browser where we put out code  
`<head>` - inside `<head>` we put things which may be useful to the browser, but which don’t appear as text on the page. In this example we put a `<title>` there, which then shows up at the top of the browser window.  
`<body>` - that’s where we put the things we want to appear on the page
