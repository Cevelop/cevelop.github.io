---
layout: post
active: news
title:  "Cevelop on Mars Released, Update Now!"
---

**Eclipse Mars** has arrived, including a new version of the CDT <span style="color:red;">C/C++</span> Development Tools on which Cevelop is built. The most important news and changes of the Eclipse platform are summarized in <a href="https://www.eclipse.org/eclipse/news/4.5/platform.php" target="_blank">Platform New and Noteworthy</a>. The platform has received many small fixes, stability and performance improvements. For example, the user interface has been cleaned up a bit (better icons, dark theme) and made more customizable.

Eclipse CDT now comes with support for <a href="https://www.docker.com/" target="_blank">Docker</a> to manage images and containers directly in Eclipse. It also allows you to run and debug <span style="color:red;">C/C++</span> applications in a container. For more details, see <a href="https://wiki.eclipse.org/CDT/User/NewIn87" target="_blank">New in CDT 8.7</a>.

Other than being founded on Mars, Cevelop 1.3 comes with a new version of CUTE and improved refactorings. For example, <a href="https://twitter.com/petersommerlad" target="_blank">Peter</a> wrote a quick assist that refactors typedefs to using aliases:

![Replacing typedefs with using](/img/replace-typedef-with-using.png)

And you can also inline typedefs:

![Inline typedef](/img/inline-typedef.png)


We recommend to [download a fresh copy of Cevelop](/download) because updating is still not reliable on all platforms (you can of course continue to use your existing workspaces). 

In the previous blog post, we promised a brand new plug-in that helps you refactor char-pointers to proper <span style="color:red;">C++</span>-string objects. Unfortunately, this needs some more polishing and has thus been delayed to the next release, planned for fall 2015. 

<p class="pull-right">
  <em>&mdash; Mirko Stocker</em>
</p>
