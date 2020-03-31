# my-blog

## My notes:
assets - css - styles.scss where to add styles
_site - assets - css - styles.css (all the styles) - doesn't save 

jekyll serve or bundle exec jekyll serve - on localhost:4000

## How to create a post
The _posts folder is where your blog posts live. You typically write posts in Markdown, HTML is also supported.

To create a post, add a file to your _posts directory with the following format:

YEAR-MONTH-DAY-title.MARKUP
Where YEAR is a four-digit number, MONTH and DAY are both two-digit numbers, and MARKUP is the file extension representing the format used in the file. For example, the following are examples of valid post filenames:

2011-12-31-new-years-eve-is-awesome.md
2012-09-12-how-to-write-a-blog.md
All blog post files must begin with front matter which is typically used to set a layout or other meta data. For a simple example this can just be empty:

---
layout: post
title:  "Welcome to Jekyll!"
---

# Welcome

**Hello world**, this is my first Jekyll blog post.

I hope you like it!

Add link to navigation directory to see on page

[Jekyll Docs](https://jekyllrb.com/docs/usage/)