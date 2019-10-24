## What is GitFlow?
It's a branching model for Git. It acts as a wrapper around Git. It's an extension of the default git init cmman and doesnt change anyhting in your repository other than creating branches for you.
### **GitFlow Workflow**
GitFlow is an abstract idea of Git workflow. It uses two branches to record the history of the project
instead of just one. The master and Develop branch.
1. Master Branch:
Stores the official release history of the project
2. Develop Branch:
Serves as an integration branch for features.
	* The “release branch” is made off of develop.

**Steps on how to use GitFlow Workflow**
* The first step is to complement the default master with a develop branch by creating an empty develop branch locally and push it to the server.
* This Branch will contain the complete history of the project and other developers can clone the central repository to go ahead an dcommit text into it.
        a. Any new developments are built through the "feature" branch. Any additions or new input is a
ccepted to be termed as a "feature".
        b. Any form of a fix or change of the input already in the repository is termed as a "Fix".
**The only commits to master branch are the merges from release branches and fix branches.**

### Some terms you need to know to understand GitFlow
1. Repositiory: 
This is, in simple terms, a file wherein all the ocntent of the project files is kept. It's best termed as the project's folder.
expample: miniproject1-123 (the current repository for miniproject1)
2. Clone:
As the name suggests, cloning literally means getting a copy of something. In github the clone command copies the source code of the repository from the source control. 
example (step wise): 
a. use the "clone or download" tab to open the link to the source code of the repository and copy the link. 
b. use this link to clone the repository through GitBash.
(using git clone git@example.git)
3. Fork:
A fork is a copy of a repository. Forking a repository lets you freely experiment without affecting the original project.
4. Branch:
A branch acts as a lightweight moveable pointer to any commits made. It literally is a branch out of te
 main trunk in the repository.
example: master and develop branch.
5. Commit:
It acts as an individual change to a file. To commit means to make whatever changes you made in your cloned repository, permanent.
example: commiting every definition to GitHub through GitBash
6. Merge:
Merge comman is one that we use in order to literally merge different branches to make one single branch. It is similar to compiling different parts of a project.
7. Checkout:
It’s the command that lets you easily navigate between different branches in your repository. It also updates the working directory’s files to match the version that’s stored in the branch that’s been navigated to.
8. Push:
It’s used to upload local repository content to a remote repository. It’s how you transfer commits from your local repository to a remote one. Pushing exports commits to remote branches unlike fetching, which imports commits to local branches.
Example: the action of pushing every commit made in the current project.

9. Pull
This is used to update the local version of a repository from a remote. It acts like a refresh command wherein changes made by any other users on the local repository can be updated on your remote repository.

