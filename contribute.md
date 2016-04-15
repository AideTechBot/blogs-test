---
layout: page
title: Contributing
permalink: /contribute/
author: "Matthew Wang"
---

Hey there, I heard you want to help make this site great (again)! Have no fear, we'll guide you on the steps to making your very own blog post!

# Making your own blog post

This site is run on the framework [Jekyll](https://jekyllrb.com/), and uses Markdown-interpreted files with ruby-based mixins to generate static site data.

That probably sounded like gibberish to you, but don't worry about it! We're here to learn. Let's take a look at how we can make our own blog post, and get it on the website!

## Writing your blog post

Let's make a **text file** (in a text editor, NOT Microsoft Word, but something more like Atom, Sublime Text or Notepad) with the name:

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

That shows up on the site as *hello world*.

Your blog post should look something like this:

```
---
layout: post
title:  "Cats are pretty cool
date:   2016-04-14 20:19:49 -0400
categories: felines cats
author: "Cat Lover"
campus: "Cat Campus"
---
Hello World! I love cats!
```

Save it, and you're done!

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

We want to put our blog post in that `_posts` directory. While I wish we could voodoo magic it online, that's not how the world works. Instead, we'll use **GitHub**, a code-versioning software, to get it on the site.

First, you're going to visit [github.com](http://github.com). If you don't have an account there already, please make one!

The next thing you're going to do is visit our **repository** (it's kinda like an online code folder), {% if site.github_repo %}{% include icon-github.html username=site.github_repo %}{% endif %}. Then, you'll press the **fork** button. This lets you make your own version of our code folder, where you can make your changes.

After that, you'll add in your blog post to the `_posts` folder. The easiest way to do that is to click the `_posts` folder, press the "Upload File" button, and upload the file you just made in your previous step.

You're going to have to write a little summary message of what you added (in the lingo we call this a **commit** and **commit message**): something along the lines of *"added blog post on how awesome cats are"* should suffice.

After you're done adding your post, you should request to put those changes on our site! In programming-lingo, we call that a **pull request**. You can click the "Create Pull Request" button here.

In the options for the pull request, make sure that the **Head** is equal to your repo, and the **Base** is equal to our repo. Then, click create pull request.

You're done! Now, you're just going to wait for us to approve the change. Mostly, we're just going to check for issues with header layout (like if you forgot your three dashes), but other than that we won't touch your blog post.

You're all set! Nice job, you just made your own Blog Post!

# Becoming a blogging pro

That being said, there's more to a blog post than just typing in text. You might want images, videos, or some cool emphasis elements like **bold** or *italics*. Don't worry, I get it! Let's go over how to do that stuff, and more!

## Using Markdown, so you'll get a mark up!

**Markdown** is the "language" that we use to make our blog posts. While it takes in normal text, it can also take in modifiers. For example, wrapping your text in one pair of asteriks makes your text italicized, like so:

`*this text becomes italicized*` becomes *this text becomes italicized*.

Here's a little cheatsheet of common Markdown syntax.

(This cheatsheet will come soon).

[Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a nice and handy Markdown cheatsheet.

## Images and Markdown

A picture is worth a thousand words, and luckily you can also add images with Markdown! It works a little bit like this:

(This example will come soon).

If you notice, you add an image URL in the second part of that statement. In order to get that image, you should probably upload it somewhere, like [imgur](http://imgur.com).

## Becoming a seasoned writer

If you post often, we'll do two things to help you out! The first thing we'll do is give you an author page. I'd show you a preview, but we haven't got to that yet.

The second thing we'll do is give you what we call "push access". In other words, we'll let you directly edit the main repository, instead of having to go through pull requests. This second option is pretty hard to get, but if you do, it might make life just a bit easier.

That's it! Thanks for reading this huge wall of text, and if you have any more questions, don't hesitate to ask me (Matt). You can find my contact info [on my website](http://matthewwang.me).
