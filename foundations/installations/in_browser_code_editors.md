### Introduction

The first step for building any website is having the right tools. For us, that means setting up a development environment for writing good code.

Many online development courses use in-browser code editors  which give you the tools and programs needed to accomplish the task at hand and nothing else. You’ll use some of these online code editors throughout the early stages of The Grassroot Project since they’re great for getting started quickly. We shall use Replit.com code editor. However, the best way to set yourself up for long-term success is to operate in a real development environment.
 
You can think of code editors as specialized web development tools. They are highly customizable and offer many features that will make your life easier. There is nothing worse than spending 2 hours trying to figure out why your program isn’t working only to realize that you missed a closing bracket. Plugins, syntax highlighting, auto-closing of brackets and braces, and linting are just a few of the benefits of using a code editor. 


There are many code editors out there to choose from, but we suggest starting with an online code editor because of the ease of use as everything has been configured for instant  use.

We recommend [replit.com](replit.com) online code editor
Head to [replit.com](replit.com) and create an account. Take note of your email and password or store it somewhere safe.

When you're done creating an account
[Click here to Create your first workspace](https://www.dailymotion.com/video/k12P6H5GUp4Y5xyVeeu)
 

### Setting up Git on mobile Phone

Git is a very popular version control system. You’ll become very familiar with this piece of software throughout your study at GSA, so don’t worry too much about understanding it at this point. There are many lessons focused on Git later in the curriculum.

GitHub is a service that allows you to upload your code using Git and to manage your code with a nice web interface. GitHub and Git are not the same thing or even the same company.


### What is a Git Repository

A Git repository stores the history of changes made to your codebase by a collection of files and folders. As a developer, I have found this to be extremely useful since it allows me to keep a single view of the project codebase, back up a copy of the entire project history, easily retrieve older versions of the whole codebase or individual files, debug code, find out who wrote a specific change and a lot more.  This is extremely useful for development teams. 

Using Github an existing repository can be cloned and continued to be developed or a new repository can be created for an existing project that has not been tracked with version control.


You typically obtain a Git repository by creating one from your GitHub.com account  and then cloning it  from the remote Github.com https link to your local pc or mobile phone. In either case, you end up with a Git repository on your local pc or mobile phone, ready for work.


### What is a Git Remote ? 

A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub.com 


### How do you save small changes in your code to the copy of repository on your phone or pc? 

Adding commits keep track of our progress and changes as we work.. Git considers each commit as a change point or  a "save point". It is a point in the project you can go back to if you find a bug, or want to make a change. 

When we commit, we should always include a comit message. By adding clear descriptive messages to each commit, it is easy for yourself (and others) to see what has changed and when. A comit message should only contain a few words and be very descriptive of what changes you made. It is mandatory to keep your comit messages as short as possible.  Usually one sentence is recommended 

Note that a comit is only saved on your local repository,  that is the copy on your phone or PC. It is not saved to the remote repository on GitHub.  If you want it to be saved on the Remote repository on GitHub.com then you must push your comit.

###  What is Push ? 

The git push command is used to upload local repository contents and commits to a remote repository in GitHub.com. Pushing is how you transfer commits from your local repository to a remote repo. Click here to watch a video on pushing commits to a remote repository 



###  What is Git Pull? 
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content
Click here to watch a video on pulling commits from a remote repository 



####  Step 2.1: Create a GitHub Account

Go to GitHub.com and create an account! During the account setup, it will ask you for an email address. This needs to be a real email, and will be used by default to identify your contributions. 



###  Git Bascis

In this lesson, we’ll cover common Git commands used to manage your projects and to upload your work onto GitHub. We refer to these commands as the basic Git workflow. When you’re using Git, these are the commands that you’ll use 70-80% of the time. So if you can get these down, you’ll be more than halfway done mastering Git!


###  Lesson Overview

This section contains a general overview of topics that you will learn in this lesson.

####    How to create a repository on GitHub.
####    How to get files to and from GitHub.
####    How to take “snapshots” of your code.

### Create the Repository :

You should have already created a GitHub account in the Setting Up Git lesson above. 

Go  to GitHub.com and sign in with your email  and password 

Now it’s time to   Create a new repository by clicking the button shown in the screenshot below.


![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/1.jpg?raw=true)


Give your repository the name “git_test” in the repository name input field. Check “Add a README file”. And then create the repository by clicking the green “Create repository” button at the bottom of the page. See screenshot below 

![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/2.jpg?raw=true)

![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/3.jpg?raw=true)


This will redirect you to your new repository on GitHub. 

[Learn how to Connect your GitHub.com account to replit.com](https://www.dailymotion.com/video/k5R9lgZyJsr3ukyVecV)


Next, we shall import the "test" repository we create in the previous section to our connected Replit account 

Sign into your GitHub.com account,  open the text repository and Click the menu bar at the top right corner to activate desktop mode 


![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/4.jpg?raw=true)


![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/5.jpg?raw=true)

To get ready to copy (clone) this repository onto your replit workspace, click the green “Code” button. Then select the HTTPS option, and copy the line below it. 

![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/6.jpg?raw=true)

![GitHub Email Settings](https://github.com/grassroot-software/grassroot_curriculum/blob/main/foundations/installations/setting_up_git/imgs/7.jpg?raw=true)



NOTE: You MUST click the HTTPS option to get the correct URL because you are using Git for replit Editor. 
See screenshot below


Now it’s time to clone your repository from GitHub onto your Replit Editor by pasting the URL you copied in the last step. 

Copy the URL and past it inside your Replit Editor. 

[Click here](https://www.dailymotion.com/video/k40AtFkHlmxbj5yVeeb) to Watch a video  instruction by our student kevin Botha from kenya


[Second video](https://www.dailymotion.com/video/k6GRZaELbTm8hNyVeeb) : import your git repository to replit workspace


[Commit your work from replit workspace to GitHub.com](https://www.dailymotion.com/video/kayhx0fMHITL24yVehb)




