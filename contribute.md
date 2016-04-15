---
layout: page
title: Contributing
permalink: /contribute/
---

Hey there, I heard you want to help make this site great (again)! Have no fear, we'll guide you on the steps to making your very own blog post!

## Making your own blog post

This site is run on the framework [Jekyll](https://jekyllrb.com/), and uses Markdown-interpreted files with ruby-based mixins to generate static site data. That probably sounded like gibberish to you, but don't worry about it! Let's take a look at what a blog post is.

Let's make a text file (in a text editor, NOT Microsoft Word, but something more like Atom, Sublime Text or Notepad)

`2016-01-31-Name-Of-Blog-Title.markdown`

With the date representing the date you wrote the article. Seems simple so far!

Next, you need to put in your header. It's a simple copy-paste job. Here's the template:

```
---
layout: post
title:  "YOUR TITLE GOES HERE"
date:   2016-04-14 20:19:49 -0400
categories: site dev
author: "YOUR NAME GOES HERE"
campus: "YOUR CAMPUS GOES HERE"
---
```

Make sure you include the three dashes, and fill out the information accordingly! The date part will obviously be the date you wrote the article on, and the categories would be decided later. Everything else is self-explanatory; just copy, paste, and edit.

After that, we want to put some actual content in there. All you need to type in is regular text. For example,

```
Hello World!

```

That shows up on the site as hello world.

And, save it, and you're done!

## Getting that post on the interwebs

Now that you have an awesome file, we need to put it somewhere!

On the website, all blog posts are stored in the `_posts` directory. The file structure looks something like this:

```
├── _config.yml # not important
├── _includes # not important
├── _layouts # not important
├── _posts # Jackpot!
├── _site # not important
└── index.html # not important
```

We want to put our blog post in that `_posts` directory. While I wish we could voodoo magic it online! I'll show you how to do that, once I finish writing this post!
