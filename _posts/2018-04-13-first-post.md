---
layout: post
title: Takeways from exploring a messy dataset
---
I'm running on 5hrs of sleep per night. For some, that's the norm. Or maybe even a generous amount. For me, that's torture. I normally run on 8. And no, I don't drink coffee or tea, nor do I plan to.

The reason why I'm short on sleep is because I'm in a data science bootcamp. The best way to illustrate the intensity is to tell you that we started on Monday and our first project was a complete data analysis and presentation over 3.5 days. 

To keep my head above water, I tried my best to stay organized and pull myself back when I realized I was going down a rabbit hole. 

Jupyter Notebook became both  my friend and my enemy. 

Here are the pluses:
1. The user interface is intuitive and the keyboard shortcuts are plentiful
2. The ability to execute small chunks of code and immediately see the output in line makes debugging easier 
3. The ability to run all cells above or below current cell. 

These are what caused me headaches:
1. The execution of code is very order-dependent
2. The kernel would keep crashing and force me to re-run my notebook
3. 

What I did to try to alleviate my headache:
Installed the ipython nbextension, which constructs a table of contents for a notebook. That allowed me to easily view all of the sections that I specified using markdown style headers.

What I'd like to see added  if it doesn't already exist:
1. A LOC that is generated within the notebook itself. That way, anyone who doesn't have the extension installed on their local computer could still easily navigate my notebook.
2. Collapsing of sections of the notebook. 
3. Have a way to specify which cells to run, outside of run above or run below. 
I look forward to not having to be dependent on jupyter-notebook for my projects. That should hopefully start next week.  

So what are the best ways   

[Jekyll](http://jekyllrb.com) is a static site generator, an open-source tool for creating simple yet powerful websites of all shapes and sizes. From [the project's readme](https://github.com/jekyll/jekyll/blob/master/README.markdown):

> Jekyll is a simple, blog aware, static site generator. It takes a template directory [...] and spits out a complete, static website suitable for serving with Apache or your favorite web server. This is also the engine behind GitHub Pages, which you can use to host your project’s page or blog right here from GitHub.

It's an immensely useful tool. Find out more by [visiting the project on GitHub](https://github.com/jekyll/jekyll).
