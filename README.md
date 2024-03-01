# payas
repo
 git checkout master
2. Create a new branch named "feature-branch" and switch to it:
$ git checkout -b feature-branch
This command will create a new branch called "feature-branch" and switch to it.
3. Make your changes in the "feature-branch" by adding, modifying, or deleting files as
needed.
4. Stage and commit your changes in the "feature-branch":
$ git add .
$ git commit -m "Your commit message for feature-branch"
Replace "Your commit message for feature-branch" with a descriptive commit message for the
changes you made in the "feature-branch."
5. Switch back to the "master" branch:
$ git checkout master
6. Merge the "feature-branch" into the "master" branch:
$ git merge feature-branch
This command will incorporate the changes from the "feature-branch" into the "master" branc
