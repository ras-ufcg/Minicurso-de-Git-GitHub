# Quiz Git

## Nível 1
#### Q1. How can you check your current git version?

- [ ] git --v
- [x] git --version
- [ ] git --option
- [ ] git --current

#### Q6. What will the following command print to the Terminal?

```git remote -v```

- [x] A list of remote repositories and their URLs
- [ ] The current git version you're running
- [ ] An inline editor for modifying remote repositories
- [ ] The last 5 git versions you've installed

#### Q12. What option can you use to apply git configurations across your entire git environment?

- [ ] --all
- [ ] --master
- [x] --global
- [ ] --update

#### Q14. If you cloned an existing git repository, what would happen?

- [ ] A new copy would overwrite the central repository
- [x] A copy of the repository would be created on your local machine
- [ ] Nothing, cloning is not a supported git function
- [ ] A copy of the repository would be created on the hosting platform


#### Q19. Where are files stored before they are committed to the local repository?

- [ ] Saved files
- [ ] git documents
- [x] Staging area
- [ ] git cache

#### Q27. After pushing commits to the remote repository for the first time using the command below, what shorthand command can you use in future?

bash
git push -u origin master


- [ ] git push master
- [ ] git push origin
- [ ] Same as before, git push -u origin master
- [x] git push
#### Q29. What is the status of the beta-notes.js file in the following output?

```shell
Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git checkout -- <file>..." to discard changes in working directory)

modified: beta-notes.js
```


- [ ] beta-notes.js is untracked and has been modified.
- [x] beta-notes.js is a tracked file and has been modified, but has not been added to the current commit.
- [ ] beta-notes.js is untracked but has been added to the current commit.
- [ ] beta-notes.js is tracked, and the modified file has been added to the current commit.

#### Q35. What command would you use to create a new git repository?

- [ ] git add
- [ ] git start
- [ ] git new
- [x] git init

#### Q44. Which Git command begins tracking of a new file?

- [x] add
- [ ] addfile
- [ ] begin
- [ ] track
#### Q46. Which key press returns a set of suggestions to pick from, when writing a Git command?

- [ ] Control
- [ ] Shift
- [x] Tab
- [ ] Alt

#### Q47. Which of these terms best describes Git?

- [x] Distributed Version Control System
- [ ] Issue Tracking System
- [ ] Integrated Development Environment
- [ ] Web-Based Repository Hosting Service

#### Q48. Which command gets a copy of an existing Git repository?

- [ ] duplicate
- [ ] replicate
- [ ] copy
- [x] clone

#### Q54. What Language is used in GIT?

- [x] C
- [ ] C++
- [ ] C#
- [ ] Java

#### Q57. How many individual commits can a single repository have?

- [x] any number of commits
- [ ] only one commit local per repository
- [ ] only three commits per branch
- [ ] only one commit per HEAD

#### Q65. You want to perform a git reset but cannot recall all of the available options. What command would you use to see a description of them?

- [x] git help reset
- [ ] git -h reset
- [ ] git options reset
- [ ] git reset help

#### Q66. What is a remote repository?
- [ ] a version of the repository that mirrors changes made in the local repository's master branch for open-source collaboration efforts
- [ ] the lead repository elected by the Git arbitrator found within local repositories of collaborating team members
- [ ] a read-only version of the repository stored on a backup server in case local repositories become lost or corrupted
- [x] a version of the repository hosted on the internet or network that is pushed to or pulled from by collaborators

#### Q72. What Git workflow is used by teams that collaborate on a single branch and avoid creating long-lived development branches?

- [ ] Git flow
- [ ] Mainline flow
- [x] Trunk-Based Development
- [ ] GitHub flow

#### Q77. What is the difference between Git and SVN?

- [ ] Git works only on Linux, while SVN works on all operating systems.
- [ ] SVN works only on Linux, while Git works on all operating systems.
- [x] SVN is a centralized system, while Git is a distributed system.
- [ ] Git a centralized system, while SVN is a distributed system.

#### Q82. What is version control?

- [ ] a type of architecture used to manage large databases
- [x] a system that shows, tracks, and controls changes to a set of files over time
- [ ] a programmatic design pattern used to manage code between multiple engineering teams
- [ ] a type of software that links a project with a GitHub repository

#### Q91. What command displays the difference between the working tree and the stage/index area, as well as files not tracked by Git?

- [ ] git current
- [x] git status
- [ ] git local
- [ ] git context

#### Q67. After modifying some existing files in a repository, you decide to discard the changes. What command can you use?

- [ ] git restore
- [ ] git undo
- [ ] git clean
- [x] git checkout

#### Q64. How does Git internally manage branches?

- [x] by creating a pointer to the most recent snapshot/commit for the branch.
- [ ] by creating a data array of branches in the same repository.
- [ ] by creating a data dictionary of code changes.
- [ ] be creating a debug log that stores repository changes.

#### Q62. After mistakenly staging a file named myFile to the index, how would you remove it from the index to exclude it from your next commit?

- [ ] Use git reset HEAD^.
- [x] Use git reset myFile.txt.
- [ ] Use git -rm myFile.txt.
- [ ] Use git reset.

## Nível 2
#### Q2. What command lets you create a connection between a local and remote repository?

- [x] git remote add new
- [x] git remote add origin
- [ ] git remote new origin
- [ ] git remote origin


#### Q16. What files is this .gitignore programmed to leave out?

```shell
#.swift
build/

*.txt
*.metadata
```


- [ ] All files with a .swift, .txt, or metadata file extension, as well as the entire build directory
- [ ] Only the build directory
- [x] All files in the build directory, as well as files ending with .txt or .metadata
- [ ] Only files with .swift and .txt extensions.

#### Q17. After you make changes to a local repository, you run the following command. What will this do?

git commit -a -m "Refactor code base"

- [ ] Nothing, you can't use multiple options in the same command
- [ ] Adds all new files to the staging area
- [ ] Commits all new files with a message
- [x] Adds all modified files to the staging area, then commits them with a message
#### Q21. Which statement is true when you use the git add -A command?

- [ ] Only new files in the working directory are staged to the index.
- [x] All new and updated files from the working directory are staged to the index.
- [ ] All files in the working directory are staged to the index in alphabetical order.
- [ ] Only updated files in the working directory are staged to the index.

#### Q30. What command would let you modify your previous commit?

- [ ] --fix
- [ ] --quickfix
- [ ] --modify
- [x] --amend
#### Q31. What is the best way to characterize the git commit structure?

- [ ] Data array
- [x] Data log
- [ ] Data snapshot
- [ ] Data dictionary

#### Q32. What change will the following command make to the staging area files?

```git rm --cached testfile.js```

- [x] testfile.js will be removed from the staging area and its changes no longer tracked.
- [ ] testfile.js will be removed from the staging area but its changes will still be tracked.
- [ ] A copy of testfile.js will be cached on your desktop.
- [ ] The current copy of testfile.js will be saved in the staging area.

#### Q38. What does commit object contain?

- [ ] A set of files, representing the state of a project at a given point of time.
- [ ] Reference to parent commit objects.
- [x] An SHA1 name, a 40-character string that uniquely identifies the commit object.

#### Q40. How many ways are present in Git to integrate changes from one branch into another?

- [ ] 3
- [ ] 5
- [x] 2
- [ ] 4
#### Q49. How does Git think of its data?

- [ ] File
- [ ] None of these
- [x] Snapshot
- [ ] Folder

#### Q53. What does refs store?

- [x] SHA-1 value
- [ ] None of these
- [ ] Branch name
- [ ] Project name

#### Q79. What is the difference between a soft reset (git reset --soft) and a hard reset (git reset –hard) ?

- [x] A soft reset only changes the commit that HEAD points to, while a hard reset resets the index and working tree to match the specified commit, discarding any changes.
- [ ] A soft reset caches the old HEAD pointer, while a hard reset deletes it entirely.
- [ ] A hard reset changes only where the HEAD is pointing, while a soft reset changes the HEAD and index.
- [ ] A hard reset caches the old HEAD pointer, while a soft reset deletes it entirely.

#### Q84. Which command can be used to list the branches that have been merged into the currently checked-out branch?

- [ ] git master --status
- [ ] git branch --status
- [x] git branch --merged
- [ ] git status --merged

#### Q96. Which statement is true of the git push command?

- [x] By default, a push doesn't send tags to the remote repository.
- [ ] Only annotated tags are automatically pushed to the remote repository with a commit.
- [ ] Tags are pushed to the remote repository with their respective commits.
- [ ] Commits can be tagged only when they are created.

#### Q102. After checking your Git status, you get the following output, which shows the file beta-notes.js in the commit but also unstaged. How can this situation occur?

```bash
Changes to be committed:
 (use "git reset HEAD <file>..." to unstage)

  modified: beta-notes.js

Changes not staged for commit:
 (use "git add <file>..." to update what will be committed)
 (use "git checkout -- <file>..." to discard changes in working directory)

  modified: beta-notes.js
```

- [ ] There were two copies of beta-notes.js but one was deleted.
- [ ] There are two tracked copies of beta-notes.js but one was removed from the commit.
- [ ] Two copies of beta-notes.js were created, but only one is being tracked.
- [x] beta-notes.js was staged, then modified afterwards, creating two different versions of the file.

#### Q63. What happens if you run this command from your master branch?

```bash
git checkout -b beta-test
```


- [ ] The beta-test branch will be checked out of the current commit.
- [ ] The beta-test branch will be checked out and deleted.
- [x] A new branch called beta-test will be created and switched to.
- [ ] The beta-test branch will be merged with the master branch.

## Nível 3

#### Q70. Which command correctly creates a lightweight tag?

- [x] git tag v3.8.1
- [ ] git tag --light "v3.8.1"
- [ ] git tag v3.8.1 —-annotate -m "<tagMessage>"
- [ ] git tag -l v3.8.1

#### Q71. What is the main issue with using git rebase when working with multiple developers?

- [ ] Rebase affects only your repository and creates a diff in the master branch.
- [ ] Rebase creates a temporary copy of the master branch in the remote repo.
- [ ] Rebase moves the HEAD of the remote master branch one commit forward.
- [x] Rebase deletes all commit history for the new feature branch.

#### Q76. How does this command alter the currently checked-out branch?

```git reset --soft HEAD^```

- [ ] It resets the working branch to the first commit.
- [x] It sets HEAD to previous commit and leaves changes from the undone commit in the stage/index.
- [ ] It deletes all previous commits and resets the repository history back to its initial state.
- [ ] It keeps the HEAD at the current commit, but clears all previous commits.

#### Q78. This command is an example of what kind of tag?

```git tag -a v1.4 -m "ABCD v1.5"```

- [ ] verbose
- [x] annotated
- [ ] lightweight
- [ ] deferred

#### Q97. How would you delete a remote branch in your repository?

- [ ] Use git --delete <branch_name>.
- [ ] Use git push <remote_name> --d <branch_name>.
- [ ] Use git push <remote_name> --D.
- [x] Use git push <remote_name> --delete <branch_name>.

#### Q99. How does the -p option change the behavior of the git add command

- [ ] It causes tracked files in the parent directory to be included in the staged files.
- [x] It allows developers to interactively choose which changes to tracked files are staged and outputs the differences for review.
- [ ] It automatically pushes changes to the corresponding branch on the remote repository.
- [ ] It allows developers to interactively choose which files are committed and outputs the differences for review.

#### Q100. After checking out a specific commit, you receive a warning message indicating You are in 'detached HEAD' state. What is Git warning you of?

- [x] You are not working on the most recent commit of a branch.
- [ ] A teammate has flagged the code with an issue.
- [ ] The commit does not have a parent.
- [ ] The branch has not been pushed to the remote repository.

## Nível 4

#### Q69. If you have several commits for a single feature, what is the most efficient way to restructure your commit history?

- [ ] Use git stash to consolidate the commits under a new hash.
- [x] Use git squash to consolidate the commits together into a single coherent commit.
- [ ] Delete the task commits and recommit with a new message.
- [ ] Use git cherry-pick to place the commits in another branch.
#### Q9. You find a bug in your project, but can't locate where it was introduced in the commit history. How would you diagnose this problem?

- [ ] Manually backtrack through your commit history.
- [ ] Use git search -diff to compare all commits in your repository history.
- [ ] Run a git rebase to find the buggy commit.
- [x] Use git bisect to compare the buggy commit to an early commit that works as expected.

#### Q11. Why would you use a pre-receive hook in your remote repository?

- [ ] You wouldn't, you would use it in the local repository
- [x] To execute a script when a remote receives a push that is triggered before any refs are updated
- [ ] To fire a script after updates are made to the remote repository
- [ ] To debug all commit tags and release versions