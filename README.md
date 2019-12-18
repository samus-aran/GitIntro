# GIT Demo

So you want to learn about GIT? A great place to start is:
* [Learn Git Branching](https://learngitbranching.js.org/)
* [GitLab basics guide](https://docs.gitlab.com/ee/gitlab-basics/README.html)

## Outcome
By the end of this tutorial you will have:
* Forked a codebase
* Created a branch
* Edited the README
* Created a PR
* Learned some git


## First Steps
In order to follow this tutorial you will need access to the following:
* GIT on your machince, this can be done by following the steps on how to [install GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
* A Github account, if you don't have one you can create one [here](https://github.com/join)

## Oh Forks
A fork is a copy of a repository that you manage. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

This repo acts as the original repository, which everyone will not have write access to. So to get around this we will fork the repo, make the changes, create a PR and see our changes once the PR has been approved.

## Forking 
On the GitHub web interface, click Fork on the top right hand corner: this will make a copy of the repo to your GitHub account. Then we will clone your forked repo onto your own machine by using git via command line or another Git tool.

To then clone on command line:

```bash
git clone https://github.com/fieheath/GitIntro.git
```

Make sure to ensure that the /username/ is in fact your own username! Aka change it from /fieheath/

## Create a Branch

Follow the instructions on how to [create a branch](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-and-deleting-branches-within-your-repository). This can be done on Github Web Interface, Name the branch after your username, mine would be fieheath_branch.

Alternatively, this can be done on the command line:

```bash
git checkout -b [name_of_your_new_branch]
```

## Edit this ReadMe
Edit this ReadMe by adding your name at the section in the bottom. 

## Add and Commit
You will want to add your changed files and the index to the repository, this is done via add.

```bash
git add .
```

Commit your change, make sure to add a useful message. Ensuring you are using your own branch!

```bash
git commit -m "Add your useful message here"
```

## Push

Once you have commit your changes on your local repo you will want to make sure it is on the repository, we do this by pushing.

```bash
git push
```

## Create a PR

Create a PR (pull-request) or MR (merge request). Follow the instructions on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

## Merge

Once your merge request has been approved, [merge your changes](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/merging-a-pull-request). You will then see the update on the original repo! (Note pull requests have a 24-48 hour period until they will be reviewed!)

## Add Your Name Here
* Fiona Heath
* Ashley Nicolson
