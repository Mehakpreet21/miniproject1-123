# Step by Step Tutorial

### Forking
Forking allows the user to create a "forked" version of the orginal project. This forked repository makes sure the user can experiment without the risk of ruining the original project. The main difference with a fork is that there still remains a connection between the original repository and the forked copy. Therefore, it will always be monitored and compared with the original repository. Changes can be  made to the original repository using pull requests. Any collaborator can edit the code and send a pull request to the owner. If the owner approves, they can merge the changes to the original version.

**Steps to Fork:**
* In GitHub, navigate to repository that you want to fork
* click the green Fork button on the upper right corner
* GitHub will send you the newly forked repository
* you can now make changes and send pull requests to the owner

### Cloning
Cloning allows the user to create a "cloned" version of the original project. The cloned repository will be created and can be stored on your local computer. Therefore, others generally do not have access to the cloned repository stored on your computer. In addition, cloning does not allow the user to pull down changes from the original repository. When collaborating, a user must be specifically added as a collaborator in order to contribute to the original repository.

**Steps to Clone:**
* In GitHub, navigate to repository that you want to clone
* On the main project page, click the green "Clone or download" button
* While in "Clone with SSH", copy the url to your clipboard
* Navigate to your command promt and type "git clone <insert url>" and press enter
* enter the newly created repository by typing "cd <name of repository> and pressing enter
* you can now make changes to the respository by using git commands like add and commit
* once you push the changes to the original repository, the changes we be available GitHub

### Pull Request
A pull request can be made by anyone who has forked an orginal repository. Making this request informs the owner that there are potential changes. Once the owner recieves the request, they can review the changes and merge the code into the base branch.

**Steps to Create/Complete a Pull Request:**
* Navigate to the repository being used
* From the "Branch" button, select the branch with the new commits
* Click the "New Pull Request" button
* Select the base branch and the compare branch. Usually, base branch is "master" and compare branch is the branch with new changes
* Enter a title and description for the pull request
* Click "Create Pull Request" if the request is ready to be reviewed or click "Create Draft Pull Request" if the request is not ready to be reviewed
* Pull request is created and the owner should be notified

### Adding a Collaborator to a GitHub Repo
Adding collaborators to a repository allows teamwork can be very useful for group projects.

**Steps to Add a Collaborator to a GitHub Repo**
* Navigate to the respository beign used
* Click the "Settings" button on the right
* From the left sidebar, click "Collaborators"
* Provide login, in necessary
* Enter the collaborator's username and select from the the dropdown menu
* Click "Add Collaborator"
* The selected user has been added as a collaborator and will be notified of their access to the repository.
