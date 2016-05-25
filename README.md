# brawler
***Game of the year edition***

Dear Tyler,

hopefully this will help... http://rogerdudler.github.io/git-guide/

The most important/confusing this is that:

when you clone a repo... You are effectively pulling the most recent version of it off of github. You then can work locally on it. If you want to push your changes to the github and commit to my repo, you need to make sure that you are working in the *repository you cloned!* If you work in another similar folder you won't be able to push the changes. It has to be the cloned one! Confusing as fuck. Easier to explain/troubleshoot in person.

*Setup Git... kinda*

This is a not the best tutorial. If you want to learn how to use it on windows I recommend checking out a few tutorials on youtube.
***ZIP OR CLONE?***

 **Zip** Download the zip from this page (top left)

![clone](https://github.com/kaegbert/brawler/blob/master/read_imgs/clone.png)

 **Cloning** I recommend cloning it in terminal. You use command line but I'm pretty sure its the same process.

Download here:
http://git-scm.com/download/win

in command line you can type:

```
git clone https://github.com/kaegbert/brawler.git
```

That will download an exact source of the folder on the web to *your working directory*.
Later, you can pull or push (pull changes from the version online so if I make changes, or push your changes to the git page so I can pull them!)

If you don't want to do the command line bs, you can just download the zip and work that way. Also, I haven't used the git client but some people like it.

https://git-scm.com/download/gui/linux

FUCK THIS WE SHOULD JUST SKYPE SOMETIME SOON AND ILL EXPLAIN.

****HOW TO RUN BRAWLER****

Navigate to where the zip/cloned folder and click on the index.html. If you pull the index.html folder into a text editor you will notice that all it is doing is consulting the p5.library and calling up on the sketch.js

Here is a link to the p5 editor if you want to use it...
https://p5js.org/download/
