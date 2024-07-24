# amFOSS Blog

## Build locally

Follow the following steps to set up and work with this project:

1. Fork, clone or download this project
2. Install [Hexo](https://hexo.io/docs)
3. Install all the dependencies with the command `npm install`
4. Use the command `hexo new post (name of post)`
5. Go to source/_posts to find the generated .md file
6. Use the template given below to write your blog.
7. Run the preview locally: `hexo server`
8. When everything seems fine, sned over a pull request !

## Template for writing your blog post

```
---
title: blog title
date: 2024-07-24 21:05:24
author: name of author
twitter: twitter username
categories:
    - Hackathons
tags:
    - cython2024
    - kochi
    - firstplace
---

**tl;dr**

+ something in brief aabout the blog
+ something else (if you want)

<!--more-->

## Blog Description

    write the description

```
## General Guidelines:

* Use `<!--more-->` after conveying the important points in the `tl;dr` and add a new line after `tl;dr` and before `<!--more-->`

* Use footnotes with [^1]

* You can choose the Slide HTML by providing it in the front matter.
    * slidehtml: true
    * slidehtml:
        titleMerge: true
        verticalSeparator: \n--\n
    * slidehtml:
        titleMerge:  true
