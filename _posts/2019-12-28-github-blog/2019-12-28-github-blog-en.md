---
layout: post
lang: en
permalink: /github_blog/githubBlog/2019/12/28
title:  "Jekyll Installation"
date:   2019-12-28 00:00:00 +0900
categories: githubBlog_en
background: '/img/tech/githubBlog/bg-githubBlog.jpg'
---
<h1> Overview </h1> 
- In order to install GitHub blog, you have to install theme and create a basic project first. In case of my blog, jekyll theme has been installed on Mac OS.
<br>

<h2> Installation </h2>
<hr>
Jekyll can be installed on Mac OS, Windows, and Linux Ubuntu. Here are some tips how to install jekyll on Mac and Windows. Most of the processes are same. If you want to get more information regarding theme, you can directly check the <a href="https://jekyllrb.com/docs/installation/" target="_blank">jekyll website.</a>
<br>

<h2> Version </h2>
<hr>
  Currently, my blog uses the following version.
<br>
  <ul style="list-style-type:disc;">
    <li>Ruby: ruby 2.6.3p62</li>
    <li>Jekyll: jekyll-3.8.6</li>
  </ul>   
<br>


<h2> Ruby Installation </h2>
<hr>
  Since jekyll is the one of Ruby Gems, you need to install Ruby first.
<br>

<h3> Install Ruby on Mac </h3>
  <code> brew install ruby </code>

<h3> Install Ruby on Windows </h3>
  <ul style="list-style-type:disc;">
    <li>Use Ruby installer.</li>
    <li>Download: RubyInstaller for Windows</li>
    <li>Install Ruby + Devkit version 2.4 or higher.</li>
  </ul>    

<h3> Check Ruby installed </h3>
  <code> ruby -v </code>
<br>


<h2> Jekyll Ruby Gem Installation </h2>
<hr>
  If you successfully installed Ruby, you could install Jekyll Gem by utilizing Ruby.
<br>

<h3> Jekyll Ruby Gem Installation </h3>
  <code> gem install bundler jekyll </code>

<h3> Check Jekyll Ruby Gem installed successfully </h3>
  <code> jekyll -v OR jekyll --version  </code>
<br>

<h2> Create a basic project by Jekyll Gem </h2>
<hr>
<h3> Create a project </h3>
  You can create jekyll project by jekyll new [project name] command

  <code> jekyll new daveleee.github.io </code>
  And then you can find the directory of your new project following the command below:
  <code> cd daveleee.github.io </code>
  Here's some default directory files once you successfully created a new project:
  <code>
  |-- posts
  | |-- 2020-03-19-hello-jekyll.markdown
  |-- .gitignore
  |-- 404.html
  |-- about.md
  |-- index.md
  |-- Gemfile
  |-- Gemfile.lock
  </code>
<br>

<h3> How to start Jekyll </h3>
  <code> bundle exec jekyll serve </code>
  Once it is started, you could access to "http://127.0.0.1:4000", which is a local server by opening a browser.
<br>

<h2> Reference </h2>
<hr>
Jekyll official website: <a href="https://jekyllrb.com/" target="_blank"> https://jekyllrb.com </a>
