---
layout: post
title: Coding Again!
---

As a developer who drifted into tech lead and then management 20 or so years ago, I have always wanted to get back to doing some coding again. A few years back I noticed that I had become out of touch on how developers code today. In the good old days all you needed was an editor (cue emacs versus vi war), a compiler and an incomprehensible make file and you were all set! However, the world has moved on and for years I have gotten by nodding sagely as a developer discussed test driven development, continuous integration, IDEs (sure vi is more than enough), frameworks and many more.

The good news is that the basics of writing some code have not changed that much (well sort of). I could quickly write loops and if-statements and sites such as [CodingBat](http://codingbat.com/java) can reacquaint you with the basics. However, what has changed is that programming languages have evolved to make it easier to work with data structures and objects in particular. For example writing loops in Java has gone from basic while and for loops to enhanced for loops to iterators and now lambdas. If I had just stuck with Lisp think of all the ugly syntax I could have avoided; okay the brackets were a killer.

Another major improvement is the tooling around software development with IDEs in particular (cue IntelliJ versus Eclipse versus ... wars). Yes these tools help with syntax but navigating a large software systems is infeasible without the support you get from IDEs to follow a chain of declarations and implementations. Combine that with plug-ins for code style, static analysis and most importantly test coverage and suddenly developers can have no excuse for creating poor quality code; alright they can moan to management if they are not given enough time.

Instead of a complex make file you now have tools like [Maven](https://maven.apache.org/) and [Gradle](http://gradle.org/) which can be integrated with tools such as [Jenkins](https://jenkins.io/) to support continuous integration from a [Git](https://git-scm.com/) repository.

(Aside: apologies that this is very Java centric but I know that the same development infrastructure exists for all modern programming languages from PHP to Ruby to .NET/C#.)

Once you understand the coding environment then you need to get familiar with a framework. I started with Spring but quickly discovered that Spring Boot encompassed most of what I needed to develop REST services. Frameworks seemed big and complex but after a few days I seen them as for helpers to provide the boring glue or pluming code and allow the developer to concentrate on the problem domain.

A long list of technologies but the key was to find a project and get started. With a few patient senior developers to help with the environment set up and a lot of online searching and tutorials I was able to make good progress and get back to being a developer.

It has been fun and definitely made me a better manager. I just need to keep up the coding!
