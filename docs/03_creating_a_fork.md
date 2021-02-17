# Forking a Repo/Project

## GitHub
A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.
Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

### Forking Steps
1. find the repository you’re contributing to and press the Fork button in the upper left. 
 - This will create an exact copy of the repository (and all of its branches) under your own username.


## Cloning 
Cloning a GitHub repository creates a local copy of the remote repo. This allows you to make all of your edits locally rather than directly in the source files of the origin repo.

### Cloning your new fork
GitHub will automatically redirect you to the forked repository under your username. This is the repository you need to clone to your local development environment, not the original. 

1. Grab the URL GitHub provides under the green **Clone or Download** button and plug it into the command below.

```git clone git@github.com: add link```

2. Once you’ve forked a repository, changes to the original (or “upstream”) repository are not pushed to your fork. We need to tell the new repository to follow changes made upstream to keep it fresh via [remotes](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes).

3. Switch directories to the forked repository you just cloned and run the following commands. Replace the last part of the first line with the original repository clone URL. This links the fork back to the original repository as a remote, which we’ll name ```upstream```, and then fetch it.


 ```git remote add --track master upstream git@github.com:facebook/react-native.git```
 
 ```git fetch upstream```
