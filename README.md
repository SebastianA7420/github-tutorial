# GitHub Tutorial

_by Sebastian Andrade_

---
## Git vs. GitHub

**What is _Git_?** 

    Git is a workspace that allows user to create projects with commands on a command line.
    
**What is _GitHub_?**

    GitHub is a remote based workspace that allows users to manage and view changes to projects
    that have been created with Git. It stores projects that have been created by the user or by
    other sources.

**How are _Git_ and _GitHub_ similar?**

    Git and Github are both workspaces that can run projects created with code.
    Git is able to run without Github but Github is unable to run without Git.

---
## Initial Setup

**How do we make a GitHub account?**
* Go to **[Github](https://Github.com)**
* Create a username and add your email or make an [email](https://accounts.google.com/SignUp?hl=en) then comeback.
* Make a secure password for your GitHub account.
* click "Sign up for Github"
 
 _Congrats! You now have a Github account where you can store your Git projects._

**How do we make a C9.io account?**

* Go to **[c9.io](https://c9.io)**
* Easily sign up for c9.io using your Github account.

 _Congrats! You now have a c9.io account where you can store your created projects._



**How do we add an SSH key to our Github account?**

You're probably wondering what an SSH key is. An SSH key allows us users to push our projects
safe to Github. Since we're mostly working with **_C9.io_** we will be using an SSH key from **_c9.io_** to put in our Github account. **Make sure not to share your SSH key with anyone! Keep it private!**

To get the **SSH** key from your C9.io account:
* Go to [c9.io](https://c9.io)
* Sign in
* Click on **Dashboard**
* Click on the gear icon (settings) on the top right of the screen.
* Click on _**SSH Key**_ in the list of options on the left side of your screen. 
* Copy the second **SSH Key** below _"Connect to your private git repository"_.

To add the **_SSH_** key to your GitHub:
* Sign into your Github account
* Once on the main page, click on your icon on the top right of your screen.
* Click on _Your profile_ and once on the Your profile menu, click on _Edit profile_.
* After clicking on Edit profile you should be led to a list of options under personal settings.
* Click on _SSH and GPG keys_ 
* Paste your _SSH key_ that you copied from **c9.io** below the **key** label, and title it what you wish.
* Click **_Add SSH Key_**.

 _Congrats! Your C9 account is now connected to your Github account._
 
---
## Repository Setup

**What is "Git Init?**"  
Git init allows users to 

---
## Workflow & Commands

### What does ___ do?  
**Git status** - Allows users to view the current state of their file. Wether it has been pushed or not.  
**Git Add** - Allows users to Add their work to the "stage". Stage is being used here as an example, because when you _Add_ you are basically preparing your file to be commited.  
**Git commit** - Allows you to finally save your work after it was added.  
**Git Push** - Allows users to send their work to their chosen repository.  

---
## Rolling Back Changes  
Sometimes users mistakenly Add, Commit, or Push. These simple commands can help you with those mistakes...  

**git checkout - filename** - helps undo when users edit.  
**git reset HEAD filename** - helps remove what you've added.  
**git reset --soft HEAD~1** - helps remove what's been commited.
