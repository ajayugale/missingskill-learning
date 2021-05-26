# GIT
---
### INTRODUCTION TO GIT
* Git is the free and open source distributed **version control system** that's responsible for everything GitHub related that happens locally on your computer.<br>
*  This report features the most important and commonly used Git commands for easy reference.<br>

#### What’s a version control system?
* A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. As the project evolves, teams can run tests, fix bugs, and contribute new code with the confidence that any version can be recovered at any time.<br> 
* **Developers can review project history to find out:**
  * Which changes were made?<br>
  * Who made the changes?<br>
  * When were the changes made?<br>
  * Why were changes needed?<br>

#### Why Git?
* According to the latest Stack Overflow developer survey, more than 70 percent of developers use Git, making it the most-used VCS in the world. Git is commonly used for both open source and commercial software development, with significant benefits for individuals, teams and businesses.

---
### GIT Workflow
The GitHub flow
The GitHub flow is a lightweight, branch-based workflow built around core Git commands used by teams around the globe—including ours.

The GitHub flow has six steps, each with distinct benefits when implemented:

1.**Create a branch:** Topic branches created from the canonical deployment branch (usually main) allow teams to contribute to many parallel efforts. Short-lived topic branches, in particular, keep teams focused and results in quick ships.<br>
2.**Add commits:** Snapshots of development efforts within a branch create safe, revertible points in the project’s history.<br>
3.**Open a pull request:** Pull requests publicize a project’s ongoing efforts and set the tone for a transparent development process.<br>
4.**Discuss and review code:** Teams participate in code reviews by commenting, testing, and reviewing open pull requests. Code review is at the core of an open and participatory culture.<br>
5.**Merge:** Upon clicking merge, GitHub automatically performs the equivalent of a local ‘git merge’ operation. GitHub also keeps the entire branch development history on the merged pull request.<br>
6.**Deploy:** Teams can choose the best release cycles or incorporate continuous integration tools and operate with the assurance that code on the deployment branch has gone through a robust workflow.<br>


---
## Basic Git commands
* To use Git, developers use specific commands to copy, create, change, and combine code. These commands can be executed directly from the command line or by using an application like GitHub Desktop or Git Kraken.<br> 
***** **Here are some common commands for using Git:**
* **git init:** initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.
* **git clone:** creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.
* **git add:** stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.
* **git commit:** saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.
* **git status:** shows the status of changes as untracked, modified, or staged.
* **git branch:** shows the branches being worked on locally.
* **git merge:** merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the main branch for deployment.
* **git pull:** updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.
* **git push:** updates the remote repository with any commits made locally to a branch.
