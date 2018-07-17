# Build Your First Website

Step-by-step directions for how to make your own website(s) and host it for free on Github!
Originally designed as an exercise for the [CS4CS K12 STEM Program, NYU](http://engineering.nyu.edu/k12stem/cs4cs/). 

Where indicated below, replace [anything within brackets] with your own input. 

## Introduction: 

What is a [Website](https://en.wikipedia.org/wiki/Website)? 

- A website is a location connected to the Internet that maintains one or more pages on the World Wide Web. 
- A website can be accessed via a web address aka [URL](https://en.wikipedia.org/wiki/URL)

What is [Github](https://en.wikipedia.org/wiki/GitHub)? 

- Github Inc. is a private company that offers a web-based hosting service for mostly computer code. 
- Github Inc uses Git (a version control system) for tracking changes to files and coordinating work among multiple people/contributors. 
- Github also allows you to host one site per account
  1) One site per account (msyinmei.github.io)
  2) Unlimited project sites (msyinmei.github.io/buildyourownwebsite)
- Github offers you freebies if you are a student! (https://education.github.com/pack)

## Goals Checklist:

In this exercise you should will:

- [ ] [Create a Github Account](#1-create-a-github-account)
- [ ] [Build a Personal Website](#2-build-a-personal-website)
  - [ ] [Make your first repository for your user site](#step-one-create-your-first-repository)
  - [ ] [Make your first commit](#step-two-make-your-first-commit)
  - [ ] [Build a starter user site](#step-three-build-your-user-site)
  - Example: msyinmei.github.io
- [ ] Use some basic HTML, CSS and JS tools:
  - [ ] HTML templates
  - [ ] CSS basics
  - [ ] Learn [Markdown](https://daringfireball.net/projects/markdown/basics) (for your README.md)
  - [ ] CSS toolkits: [Bootstrap](https://getbootstrap.com/), [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)...

For those of you who have finished this first step, here is an extra challenge:

- [ ] Make another repository for your first project
  - [ ] Make your first commit
  - [ ] Build a site for your first project 
  - Example: msyinmei.github.io/buildyourownwebsite


# 1. Create a Github Account
Get a Github Account
1. Pick a username (use your name or pick an alias!)
2. Go to https://github.com/ and create an account with your username, email and password
3. Login!
4. Sign up for the GitHub Student Pack for unlimited private repositories! https://education.github.com/pack 

(Advanced) If you are using your personal computer: [Generate an SSH key for your Github Account](https://help.github.com/articles/connecting-to-github-with-ssh/)

# 2. Build a Personal Website
This is your personal website at <your_username>.github.io

### Step One: Create Your First Repository
1. On the homepage of Github, click "new repository"
2. Create this new repository by using "<your_username>.github.io" as the name of your repository. My username is msyinmei so I named my user site repository "msyinmei.github.io"
3. Decide if you are creating a *public* or a *private* repository
4. Select " Initialize this repository with a README "
5. Click " Create Repository "

### Step Two: Make Your First Commit
1. You can follow the directions on the official Github page on [how to make your first commit](https://help.github.com/articles/create-a-repo/#commit-your-first-change). 

OR

1. Go to the repo that you built
2. Click on " *Clone or Download* "
3. Select "Use HTTPS"
4. Copy the text to the clipboard by using the clipboard icon.
5. In your terminal, navigate to "Documents" directory. 
6. Type the command `ls` to check what files you have in your Documents directory.
7. Type in the command `git clone ` and paste the text you clipped earlier. 
You should have:`git clone https://github.com/<your_username>/<your_username>.github.io.git` by replacing <your_username> with your own username. 
8. Type the command `ls` again in your terminal, and you should have cloned your own directory! 
9. Change directories into the  "<your_username>.github.io" directory with the command `cd <your_username>.github.io` 
10. Make a file called index.html with the command `touch index.html`
11. In this file, type `<h1>Hello World <h1>`
12. Save the file, then back in your terminal type the following: (https://try.github.io/)
  
  ```sh
  git status
  git add .
  git commit -m"this is my first commit" 
  git push origin master
  ```
13. When prompted for your password, type it in.
Now, open up your website to "<your_username>.github.io" 
Congratulations! You have a website!

### Step Three: Build Your User Site
1. Enforce HTTPS for your Github Page: https://help.github.com/articles/securing-your-github-pages-site-with-https/
2. Choose one of the following templates for your website to use in your index.html file: 
https://www.w3schools.com/bootstrap/bootstrap_templates.asp 
3. Learn more about HTML, CSS: 
  https://www.w3schools.com/html/html_css.asp 
  https://www.codecademy.com/learn/learn-html
4. Learn more about Bootstrap: https://getbootstrap.com/
5. Learn about Flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/ 
6. Add an image file to your website. 

# 3. Build a Project Website
(aka username.github.io/myfirstproject)
1. Make your project repository
2. Follow steps in https://pages.github.com/ 
