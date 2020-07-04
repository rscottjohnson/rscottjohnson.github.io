---
layout: post
title: First Post
categories: [general, blog, setup]
tags: [jekyll, github, ruby, blog]
fullview: false
comments: true
---

#### Getting a Blog Up and Running
Having **[thrown my hat into the ring](https://twitter.com/rscottjohnson/status/1124697196278972416)** for the #100DaysOfCode recently, I decided that I'd like to begin taking notes down in a blog to capture thoughts on what I'm accomplishing and learning along the way.

*I thought this would be the easy part.*

Wanting to roll my own blog, I started to research options, and being a GitHub fan I liked the idea of utilizing GitHub Pages.  This soon introduced me to the use of **[Jekyll](https://jekyllrb.com)** for powering up your GitHub Pages page into something special through the use of markdown (which I already enjoy using).

*Done.  Solution.  Right?  Well...*

I soon found myself in Ruby Gems *heck*, and fighting with Jekyll's `bundler` commands.  For one reason or another, it just wasn't coming together.  I backed up, punted, and deleted all the files from my repository.  I knew I wanted to use the **[dbyll theme](https://github.com/dbtek/dbyll)**, so I downloaded the files, put them in my already established local GitHub repo, and ran `bundle exec jekyll serve` to start a local view of the file.

*Hallelujah moment*

From here it was just a matter of making any changes to tailor it to what I wanted, and going through the normal add, commit, and push to GitHub.

`git add .`

`git commit -m "Updated blah blah blah"`

`git push origin master`

There are a lot of changes yet to make to the structure, design, etc. of the blog, but it works and that feels like a successful step 1.

As far as today's work on #100DaysOfCode, I worked up through **[Comparison with the Strict Equality Operator](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-strict-equality-operator)** on **[freeCodeCamp](https://www.freecodecamp.org)**.  Making solid progress in the Basic Javascript section.

*May the Fourth be with you...*