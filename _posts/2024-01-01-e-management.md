---
title: 'Feimi&#39;s Subtitiling Notebook (5) - File Management and Collaboration'
date: 2024-01-01
permalink: /posts/240101_5/
tags:
  - subtitling
---

For team collaboration, it is preferable to always keep the file up-to-date among teammates and make changes traceable. I don't know if this sounds like anything to you, but for me, this reminds me of what programmers do. In fact, after testing in practice, [Git](https://en.wikipedia.org/wiki/Git){:target="_blank"} has proved to be a very helpful tool in online file exchange, change tracking, and branch management. 

For example, Git compares the file before and after every commit and shows what has been changed. As seen in the screen shot below, red lines are contents in the old file and green lines shows what has been changed. This makes it easy and clear to track what other people has worked on. 

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="/images/240101_5_1.png" width="70%" height="70%">
    <br>
    <div style="color:orange; font-size: 0.8em;
    display: inline-block;
    color: #999;
    padding: 2px;">An example of file differences showed by Git</div>
</center>

\
On the other hand, branch allows multiple versions of a file to be worked on simultaneously. This can be work of different people, or simply different parts of a video. For example, I have tried to deal with human speech part and lyrics part from the same video in different branches. In the end, thay can be easily merged and all the changes can be collected together. 

For new users, if you would like to learn more about Git, there are a lot of tutorials available on the internet, [this one](https://www.w3schools.com/git/){:target="_blank"} and [this one](https://learngitbranching.js.org/){:target="_blank"} as two examples.  

Git repositories can be hosted on many git server providers, like [github](https://github.com/){:target="_blank"} or [GitLab](https://about.gitlab.com/){:target="_blank"}. My subtitile files are placed on a [gitee repo](https://gitee.com/ifeimi/akbsub){:target="_blank"}, however this is a private repo so you are probably not able see it. 