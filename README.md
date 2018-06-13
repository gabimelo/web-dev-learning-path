# web-dev-learning-path
> An opinionated guide to learning web development.

This is my attempt to create a learning path for those interested in web development - whether you're a total beginner, or you just want to improve your skills. There's so much information available online nowadays that it's easy to get lost in the middle of it all without knowing where to begin.

The *opinionated* in the description of the repo is to show that this is just the way I see that it could be done, but it might be different for everyone, so feel free to adapt accordingly.

I'm under the impression that lately, especially given the rise of popular JavaScript frameworks, many people might be skipping the traditional HTML and CSS basics - and even the basic understanding of how a website actually works - and jumping straight to some framework or library. That might work for some people (and be sure to jump to that if that's what you're looking for) but I do believe a solid knowledge on the basis of web development might be beneficial to your web dev skills, so I added material on those basic stuff as well.

For some of these topics, I just linked some resources. On others, I gave a very brief explanation on the topic. On others, I did a little bit of both. However, this is just meant to show what can be studied and learned, and present the reader with topics that might be further looked into.

**This is a draft for now**, and I hope to add more material and improve it soon. I also hope to write some articles soon about some of these topics, and will link them here whenever they're available.

## Here is how I would structure the learning path:

1. Basic programming
    * It would be good to have some basic algorithms and data structures background knowledge - it might be good looking for a course on it (whether it's online or not)
    * I find that some of these things work better and more easily on UNIX systems, so if you're running in Windows, maybe it would be nice to get a Linux dist installed
    * Having a good development environment is very important. Basic text editors, as Sublime and Atom are very popular for web dev. There are some plugins that help you customize them for the specific languages that you're developing in. I would recommend looking up some tips for that (e.g. Google something like "Sublime set up for JavaScript development")
    * I believe having good programming practices is very beneficial, and would recommend this book: [Clean Code: A Handbook of Agile Software Craftsmanship, by Robert C. Martin](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship-ebook/dp/B001GSTOAM)
        * I also wrote an [article on this topic]()
    * Having some understanding of good software development project management might help. I would recommend getting to know Agile and Scrum concepts
        * https://www.scrum.as/academy.php
        * software that might help:
            * Jira
            * Trello


2. What is a website
Seems trivial, but with the advance of the web, it has become a more complicated architecture than it used to be. Specially, with the advances of "web apps". What is a web app? What is a website? 

It is good to be able to really understand these terms and to have some understanding of the information flow that are involved to have a website on the browser.

[I wrote an article on this](), but am also open to accept suggestions on resources for this topic.

3. Front and back ends
There are two main sides to web development, that are always mentioned, and that is important to understand. But they are quite simple:

The front end is what you actually see. It's the presentation of content, styling and animation that is run on the browser.

The back end is responsible for most of the business logic, and runs on the server. Lately, with the advances on web apps, the front end started having some logic being executed on it, so this distinction has become fainter. 

4. Git & basic command line
   * Git is a software for software versioning control. It allows for very easy collaboration on code between multiple people, and an easy way to restore your code to previous versions.
    * https://www.codeschool.com/courses/try-git
    * http://rogerdudler.github.io/git-guide/
    * https://www.atlassian.com/git/tutorials/using-branches
    * Some existing workflows for Git:
        * https://www.atlassian.com/git/tutorials/comparing-workflows
   * It is also a good moment to familiarize yourself with the terminal (command line). This is where you configure and put your web servers to run, so it's nice to feel comfortable interacting with it. I won't recommend any specific guide or tutorial on this, but would rather learn from usage (if you start using a Linux OS this will probably come naturally).

5. HTML
   * This is the basis for web pages. It is what structures the content that is being shown. The link below show all of the available HTML tags, and their explanation.
   * https://www.w3schools.com/html/default.asp

6. CSS
   * CSS is the language for styling web pages.
    * https://www.w3schools.com/css/default.asp
    * Bootstrap allows for a fast way of designing responsive websites (the ones that show up nicely on all screen sizes, both desktop and mobile) http://getbootstrap.com/
    * SASS is a way of splitting your CSS in multiple files, and it also adds some nice functionalities. Might be worth giving it a look.
        * http://sass-lang.com/guide

7. JavaScript
   * JavaScript is a programming language that browsers are able to execute. It allows for everything from animating content on the browser to running some logic that your website requires.
      * W3 reference: https://www.w3schools.com/js/default.asp
   * JavaScript has also made possible the concept of single page apps. 
      *
   * Another thing that has become popular recently are some frameworks and libraries, that allow for the development of single page apps. These frameworks and libraries have changed a lot how front end web development works, and provides for a course of their own. Here are some of the most popular front end frameworks/libraries (as of March 2018):
      * AngularJS https://angularjs.org/
      * React https://reactjs.org/
      * Vue.js https://vuejs.org/

8. Back end

The back end is where most of the business logic runs, as I mentioned above. It is the server side. It has been changing a lot lately, with architecures such as the "serverless", which use resources of cloud providers to run back end logic, without needing an actual back end server for your app. However, traditionally, it runs on a server application. Different languages can be used for it, and each of these have frameworks/libraries for implementing app servers. The most common languages for back end web apps are:
- [Node.js](https://nodejs.org/en/) (JavaScript)
- Python, with frameworks such as [Flask](http://flask.pocoo.org/) or [Django](https://www.djangoproject.com/)
- Java, with frmeworks such as [Spring Boot](https://spring.io/projects/spring-boot)

Although these languages might have pros and cons between them for web apps, I think a good criteria for choosing the first one to start learning could be just your familiarity with these languages. Once you understand how server side apps are developed, it's easy going from one of these languages/frameworks to another one, if needed. My only recommendation is, if you choose Python, to go with Flask. Given that most websites nowadays work as single page apps, your server side ends up being pretty much just the API with which you'll communicate from the front end, and I think Flask is best suited for this, as it is more lightweight (and consequently also easier to learn)

9. Where to go from here:
    * focus on front end frameworks
    * back end 
    * infrastructure
    * UI/UX
    * databases
    * Mobile/react native 
