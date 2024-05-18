# <p align="center">TENDELIC-POS-SYSTEM-PROJECT</p>

<p align="center"><a href="#"><img src="./public/assets/imgs/tendelic-logo-name.png" widht="400" height="200"></a></p>

[**Tendelic**](https://github.com/JianefrelDionaldo/Tendelic-POS-System-Project) provides a professional and reliable platform that streamlines the entire food services and management process for a restaurant that lead to customers satisfaction.

## Documentation

In this comprehensive project, we College Student at Bestlink College of the Philippines aim to develop an innovative solution that streamlines the entire food service and management process for restaurants, catering customers. Our system will revolutionize the way restaurant operate by integrating advanced features to enhance efficiency and customer satasfaction. We will include the whole documentation too ***soon***.

---

## Start & Installation Dependencies

```bash
# To get Start
npm init -y

# To install all Dependecies
npm i
# Or 
npm install
```

---

## **Clone** Remote Repo

Copy the link from the button that you'll find at the top.

![CODE](https://custom-icon-badges.demolab.com/badge/CODE-brightgreen.svg?logoColor=fff&logo=code)

```bash
# To get Clone
git clone https://github.com/JianefrelDionaldo/Tendelic-POS-System-Project.git
```

---

## Create new **Branch**

> ⚠️ **Warning:** Before writing code/feature, make sure you had seperated new branch to avoid conflict.

```bash
# To CHECK any existing branch
git branch

# To CREATE a new branch - [branchName] name it depends on what you prefer of
git branch -c myBranchName

# To check untrack files/folders in current branch
git status

# To ADD to stage the Untrack/Modified files
git add filename.ex
```

## Conventional Commit Message

```bash
# Good Conventional Commit Message
git commit -u "feat: improve performance with lazy load implementation for images"
```

> You can read more on [freecodecamp.org news](https://www.freecodecamp.org/news/) specifically on [How to Write Better Git Commit Messages – A Step-By-Step Guide](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/).

***The commit type can include the following:***

- **feat** – a new feature is introduced with the changes.
- **chore** –  changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies).
- **refactor** – refactored code that neither fixes a bug nor adds a feature.
- **docs** – updates to documentation such as a the README or other markdown files.
- **style** – changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
- **test** – including new or correcting previous tests.
- **perf** – performance improvements.
- **ci** – continuous integration related.
- **build** - changes that affect the build system or external dependecies.
- **revert** - reverst a previous commit.

## Commiting file/folder - Push to remote Repo

```bash
# You committed a new change in myBranchName
git commit -m "docs: Updated documentation on README.md file"

# Check branches [The Green highlighted, where you working at]
git branch

# Switches to the specified branch and updates the working directory E.g., git checkout [branch-name]
# Switch to brach main
# Your branch is UP TO DATE with 'origin/main'
git checkout main 

# Swtiched to branch 'myBranchName'
# Your branch is ahead of 'origin
git checkout myBranchName

# To push to the branch of the same name on the remote, use
git push origin head

```

---

## GIT PULL

**Git Pull** - It updates your current local working branch with all new commits from the corresponding remote branch on GitHub. `git pull` is a combination of `git fetch` and `git merge`.

> If you're working on a development team that's making lot of changes to your code base and constantly submitting pull requests. At the same point it'll be your interest to contribute and to make sure you have updated on their code. Here's `git pull` command request comes into the picture.

```bash
# You'll get the latest commit/push
git pull

# Create a new branch to implement your task
git checkout -b newFeatureBranch

# Check what branch you are in E.i., 'newFeatureBranch'
git branch
```

> Right after you finished the tasks, you'll need to execute the same procedure to add it into the remote GitHub Repository.

```bash
# To Add files/Dirctory
git add filename.ex
# Or
git add .
git add -A
git add --all

# Or

# To get staged and directly committed
git commit -a -m "feat: A new feature is introduced with the changes"

# Or just simply commit command like this
git commit -m "feat: a new feature is introduced with the changes"

# To push the new feature 
git push origin head
```

<!-- # Back to main branch
# git checkout main

# Switches to the specified branch and updates the working directory
# git checkout newFeatureBranch -->

> And there you go. Great job, your done!

---

## LICENSE

Starting at version 1.0.0 Tenedelic-POS-System-Project Licensed under the [MIT License (MIT)](https://github.com/JianefrelDionaldo/Tendelic-POS-System-Project/blob/main/LICENSE).
