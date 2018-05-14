---
title: "FirstImpressions"
date: 2018-05-12T15:35:16+01:00
lastmod: 2018-05-12T15:35:16+01:00
author: Richard Pape
cover: /imgs/code-gopher.png
catagories: ["golang", "noobs"]
tags: ["golang", "noobs"]
draft: false 
---
*These are my thoughts, I'm basing these on what I have heard, read or experienced - if I am misinformed, I am sorry - correct me, by all means but I am not purposfully spouting my own brand of nonsense or mistruth. Let me know and I'll try to edit where I am wrong*
# Try Go - These are my impressions after using Golang as my main language for 6 weeks
![Gopher with checkered flag](/imgs/code-gopherE.png)
If you came upon Go recently the chances are you've come upon the [Tour of Go](https:tour.golang.org/welcome/1).

I did the tour mid 2017 - I spent a few evenings playing with it. Exciting stuff for me a self taught developer who's
always wanted one language to beat them all - LOTR style. 

In 2018 I bought a good Go book([The Go Programming Language - by Alan A. A. Donovan, Brian W. Kernighan](https://books.google.co.uk/books?id=SJHvCgAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false) - This book is pretty best if you are transitioning to Go from another language, and want a rounded view of it all) and took it away on holiday to read and really, since then almost everything has been pretty Go focused.
# The story so far...

The best way to understand why I have been attracted to Go is to look at my past list of languages I've put time into.

**PYTHON**
 I see myself as a big a Python fan even now, Python is awesome especially for data science, but Python is
apparently slow and awesome in equal parts.

**RUBY**
 I love Ruby for similar reasons to Python, it has a lot of good stuff going for it but I've always been wary that there was not a lot of jobs using it near me so I have never used it for more than side projects.

**NODEJS**
JS has never been a favorite but I have clocked many hours using it and I can write it pretty well in the browser and NodeJS has been fun to play with, especially the async
stuff for building CLI tools. In fact JS is really good fun but to be honest I found it easier to write bad JS than I found it to write
good JS, or didn't feel I could always tell the difference (I best move on as I am probably not qualified to backup[ that statement)

**C,C++,C#,Java, Delphi** All these fall into the same category - cool but often they seem too complicated, C and C++ are rarely used on
the web and to ignore the web is pretty much ignoring a big part of life. Using C# and Java have a
really good chance of employment but C# is better developed on Windows (I am a Linux fanboy) and when I dabbled in Java (and Delphi for that matter) it always seemed to
trip over it's own releases and be needing me to write more than was needed in another language.

I could go on - **PHP, Scala, Julia, Rust, Elixir, R** I've dabbled and enjoyed bits of them all to a degree but **Go** grabbed
me as a more rounded language worth spending more time on.

# Why Go?:
Is a fair question, hopefully these seem like fair answers:

- **Fast** - If I am going stop using Python I was needing something that addressed it's achillies heel - speed.
- **Statically typed / Lazy assignment** - I wanted to learn to use a statically typed language mainly to allow me to segue into being a more rounded programmer but I'm lazy when it comes to writing `var ... string`. Go allows you to statically type but does not make you if it is not needed with the "magic"`:=` assignment - a nice feature that got me interested.
- **Lazy formatting** - Most languages have a defined style like PEP8 in Python and house styles of companies which create needless friction among programmers. The Go team just decided to build a
  formatter into the language from early on. Write bad code and then throw it to the formatter.
- **No semi colons** - This is a lie there are semi colons but they are added by the compiler rather than the
  programmer except for in a few instances where they are needed.
- **Optional OOP / Functional** - I'm an advocate of using the right tool for the job, Go lets you choose the method you feel is best and also mix them. Arguably some other languages do too but Go seems to have a good balance of this.
- **ASYNC / Concurrency** - This is a massive topic in modern languages, Go has been built to do this as standard other
  languages have evolved to do this as an after thought. Go routines and channels blew my mind.
- **Readability** - I've already mentioned laziness twice. I read code as much as I write it, if not more, I don't want to write 10 lines when one line will do and I don't wan to read 10 lines of code when one will do. Go is
  easy to read - Win win. 

# Conclusion:

Go in my eyes deserves all the excitement It is getting right now. It is fast, each release is apparently backwards
compatible, it has an easy import system built into it, it is flexible, it has a thriving community, lots of projects
use it (Kubenetes, Hugo, HashiCorp) & it has a robust test suite built in. Employment wise I
can only see it becoming more popular. Go Try Go, you might like it.
