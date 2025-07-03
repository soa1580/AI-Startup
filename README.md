# - Clone the project to my laptop:
- Open the terminal on your computer and make sure you are in the folder where
you want to put the project.
- Then write the following command:
- git clone https://github.com/soa1580/AI-Startup/blob/main/README.md
- Create a personal branch to carry all your development work.
- git checkout -b branch_name
- git checkout -b soa1580/development
- The above command will create a branch called soa1580/development and
switch to it immediately.

- Write your code and make changes to the codebase.
- When you are done, add and commit your changes.
- git add . (To add all files, or you can selectively add files by specifying their
names.)
- git commit -m ‘useful commit message’
- Push the changes to your remote branch.
- git push origin name-of-your-branch e.g
- git push origin soa1580/development
- Back on Github website in your browser, a new pull request button will appear, click on it.
- You will be taken to where you will fill the pull request form.
- Edit the title of the pull request or leave it as it is.
- In the description of the pull request, describe the type of changes that will be
made in the code you are about to submit. You can optionally leave it blank.
- You can also choose to add snapshots if words can’t sufficiently describe the
changes made.

- When you are all done, click on the ‘create pull request’ button and you are all set, and
wait for your pull request to be merged into the main codebase.
- Do the following once you have gotten confirmation that your code changes have been
merged.
- Go back to your terminal and switch to the main branch.
- git checkout main
- Update your local version with the latest version that is on the github website:
- git pull origin main
- The changes on the remote branch will be added to your local branch and
everything is up to date.

- Now delete your personal branch you created in step 2:
- git branch -D branch_name
- git branch -D soa1580/development