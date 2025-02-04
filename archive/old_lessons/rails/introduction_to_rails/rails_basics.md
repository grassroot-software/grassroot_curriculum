### Introduction

You're probably here because you want to learn the [Ruby on Rails](http://rubyonrails.org/) framework but you may not be entirely sure what it is.  Well, Rails is just a bunch of ruby code written to handle the parts of a web application that you don't often want to think about.

Rails uses, as you'll often hear, "convention over configuration".  That means that the creators of Rails have made a lot of decisions for you about how things should be structured and how the code should run.  You can change them, but it's best if you just go with the flow and work within their rules (especially as a noob).

Think of it like buying a car -- you probably don't care about individual specifications of engine parts, which companies shipped the parts to the final production facility, or even what legislative requirements a car has to meet ... you trust the manufacturer to have figured all that out and you just want to be able to buy the nice looking car knowing that it works as intended.  Rails is your Ruby manufacturer.

Why Rails?  Why not.  There are dozens of possible technologies out there to choose from and, frankly, they do pretty much the same things.  Rails is attractive because it's a relatively straightforward and very well documented framework that's used by tons of great startups and tech companies today and it has a very strong community of developers and students who support it.  It lets you put up a functioning website in hours, not days or weeks.  The "in" tech will probably be something completely different in a few years, as it always is, but Rails presents a great platform on which to build the skills you need to carry you to that next phase.

Because Rails has made a lot of decisions for you, you can work incredibly fast.  You can have a website up on the internet (though it won't look like much) within a couple minutes.  The very first time you generate a new project, everything is in place so you just have to fire up your local server (by typing simply `$ rails server`) and you'll already see the Rails welcome page up there.  Then it's just a matter of plugging in all the pieces you actually need to make your rich web application run.

It also means that you can start immediately making small changes and seeing how they affect your application where before you would have had to build a ton of infrastructure and write lots of code before seeing a single thing change live.  Rails makes your life a whole lot easier!

Rails also firmly organizes your code using an MVC pattern which you will come to know and love.

The best way to understand Rails is to use it, so we'll spend a bit of time on some videos and reading but you'll mostly be building your own Rails sample app.  You may have no idea what you're doing, and that's okay, but at least you should begin to understand what you DON'T know and what you'll want to pay attention to going forward.  A good tactic is to write down all the things that confuse you and either go looking for them on your own or keep them in mind for later when we do our deep dive into Rails.

### Learning Outcomes
Look through these now and then use them to test yourself after doing the assignment.

* What is Rails?
* What language is Rails written in?
* Refresher: What are gems?
* What are the seven gems that make up Rails?
* What is the purpose of the gemfile?
* What is the command to create a new Rails app from the command line?
* How is a GET request different from a POST request?
* What is REST?
* What is a view?
* What is a controller?
* What is a model?
* What is the Ruby Standard Library?
* What does the Bundler do for Ruby Gems?
* What is the Ruby load path?


### Assignment

<div class="lesson-content__panel" markdown="1">

  1. Read Daniel Kehoe's excellent [What is Ruby on Rails?](http://railsapps.github.io/what-is-ruby-rails.html) introduction to get a good grasp on what we're working with.
  2. The main [Grassroot Rails course](http://www.grassroot.herokuapp.com/courses/ruby-on-rails) primarily uses Michael Hartl's fantastic "Ruby on Rails Tutorial". Get started coding right away by diving into [Chapter 1](https://www.learnenough.com/ruby-on-rails-4th-edition-tutorial) of the book now! Hartl spends a fair amount of time getting everything setup correctly, and he suggests using a Cloud9 development environment. At this point, you should have already done the [installations](https://learn.grassroot.academy/courses/foundations/lessons/your-first-rails-application?ref=lnav) that will allow you to work on your own machine, so you can skip section 1.2. The rest of the book is covered in a later section, so just work through Chapter 1 for now.
  3. Get another quick explanation of Model/View/Controller in [this short YouTube video from Lynda.com](http://www.youtube.com/watch?v=3mQjtk2YDkM)
  4. Read the [Ruby on Rails Guides: Getting Started](http://guides.rubyonrails.org/getting_started.html) and try to follow along with the application they build (you don't need to build it, but try to read it through. You'll be building soon enough). By the end, your head will probably be spinning a bit but don't worry, that's normal. You'll understand this stuff no problem by the time you do the Rails course later in the curriculum. The Ruby on Rails Guides provide some of the best documentation for the Rails framework out there, so it's good to start getting familiar with how they look.
  5. Check out the [Using Libraries section](http://webapps-for-beginners.rubymonstas.org/libraries.html) from Ruby Monstas to learn about the Ruby Standard Library, Rubygems, Bundler, and the Ruby Load Path.

</div>

### Additional Resources
This section contains helpful links to other content. It isn't required, so consider it supplemental for if you need to dive deeper into something.

* [MVC for Noobs](http://net.tutsplus.com/tutorials/other/mvc-for-noobs/) uses PHP as an example later in the article, but you should get the gist of it.
* [How I Learned Ruby on Rails](https://medium.com/how-i-learned-ruby-rails/e08c94e2a51e)
* [Wonderful explanation of how REST and HTTP works](https://www.youtube.com/watch?v=Q-BpqyOT3a8)
