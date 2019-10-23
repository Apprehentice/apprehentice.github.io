---
layout: post
title:  "Blog Workflow"
date:   2019-10-22 22:00:00 -0800
categories: meta
---

My first post here was about me trying out Jekyll for a change. Previously, I've tried blogging with Tumblr and I think I've even tried setting up WordPress a time or two. Honestly, though, nothing seems easier than Jekyll.

Working with Jekyll feels natural for me because I understand web development. Yes, there is a learning curve. I had to learn the folder structure and the processing order and I wasn't quite familiar with Liquid templates, though I had used Moustache before. Once I learned my way around it, though, I was quite pleased with how configurable, simple, <span title="It also helps that I have a fetish for static websites">and straightforward it is</span>. Working with it is a breeze.

## Website Generation ##

> Jekyll is a blog-aware static site generator in Ruby - <cite>github/jekyll</cite>

I like the idea of a document/template-based website generator because it helps separate content from presentation. These posts are written in markdown[^markdown] which is both human readable and machine readable. That means that they're easy to write and easy to convert[^pandoc].

With Jekyll, I can write my content without fussing over layout and, assuming my layout and stylesheet files are sanely written, they should look good when I build them.

## Workflow ##

So, what does my workflow look like? Distilled into a list, it goes something like this:

1. Setup
    1. Generate scaffolding with Jekyll
    2. Edit layouts and stylesheets
    3. Add pages
2. Blogging
    1. Create new post file
    2. Write post (with metadata)
    3. Build and preview
    4. Publish with a git commit

Thanks to Jekyll and Git, most of my work can be done on the command line and in a simple text editor. At this moment, I'm writing this in <span title="Not Vim, sorry!">Visual Studio Code</span> and I wouldn't have it any other way.

Sure WYSIWYG editors are nice, but I hate the bloat that comes with a complicated CMS. I can get the same result with a static site and a text editor with syntax highlighting, so why shouldn't I? Plus, if I decide I don't like the way things look, I can write up a new layout in plain HTML and CSS (plus Liquid for templating;) there's no server-side language to deal with.

I like that I can iterate quickly and that my hands rarely leave the keyboard. There isn't a clunky UI with menus to fumble around in. There aren't a million keyboard shortcuts to remember. I type, switch to my terminal, push a commit or two, and my work is complete.

I think I'm sticking with Jekyll for a while.

[^markdown]: [https://daringfireball.net/projects/markdown/]
[^pandoc]: I've actually taken to writing my own [build scripts](https://github.com/Apprehentice/pdbuild) for markdown documents to convert them to PDFs.