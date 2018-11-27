# Introduction to GIT
## Introduction
In the age of programmability, git and github becomes an awesome resource for version control.   While the normal use for both of these tools is for software development, there is a great number of other uses as well.   For example, users may want to maintain configuration snippets for routers or switches or you may want to maintain documentation.   

In this tutorial, I'm going to provide a overview of a git workflow that is very useful for multiple people working on a single project.   There is really alot of documentation on git, but sometimes it is a bit difficult to find on how you can apply git or github to your own personal needs.   Instead of reading a reference manual, hopefully this tutorial will serve as a launching point to get started with git.

I would really like to thank the following people since I borrowed some ideas and text from them and made this a bit more concise:

* Aditya Sridhar ([https://adityasridhar.com/)]() - Aditya Sridhar wrote the original tutorial that I used to build off of.  It is a great tutorial and I wanted to add more detail to it.

## What is git and github anyway?
These are two very closely related tools that serve as a great solution for source control and revision control.

### git
git is an opensource revision control system that allows you to manage your source code history.  git is free to download and install and a great solution for anyone wanting a simple and easy to use method for maintaining revision histories of your files.

git is provided via several methods.

* OSX - git is provided by the Mac OSX package called XCode.  most OSX installations do not have XCode installed by default.   Therefore you can install it via the App Store.
* Windows - git is provided free of charge at the following link [https://www.atlassian.com/git/tutorials/install-git](). Once you download and install it, you will be able to leverage git on Windows.

### github
github is a hosting service for git repositories.  There are multiple providers of repositories that work with git.   However, github is really used by alot of people. 

Installation of a repository can also be a on-premise.   This is useful for customers that would like to maintain their own repositories. Obviously corporations don't want to publish their proprietary source code in the public domain, so they can choose to host the repository on premise.  However, the public github is used by millions so users can share and work on each others source code.

All of the examples, in this tutorial will be done using mac OSX.   However, they should also work with Windows with minor changes.   In addition, although we are showing examples using github, any hosting service that supports git should be supported.


## Table of Contents
* [Lesson 1 - Creating my first git repository](lesson1/lesson1.md)
* [Lesson 2 - Managing a simple branch workflow](lesson2/lesson2.md)
