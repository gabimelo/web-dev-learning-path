# web-dev-learning-path
> An opinionated guide to learning web development.

This is my attempt to create a learning path for those interested in web development - whether you're a total beginner, or you just want to improve your skills. There's so much information available online nowadays that it's easy to get lost in the middle of it all without knowing where to begin.

The *opinionated* in the description of the repo is to show that this is just the way I see that it could be done, but it might be different for everyone, so feel free to adapt accordingly.

I'm under the impression that lately, especially given the rise of popular JavaScript frameworks, many people might be skipping the traditional HTML and CSS basics - and even the basic understanding of how a website actually works - and jumping straight to some framework or library. That might work for some people (and be sure to jump to that if that's what you're looking for) but I do believe a solid knowledge on the basis of web development might be beneficial to your web dev skills, so I added material on those basic stuff as well.

For some of these topics, I just linked some resources. On others, I gave a very brief explanation on the topic. On others, I did a little bit of both. However, this is just meant to show what can be studied and learned, and show topics that might be further looked into for learning web dev.

## Here is how I would structure the learning path:

1. Basic programming
    * It would be good to have some basic algorithms and data structures background knowledge - it might be good looking for a course on it (whether it's online or not).
    * I find that some of these things work better and more easily on UNIX systems, so if you're running in Windows, maybe it would be nice to get a Linux dist installed. Also, most servers run Linux systems, so it would be helpful to know your way around them.
    * Having a good development environment is very important. Basic text editors, such as Sublime and Atom are very popular for web dev. There are some plugins that help you customize them for the specific languages that you're developing in. I would recommend looking up some tips for that (e.g. Google something like "Sublime set up for JavaScript development")
    * I believe having good programming practices make a huge difference, and would recommend this book: [Clean Code: A Handbook of Agile Software Craftsmanship, by Robert C. Martin](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship-ebook/dp/B001GSTOAM)
        * I also wrote an [article on this topic](https://medium.com/@gabimelo/how-to-write-code-that-is-readable-and-understandable-by-others-and-yourself-aedf739650fe)
    * Having some understanding of good software development project management might help (although maybe on a later stage of the learning process). I would recommend getting to know Agile and Scrum concepts:
        * https://www.scrum.as/academy.php
        * Software that might help:
            * Jira
            * Trello


2. What is a website

Seems trivial, but with the advance of the web, it has become a more complicated architecture than it used to be. Specially, with the advances of "web apps". What is a web app? What is a website? 

It is good to be able to really understand these terms and to have some understanding of the information flow that are involved to have a website on the browser.

[I wrote an article that might help with this](https://medium.com/@gabimelo/what-are-apps-how-do-i-develop-one-8fde8535896d), but am also open to accept suggestions on resources for this topic. I haven't added anything on information flow between browser and server on my article, so something on that would be nice - although I might write something on this sometime as well.

3. Front and back ends

There are two main sides to web development, that are always mentioned, and that is important to understand. But they are quite simple:

The front end is what you actually see. It's the presentation of content, styling and animation that is run on the browser.

The back end is responsible for most of the business logic, and runs on the server. Lately, with the advances on web apps, the front end started having some logic being executed on it, so this distinction has become fainter.

You might read some more into these, and see if you're interested in learning both of them (so you could be a full stack developer), or if you'd rather focus on one of them.

4. Git & basic command line
  * Git is a tool for software versioning control. It allows for very easy collaboration on code between multiple people, and an easy way to restore your code to previous versions. These are some resources to get you going with Git:
      * https://www.codeschool.com/courses/try-git
      * http://rogerdudler.github.io/git-guide/
      * https://www.atlassian.com/git/tutorials/using-branches
  * Some existing workflows for Git:
      * https://www.atlassian.com/git/tutorials/comparing-workflows
  * It is also a good moment to familiarize yourself with the terminal (command line). This is the tool with which you configure and put your web servers to run, so it's nice to feel comfortable interacting with it. I won't recommend any specific guide or tutorial on this, but would rather suggest learning from usage (if you start using a Linux OS this will probably come naturally).

5. HTML
  * This is the basis for web pages. It is what structures the content that is being shown. The link below show all of the available HTML tags, and their explanation.
      * https://www.w3schools.com/html/default.asp

6. CSS
  * CSS is the language for styling web pages.
      * https://www.w3schools.com/css/default.asp
  * Bootstrap is a library that allows for a fast way of designing responsive websites (the ones that show up nicely on all screen sizes, both desktop and mobile). It might be starting to get a bit outdated, with the advances on single page apps and PWAs ([which you can read about on the article I linked on section 2](https://medium.com/@gabimelo/what-are-apps-how-do-i-develop-one-8fde8535896d)) but depending on what you're going to be working with, might be useful.
      * http://getbootstrap.com/
  * SASS provides a way of splitting your CSS in multiple files, and it also adds some nice functionalities. Might be worth giving it a look, although it might also be getting a bit outdated, for the same reasons as bootstrap.
      * http://sass-lang.com/guide

7. JavaScript
  * JavaScript is a programming language that browsers are able to execute. It allows for everything from animating content on the browser to running some logic that your website requires.
      * W3 reference: https://www.w3schools.com/js/default.asp
  * JavaScript has also made possible the concept of single page apps. 
      * I go into them, very superficially, on the [above mentioned article](https://medium.com/@gabimelo/what-are-apps-how-do-i-develop-one-8fde8535896d))
  * Another thing that has become popular recently are some frameworks and libraries, that allow for the development of single page apps. These frameworks and libraries have changed a lot how front end web development works, and provides for a course of their own. There are plenty of tutorials and online courses on them. You might also have a look at articles explaining the differences between them, to be able to pick one (but I don't have any resources to link to on this matter :( ) Here are some of the most popular front end frameworks/libraries (as of March 2018):
      * AngularJS https://angularjs.org/
      * React https://reactjs.org/
      * Vue.js https://vuejs.org/

8. Back end

The back end is where most of the business logic runs, as I mentioned above. It is the "server side". It's where the connection to the database happens.

It has been changing a lot lately, with architecures such as the "serverless", which use resources of cloud providers to run back end logic, without needing an actual back end server for your app. However, traditionally, the back end runs as a server side application. Different languages can be used for it, and each of these have frameworks/libraries for implementing app servers. The most common languages for back end web apps are:

  * [Node.js](https://nodejs.org/en/) (JavaScript)
  * Python, with frameworks such as [Flask](http://flask.pocoo.org/) or [Django](https://www.djangoproject.com/)
  * Java, with frameworks such as [Spring Boot](https://spring.io/projects/spring-boot)

I have an impression that Java is less used, but maybe this is not true when it comes to large enterprises. There is also PHP, but I think it's a bit legacy and wouldn't recommend going into that if you're just now getting into software development.

Although these languages might have pros and cons between them for web apps, I think a good criteria for choosing the first one to start learning could be just your familiarity with these languages. Once you understand how server side apps are developed, it's easy going from one of these languages/frameworks to another one, if needed. My only recommendation is, if you choose Python, to go with Flask. Given that most websites nowadays work as single page apps, your server side ends up being pretty much just the API with which you'll communicate from the front end, and I think Flask is best suited for this than Django, as it is more lightweight (and consequently also easier to learn).

9. Where to go from here:

This is just the main things that I think are good for every developer to have at least som ebasic understanding of. However, there are many different things that you can choose to focus on:

    * Front end and front end frameworks
    * Back end/API development 
    * Infrastructure and DevOps
    * UI/UX for the front end
    * PWAs

This is a very big topic, so of course there are many ways of looking at it and learning it. If you have suggestions, feel free to open issues and/or PRs!
