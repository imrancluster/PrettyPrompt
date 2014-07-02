# PrettyPrompt
*Clean & stylish prompt for bash that will change your feel about using bash ever after.* 

## Where did it come from?
Basically this idea of [PrettyPrompt] is brought to light based on the idea of vim's statusbar plugin [powerline] or [vim-powerline] (and later from [vim-airline]). Later I've *stolen* some code from another vim plugin [promptline] which does somewhat same thing in a different way.
It could be a question then why [this][PrettyPrompt] where there is already [promptline]. The answer is, the dependency to a vim plugin for creting even a simple prompt with style and how I can update the prompt with promptline looks a bit complex to me. And as I already came to a solution, I wanted to merge the **best of both**. But to be honest, promptline is awesome!

## Features

*  Easy configurable section (and sub-section), you'll see what you want to (username|pretty-path|git-branch is set to show by default).
*  Show git branch with unstaged change indication by color (*green* for clean and *red* for changed by default).
*  Design as you wish: 
    *  colors (background and foreground of sections)
    *  charecters (section separator, sub-section seperator, git branch, ..)
    *  path format
    *  ... add more!
*  Can work any with regular font/unicode symbles, but look awesome with powerline symbols. One powerline font patch (Menlo) is added with this repo.


[vim-airline]:   https://github.com/bling/vim-airline
[vim-powerline]: https://github.com/Lokaltog/vim-powerline
[powerline]:     https://github.com/Lokaltog/powerline
[promptline]:    https://github.com/edkolev/promptline.vim
[PrettyPrompt]:  https://github.com/ashikahmad/PrettyPrompt  

## Install

.. todo ..

## Configurations

.. todo ..

## Using Powerline patched font

.. todo ..
