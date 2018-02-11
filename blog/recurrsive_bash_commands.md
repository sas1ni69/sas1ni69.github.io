---
# Page settings
layout: default
keywords: bash commands linux unix mac
title: Recurrsive Bash Commands
description: How to use bash command results in subsequent bash commands
micro_nav: true
author:
    title: About me
    title_url: '#'
    external_url: true
    description: My name is Hassanin Ahmed, I'm a Ruby and Javascript developer working on <a href="https://cliniko.com" target="_blank">Cliniko</a>. <br><br>I am based in Kuala Lumpur, Malaysia.
---
I found myself copying paths more often than not while trying to create a symlink for the current directory.

You could quickly use the $PWD variable but this is very specific to the working directory.

<code>
  ln -s $PWD ~/src
</code>

However there is another way I found to be useful, you can reuse bash results by using the "` &nbsp;" back tick quotes.

<code>
  ln -s `pwd` ~/src
</code>

It's a simple tip that could save you so many seconds in your lifetime! ;) JK I just avoid using the cursor if I can help it.
