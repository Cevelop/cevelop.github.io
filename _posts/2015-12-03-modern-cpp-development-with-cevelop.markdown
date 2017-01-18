---
layout: post
active: news
title:  "Modern C++ Development with Cevelop 1.4"
---

One of our primary goals with Cevelop is making it easier to write clean, modern <span style="color:red;">C++</span> code, using the latest <span style="color:red;">C++</span> standard. Unfortunately, this is not the default in Eclipse: multiple settings (compiler dialect, discovery options, static analysis checkers) need to be changed in each project.

Our new Cevelop release fixes this. The New Project wizard now includes a page to set the version of <span style="color:red;">C++</span> (defaults can be changed in the Eclipse preferences):

![New Project wizard](/img/elevenator-project-wizard.png)

This comes as part of the latest CUTE update and is explained in detail on [the CUTE Wiki](http://www.cute-test.com/projects/cute/wiki/Elevenator).  We also upgraded the underlying Eclipse CDT release from 8.7 to 8.8. Besides many debugging improvements, CDT now supports user-defined literals. See [New in 8.8](https://wiki.eclipse.org/CDT/User/NewIn88) for further details.

We recommend [downloading a fresh copy of Cevelop](/download) because updating is still not reliable on all platforms (you can of course continue to use your existing workspaces). 

<p class="pull-right">
  <em>&mdash; Mirko Stocker</em>
</p>
