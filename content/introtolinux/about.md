+++
title = "About"
date =  2020-08-22T08:32:17+04:00
weight = 2
+++

During a traditional Computer Science education, chances are you will take plenty of classes that teach you advanced topics within CS, everything from Operating Systems to Programming Languages to Machine Learning. But there is one essential topic that is rarely covered and is instead left for students to pick up on their own: *computing ecosystem literacy*.

 Usually students have limited knowledge of the tools available to them. Computers were built to automate manual tasks, yet students often perform repetitive tasks by hand or fail to take full advantage of powerful tools such as version control and text editors. In the best case, this results in inefficiencies and wasted time; in the worst case, it results in issues like data loss or inability to complete certain tasks.

This guide is intended to be pragmatic and practical, and it provides hands-on introduction to tools and techniques that you can immediately apply in a wide variety of situations you will encounter.

#### Command Shell

How to automate common and repetitive tasks with aliases, scripts, and build systems. No more copy-pasting commands from a text document. No more “run these 15 commands one after the other”. No more “you forgot to run this thing” or “you forgot to pass this argument”.

For example, searching through your history quickly can be a huge time saver. In the example below we show several tricks related to navigating your shell history for convert commands.

**TODO:** Add gif here

#### Version Control

How to use version control properly, and take advantage of it to save you from disaster, collaborate with others, and quickly find and isolate problematic changes. No more rm -rf; git clone. No more merge conflicts (well, fewer of them at least). No more huge blocks of commented-out code. No more fretting over how to find what broke your code. No more “oh no, did we delete the working code?!”. We’ll even teach you how to contribute to other people’s projects with pull requests!

In the example below we use git bisect to find which commit broke a unit test and then we fix it with git revert.

**TODO:** Add gif here

#### Text Editing

How to efficiently edit files from the command-line, both locally and remotely, and take advantage of advanced editor features. No more copying files back and forth. No more repetitive file editing.

Vim macros are one of its best features, in the example below we quickly convert an html table to csv format using a nested vim macro.

**TODO:** Add gif here

#### Remote Machines

How to stay sane when working with remote machines using SSH keys and terminal multiplexing. No more keeping many terminals open just to run two commands at once. No more typing your password every time you connect. No more losing everything just because your Internet disconnected or you had to reboot your laptop.

In the example below we use tmux to keep sessions alive in remote servers and mosh to support network roaming and disconnection.

**TODO:** Add gif here

#### Finding Files

How to quickly find files that you are looking for. No more clicking through files in your project until you find the one that has the code you want.

In the example below we quickly look for files with fd and for code snippets with rg. We also quickly cd and vim recent/frequent files/folder using fasd.

**TODO:** Add gif here

#### Data Wrangling

How to quickly and easily modify, view, parse, plot, and compute over data and files directly from the command-line. No more copy pasting from log files. No more manually computing statistics over data. No more spreadsheet plotting.

#### Virtual machines

How to use virtual machines to try out new operating systems, isolate unrelated projects, and keep your main machine clean and tidy. No more accidentally corrupting your computer while doing a security lab. No more millions of randomly installed packages with differing versions.

#### Security

How to be on the Internet without immediately revealing all of your secrets to the world. No more coming up with passwords that match the insane criteria yourself. No more unsecured, open WiFi networks. No more unencrypted messaging.

### Conclusion

This, and more will be covered in the guide, each including an exercise for you to get more familiar with the tools on your own.
Enjoy and have fun.

Happy Hacking
