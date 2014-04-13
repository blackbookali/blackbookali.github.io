---
layout: post
title:  "some basic git commands"
date:   2014-04-06 11:20:50
categories: jekyll update
---

### SOME BASIC RVM COMMANDS

```
  # gem is rvm command
  # install installs the gem name supplied
  gem install jekyll

```
### Jekyll info
```
  jekyll new blackbookali 
  #made a new jekyll application called 'blackbookali'
```
### Ruby Environment command, RVM is another type
  rbenv --version 
  #helps you manage what version of ruby you are using, because you can have multiple versions of ruby in your computer

### Ruby Command
  ruby -v 
  #tells version of ruby you are using in that momement 

  git remote add origin somerepository.git 
  #connect the remote repository to the local repository, added the https line

  jekyll server -w (runs the jekyll applications, you run this command whenever you make changes to your jekyll application)

  ran sublime

### how to add changes to a git repository

  #step 1
  git status
  #how to see if there are local changes made to a git repository

  #step 2
  git add . -A (step 1 of how to commit changes to github repository)

  #step 3
  git commit -m "some message"(step 2 of how to commit changes to github repository)

  #step 4
  git push origin master(step 3 of how to commit changes to github repository)