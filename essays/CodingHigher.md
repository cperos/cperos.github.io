---
layout: essay
type: essay
title: Coding to a higher standard with ESLint
# All dates must be YYYY-MM-DD format!
date: 2021-09-23
labels:
  - Javscript
  - Learning
  - ESLint
---

Coding standards just might be the most useful technically useless thing I can think of.  They don't always change how your code runs, but it it is like the programmers equivalent of taking a messy room and making a clean room.   I remember in high school we used  to write essays for English class, and we had to use MLA format, and spell check and set up the margins and the citations had to be formatted a specific way.  None of this really adds information to the actual paper you have written, but it does present the essay you worked so hard on in a more presentable way to the user.  Coding standards like ESLint are like the programmer's MLA format when writing a paper, only when using a powerful yet lightweight IDE such as IntelliJ, implementing such a format becomes as easy as running good old spell check F7 in MSWord.

If I have learned anything this semester in 314 is a programmers life doesn't always have to be hard and grueling.  Often times sure it's unavoidable, but if there is often times a simple solution if you have the right knowledge.  By configuring my IntelliJ IDE to automatically use ESLint, I have brought my JavaScript coding from the amateur level to much more professional level without actually changing much about my personal coding style what so ever!  It is wonderful, I can hammer out rough code on my keyboard like barbaric heathen that has never seen the outside of a cave, and the IDE automatically tidy's it up and makes me appear like a civilized gentleman.  It is the biggest single leap in my ES coding I can make with the least amount of effort, so I am sold on it.

What is funny is I have am not a stranger to Lint and I didn't even know it!  In a previous class we had to run a python script called CPPLint.py to check our work.  We program in this particular class in a terminal over uhunix, with VIM as the most luxurious IDE that we are supposed to use, so the process of going through and deleting all the incorrect spacing and spaces would be a little tedious at times.  I recall I would often write an entire program, get it working and compiling with no errors, then run the python script only to find I had 80+ hidden lint errors in my code I was unaware of.  To make things worse one of my biggest deviations from the code I tend to do is extra blank lines so everything is spaced out and easier for me to read and debug.  This is always fun to fix because when you have dozens of errors to fix and you are deleting lines and you know last time you ran the script you had errors on a specific line number but cant keep track of how many lines you deleted, then you have to save and exit, run the script again, then go back with the updated numbers and fix them again.  Often times a cycle, having to exit, reopen delete a few likes, exit runt the script, over and over again.  Very tedious.

However with intelliJ I can click ESLint fix the current file a couple times and everything is automatically solved. This is why I think I love it, I know the alternative. I like it so much I have now downloaded IntelliJ CLion for my C/C++, with the CPPLint plugin for all my C/C++ coding needs, so it is changing the way I code in other languages as well. Aside from just being purely aesthetically pleasing, I think coding standards have other benefits as well. With ESLint in particular, I am writing more efficient code by using the correct variable notations. This is because JavaScript and ES are the same but kind of different, too, so if I can get a program working by any means of outdated shoddy JavaScript, and can have my program updated an rejuvenated, made current, trendy and hip with the click of a button.

But now that I have spoken of the praises of the standards of the code, I must get to the one downside of a coding standard that I see. That is what is the coding standard you have to use isnt up to your liking? What if you dont agree with the way ESLint likes to see something written. What if the coding stanard of a project of your liking isnt the coding standard that you know in your heart and love? It can be a tough thing to reconsile with sometimes as a programmer. Its like having to wear a school uniform when you have a style or a unique flair that is a little bit your own. I have this problem with one small thing in ESLint, and although it is just one small thing, it sometimes feels like my favorite shirt I like to wear violates the school dress code. Do you want to know what my one beef with ESLint is? The one simple thing that I do that just breaks my heart and makes me want to cry when I have to change is this

    Function Foo ()    // <----- My Way
    {
        ...... Function stuff here
    }

    Function Foo () {    // <----- ESLint Way
        ...... Function stuff here
    }

Now the reason I don't like this and try to only  update my code fully to ESLint standards immediately before a final commit, especially on a larger project would be because the first way, my preference, is easier to match an open bracket with a closed bracket quickly.  It just seems to line up a little better for me and it is also a little thing my brother taught me so I it kind of feels sentimental as well I suppose.  I know it isn't the standard for all languages, but I think it depends on the coding style you are using, and even what is considered standard for the language you are using. I know in some cases even the way you capitalize your variable names, and if you use camelCase in the wrong language it can be considered faux pas, but I like when function follows form so that particular way of bracketing works for me but not for my linty friends.  
Overall coding has been one of my favorite modules, and I'm not just saying that because it was easy, although if I am completely honest, yeah that's part of it too.

2021-09-23
