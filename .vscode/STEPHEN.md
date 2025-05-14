# Day 1 & 2 Learnings - Git & Github Basics

## Day 1: Git and Github Basics

### What I Learnt:

- **Git Initialization**:
  Learned how to initialize a git repository by using `git init` in the terminal.

- **Making Commits**:
  Used `git add .` and `git commit -m "your message"` to stage and commit changes.

- **Pushing to Github**:
  Connected local repos to Github using `git remote add origin <url>` and pushed using `git push -u origin (branch name)`.

- **Branching**:
  Also Learned how to create and switch between branches using:
  `git checkout -b "branch-name"`: to create a new branch.

  `git push --set-upstream origin branch-name`: to set the branch you created as an upstream, so it would be registered in the repository and you can push to it.
  
  `git checkout branch-name`: to switch between branches.

- **To Create a New Repository**
  git init
  git add .
  git commit -m "your message"
  git branch -M main
  git remote add origin <repo-url>
  git push -u origin main

#### Day 2: Git Collaboration

##### What I Learnt:

- **Pull Requests (PRs)**:
  Learned how to collaborate on github using pull requests to suggest that changes has been made to the repository and request reviews before merging is made.

- **Conflicts**:
  Learnt that conflicts can happen when there is a code clash and then you can resolve the conflict by accepting only one changes and stashing the other. You can get this conflicts when you pull from another branch to your branch and as a team lead who reviews pull requests before merging you could get conflicts when trying to merge

- **Git Flow**:
  main-branch: `Production-ready code.`
  dev-branch: `Active development happens here.`
  Merge codes to dev branch first then merge to main when ready for release.

- **Git Collaboration Flow**:
  git clone <repo-url>
  npm install
  git checkout -b "to your own branch"
  **then you can start working**
  **After working**
  git add .
  git commit -m "your message"
  git pull origin dev: to pull new changes
  git push -u origin "your own branch"
  **After Pushing, you go ahead to create a pull request**

  - **Best Practices Learned**
    Commit often with meaningful messages.
    Always pull the latest changes before pushing.
    Open a Pull Request for every major feature or fix.
    Collaborate via code reviews and PR comments.


###### This is all i learnt and understand, Thank you.
