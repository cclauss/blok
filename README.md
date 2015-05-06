# blok
A simple static site generator for Pythonista + Editorial: write in Editorial and send to blok


**Editorial workflows**:
* [New post](http://www.editorial-workflows.com/workflow/5812790350577664/oa40mJqmRxY) - a UI for making a new post in Editorial. If you tell it to use the existing file, the contents of the file are added to the post metadata, like so:
```
title: Example title
date: 16-04-2015
slug: example-title
====
(existing file contents here)
```
* [Post -> Blok](http://www.editorial-workflows.com/workflow/5900215483629568/b1X0ckOwSCY) - sends the current post to Blok, where it is added to the posts folder as a markdown file. Then, when the site is built, the post will be included.
