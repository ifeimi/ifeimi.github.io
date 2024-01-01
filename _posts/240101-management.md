---
title: 'Feimi's Subtitiling Notebook (5) - File Management and Collaboration'
date: 2024-01-01
permalink: /posts/240101_5
tags:
  - subtitling
---

Introduction
======

For team collaboration, it is preferable to always keep the file up-to-date among teammates and make changes traceable. I don't know if this sounds like anything to you, but for me, this reminds me of what programmers do. In fact, after testing in practice, [Git](https://en.wikipedia.org/wiki/Git) has proved to be a very helpful tool in online file exchange, change tracking, and branch management. 

For example, Git compares the file before and after every commit and shows what has been changed. As seen in the screen shot below, red lines are contents in the old file and green lines shows what has been changed. This makes it easy and clear to track what other people has worked on. 

![example of file differences shown in git](/images/240101_5_1.png)

On the other hand, branch allows multiple versions of a file to be worked on simultaneously. This can be work of different people, or simply different parts of a video. For example, I have tried to deal with human speech part and lyrics part from the same video in different branches. In the end, thay can be easily merged and all the changes can be collected together. 

For new users, if you would like to learn more about Git, there are a lot of tutorials available on the internet, [this one](https://www.w3schools.com/git/) and [this one](https://learngitbranching.js.org/) as two examples.  

Git repositories can be hosted on many git server providers, like [github](https://github.com/) or [GitLab](https://about.gitlab.com/). My subtitile files are placed on a [gitee repo](https://gitee.com/ifeimi/akbsub), however this is a private repo so you are probably not able see it. 