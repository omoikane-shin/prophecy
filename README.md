# Essays on world affairs

[Prophecy](https://omoikane-shin.github.io/prophecy/) is a blog media talks about world affairs.

## Topics

### universe

I talk about general idea of the universe, nature and stuff.

### philosophy

Philosophy covers any topics happening in the world. It tells you critical thinking and how to face the matters.

### politics

This topic mostly talks about how political mechanism influences incidents.

### economy

Economy is one of the most important factor to chase the power ballance of organizations and people.

## How to manage articles

### articles

Articles are put in _posts directory with thier name as yyyy-mm-dd-{title}.md

You need to put the Front Matter at the begining of the file like below

Example article

```
---
layout: post
title:  "平和を望む"
author: "Omoikane"
date:   2019-02-15 23:14:13 +0900
background: '/img/posts/hetsuri.jpg'
categories: concept
---

ここに記事を Markdown で書く
```

In the Front Matter, you would set categories the article is belonging to.

### draft articles

If you want to write a draft content, you would put the article in _drafts directory.

### run host on local

normal run

```bash
$ bundle exec jekyll serve
```

draft run

```bash
$ bundle exec jekyll serve --drafts
```
This includes _drafts posts
