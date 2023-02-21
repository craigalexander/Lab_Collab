Lab 5 - Collaborative Coding
================

# Part 2 - Create a Pull Request to an existing project

This tutorial is about contributing to someone else’s project. The
sample project that we are going to contribute to can be found here:

(<https://github.com/craigalexander/Lab8Pt2>)

We are simply going to add a line to the existing `readme.md` file, but
you are going to apply an update to the repository and contribute and
submit to the project maintainer for approval.

In Git terms, what you need to do is:

1.  **Fork** the project on GitHub to your account
2.  **Clone** it to your local machine
3.  Make the change
4.  **Stage, commit** and **push** the change to GitHub
5.  Create a **Pull request** on the original project which points to
    your fork
6.  **Code review**: the project maintainer will review your change to
    decide if they want to integrate it, close it, or request
    modifications

*Aside - difference between Fork and Clone* - Forking is done on the
GitHub account while Cloning is done using Git. When you fork a
repository, you create a copy of the original repository but the
repository remains on your GitHub account. Whereas, when you clone a
repository, the repository is copied to your local machine with the help
of Git.

## Forking and Cloning

You can find instructions on how to fork and clone using the terminal in
the Using Git with R tutorial when using the terminal. If you wish to
use GitHub and GitHub desktop, follow the instructions below.

To fork the repository, visit the GitHub page of the repository and
click the Fork button on the top right. After this, you will have the
opportunity to give the forked repository a different name, description
and which branch to fork. Once done, you will have a copy of the project
under your name on GitHub.

Next, you can clone the project onto your local machine. You can either
do this on the terminal by obtaining the HTTPS or SSH key from GitHub,
or can clone using GitHub desktop.

## Making changes

Once you have cloned the repository, modify the `readme.md` file. Add
your own text to this file (feel free to be creative!)

## Stage, commit and push the change to our repository

Following this, you can commit and push your changes to the repository
using GitHub desktop. If you wish to use the terminal, you can use the
following commands

``` r
> git add readme.md
  git commit -m "added my updates to readme"
  git push
```

## Create a Pull Request

1.  Navigate to the original project repository
2.  Click on the Pull Requests tab
3.  Click on the green button with the label “New pull request”

Once on this section, click the “compare across forks” highlighted text

4.  Select your cloned repository from the “head” dropdown menu
5.  You will then see your commit message and the contents of your
    commit.

Now you can click the green button with the label “Create pull request”

Once clicked, you will have the opportunity to rename your Pull Request
and give it a description. When you’re ready, you can click the green
button with the label “Create pull request”.

Now we can see that the pull request has been created by returning to
the repository and looking at Pull requests (you will see a number
appear with the number of pull requests open).

Once your request has been sent, this will be reviewed. If accepted, you
will be notified that your Pull Request has been accepted and the update
has been applied to the repository.
