---
layout: post
title: Learning from Errors
---
I am currently go through a tutorial that I found on a blog.  So far I'm liking it. The author is using Test Driven Development in the tutorial and I love this.  My whole goal is learn the best practices of coding.  I  heard and read that it is easy to learn the bad practices when learning a programming language on your own.  

One Lesson would like to share. 
Copy and paste is not always your friend.  Last Tuesday, I spend at least an hour troubleshooting an error I received when I running unittests.  I know.  How does one get an error when you just writing the exact code in tutorial.  Well, you don't know me lol.  I kid you not that every step of the way, an error was thrown when I ran the development server. It always ends up with me finding out  that cause is a missing or extra punctuation or even a misspelled word.  

Well back to my original point.  I copied the code straight from the tutorial into [PyCharm](https://www.jetbrains.com/pycharm/) ( By the way I love this IDE). Sure enough,  errors abound when I run the development server.  Remember, just because the error is  states there is error is on link 3x, does not mean the error is there. The issue could be with code before the error line number.  Well, I found that line of code and couldn't understand how could this be when the text and punctation( at least so I thought) were exactly the same as the tutorial.   

After close examination, I realized that I was wrong.  The single quotes were not exactly the same. I re-typed the single quotes in my IDE and sure enough I was able to run development server without an error.  It kind of makes sense since characters on a the blog will not necessary look the same or be interpreted when copied into an application. 

All this to say always verify that what case, punctuation , etc when using copy and paste. It will probably save you a hour.  I hope you learn from my mistakes as I am doing. 

Sidenote: I actually like when the program fails or there is an error. I am learning so much more I research the error and look at other resources like [Stackoverflow[( http://stackoverflow.com) to help me troubleshoot. 

Tutorial:
[Marina Mele's Django Tutorial](http://www.marinamele.com/taskbuster-django-tutorial)
