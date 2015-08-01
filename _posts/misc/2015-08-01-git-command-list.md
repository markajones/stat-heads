---
layout: article
title: Git commands list
meta: 
category: misc
tag: git
---

This is a set of commands for using git.

## Post-install config

1. At its first use git will ask you to set config items to identify yourself in commits etc. Use `git config --global user.name "Marky Mark"` and `git config --global user.email an.email@myemail.com` (no quotes around the eamil are required).

## Repository Initialisation 

1. If you already have a project filestructure and want to put it under revision control, go to the root directory and do `git init`
1. If you are starting a project from scratch you can do `git init myproject`

A .git folder will be created which is where everything gets saved as we make additions to our project.

