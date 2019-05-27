---
layout: post
title:  "Learning Git Basics"
date:   2019-05-27
desc: "A beginners guide to use the git and get associated with github"
keywords: "anaconda,python,python3,pydev,Machine Learning,Opencv,OpenCV"
categories: [Tech]
tags: [DeepLearning,Python,Machine Learning,Opencv]
icon-family: fab
icon: fa-github
icon-colour: black
author: "Shashwat Hiregoudar"
---
# What is it?

It is a distributed version-control system for tracking changes in source code during software development.
Sounds complex?? Read further you will understand

# Why use git?
Suppose you are building a software written code and it works upto a certain level. Now when you want to add another module or done some changes which led to the whole app not working. And ctrl Z cant help much,ever came across this situation?
At times like these version control systems specially git comes in handy.
After we are sure that till this point the software is working fine, we create a commit. So that in future if we mess up the flow we can always rollback to this point in code and resume.

Now imagine there are more than 1 person who is developing the code for the software / application. You assign some module to a person / group. How to keep track of who did what. And what-if someone messed up somewhere which led to the whole software to fail,
Here also we need git.


# Then what is GitHub?
Github is a free file hosting service where we can upload the source code and access it from anywhere. Just like google drive or any online file storage service. And is built specially keeping git in mind.

# So Lets start
[windows] - download and install git from here(https://git-scm.com/downloads )

[linux] - sudo apt install git

Usually whenever we create a project it usually involves creating a folder and sometimes work-space. 
1. Create a folder
2. open the command prompt or terminal in that directory and press ` git init`
3. now place some code or open a project
4. after making all the changes on files, type `git add * `
5. now make a commit with some message ; type `git commit -m "commit message you wanna write" `

There it is. We have create our git repository. But this is only local. If we wan to back it up in cloud Ex GitHub, then first we need to have a GitHub account.
Go ahead and create an account if you havent already. Don't worry its free of cost; and use some sensible username and password.

6. and create a repository  with the same name as the folder in which the project or software is.(Below two instructions will be available in the webbrowser just copy paaste in command line)
7. git remote add origin https://github.com/[username]/[repository_name].git
8. git push -u origin master

Now, Reload the webpage.
Congratulations you have created a repository successfully and uploaded it to github

# Where does it store ?
Whenever you browse the structure of a git repository, there is a folder named as .git ( because of the . in the front of the folder name it may be invisible to some file browsers )

## Next part comming soon.✌