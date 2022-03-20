---
layout: post
title:  "Introduction to cypress"
date:   2022-03-20 19:08:28 +0600
categories: Cypress
---
In software development, Software testing has played a vital role. It gives confidence that the application works well, which it should be. Test automation gives a dimension to Software testing. There are several test automation tools available, In this series, we will talk about Cypress. Which is quite new and not selenium-dependent which makes it faster.  Let's dive into our Awesome [hopefully ✌️] journey.

# Install Cypress


## Windows :

To install Cypress in your machine first we need Nodejs. You can download it from [here](https://nodejs.org/en/download/) for windows/mac/Linux.

Now we will install Cypress in our project. We will use `npm init` to initialize the project with basic nodejs installation. For now, we can install Cypress in our project for our web application.


{% highlight javascript %}
npm install Cypress —save-dev
{% endhighlight %}

or

{% highlight javascript %}
npx cypress install
{% endhighlight %}

When we install cypress in our project, we can run 

{% highlight javascript %}
npx Cypress open
{% endhighlight %}

when we click this, it will open a test runner like this : 

![](/assets/images/test_runner.png ){: width="800"}

Here we can select our desire browser where the tests will run 

![](/assets/images/browser.png ){: width="800"}
