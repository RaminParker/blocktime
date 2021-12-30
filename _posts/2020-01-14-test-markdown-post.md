---
toc: true
layout: post
description: A minimal example of using markdown with fastpages.
categories: [introduction, bitcoin impact, big picture]
title: An Example Markdown Post
image: images/blog_post_images/welcome.png
comments: true
author: Ramin Parker
---
# Example Markdown Post


## Welcome to this blog

Hey everyone, welcome to my blog. I finally took the leap and set up my blog, and after a lot of thinking, I finally decided to create a blog.

Why a blog? Well among a lot of other reasons, like not forgetting what I learn from time to time, and to keep track of my journey as a Software Development Engineer. The other huge reason is that I love to learn new things, research the ones I find interesting, and I plan to document and share my learnings via blog posts, which can be easily found and referred to later as well. I'll try to share things I learn about Software Development, my interests in Data Science and all the other random things I encounter. Hopefully, other people will also find these posts helpful, relevant or interesting. 

Thanks for visiting this blog!

## About Me

Work in progress...

## Youtube Videos

A more in-depth explanation about the above project can be viewed in this video:

{% include youtube.html content="https://youtu.be/Ll50l3fsoYs" %}

## Tweetcards

<center>{% twitter https://twitter.com/jeremyphoward/status/1232059428238581760?s=20 %}</center>


## Basic setup

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-filename.md`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `filename` is whatever file name you choose, to remind yourself what this post is about. `.md` is the file extension for markdown files.

The first line of the file should start with a single hash character, then a space, then your title. This is how you create a "*level 1 heading*" in markdown. Then you can create level 2, 3, etc headings as you wish but repeating the hash character, such as you see in the line `## File names` above.

## Basic formatting

You can use *italics*, **bold**, `code font text`, and create [links](https://www.markdownguide.org/cheat-sheet/). Here's a footnote [^1]. Here's a horizontal rule:

---

## Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2

## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

## Images

![]({{ site.baseurl }}/images/logo_blocktime.png "Das ist mein Logo")

## Code

You can format text and code per usual 

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

Formatting text as shell commands:

```shell
echo "hello world"
./some_script.sh --option "value"
wget https://example.com/cat_photo1.png
```

Formatting text as YAML:

```yaml
key: value
- another_key: "another value"
```


## Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |


## Tweetcards

{% twitter https://twitter.com/jakevdp/status/1204765621767901185?s=20 %}


## Footnotes



[^1]: This is the footnote.

