# LINUX

- To use this command in the whole file use:%s/searchword/replaceword/gc

Search in Vim Editor
- To search the word After the cursor uses the backslash key and then write the word and press enter. : /word
- Use n to move on next matching word. : n
- Use N to move on previous matching word : N

### Search and Replace in Vim Editor
- To replace the word in file use s/ command in vim like :s/searchword/replaceword/
- To do replace all occurrence of word use g :s/searchword/replaceword/g
- This command will replace the word globally.
- To confirm before replacements of words use gc. : s/searchword/replaceword/gc% before the command.

# SCM

### What is SCM and its Importance

- DevOps is a collection of processes that shorten the time between committing a system change and putting it into normal production while still maintaining high quality. SCM (Source Code Management) is indispensable in this ecosystem, acting as the backbone for managing changes and ensuring high-quality software production. Let's explore its critical role in DevOps:

- Facilitating Rapid, Reliable Changes: DevOps emphasizes rapid delivery of high-quality software. SCM plays a pivotal role by managing source code changes, making sure they are consistent, traceable, and reversible if needed. This cagability is essential in reducing the time from code commitment to production deployment.

- Central to Developer Workflow: SCM is not just a tool; it's an integral part of the daily workflow for software developers. It provides a structured, collaborative environment where code changes are efficiently managed, reviewed and integrated. This orderly management is essential in a DevOps culture that values rapid iteration and frequent releases.


### Distributed vs Non-Distributed VCS

- The Version Control System (VCS) presents a core component from the DevOps cycle. Tracking anything from application codes, infrastructure, policies, and what not is part of the best practices such as laC (infrastructure as code) and GitOps. Simply put, treat everything (if possible) as code. Therefore, introducing many upsides including: having a clean change history, immutable deployments, implementing familiar development workflows on the Ops side of the story.
- Now, you can't think of VCS without Git. Though Git is a distributed VCS, on the quite opposite side you have a centralized VCS. So, what's the catch ?!
- The main difference is: centralized VCS stores the code on a central remote serves only, where in a distributed VCS the code can be stored (cloned) on a local workstation as well.

### distributed

- Every developer holds a local copy of the remote repository including the metadata.

### Working Model of GIT(Local Workspace/Remote Repo)

- Git uses a three-stage architecture - working directory, staging area, and local repository to optimize change tracking.
- Key concepts like committing, branching, merging, and remotes enable powerful version control workflows.
- Git maintains an extensive history and provides commands like git log and git diff to analyze changes over time.

### Git Architecture & Components
- While many version control systems use a two-tier architecture consisting of a repository and a working copy, Git distinguishes itself with a three-stage model optimized for tracking changes: the working directory, staging area, and local repository. Additionally, Git includes the concept of remote repositories for collaboration.
- The open-source Git project offers a wide variety of commands to make teamwork easier.

### Here are some of the most commonly used commands.
- git init: Initialize a new Git repository.
- git clone [url]: Clone an existing repository.
- git add [file]: Add a file to the index.
- git commit: Validate changes made.
- git commit -m "message": Validate changes with a message.
- git status: View the status of files in the working directory.
- git push: Send changes to remote repository.
- git pull: Fetch changes from the remote repository and merge them with the local repository.


## Commands
- $ git config --global user.name "ShagufthaNikhar"
- $ git config --global user.name "shagufthanikhar@gmail.com"
- $ git config --list


