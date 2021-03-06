# IS218-Mini-Project-1
##### Mini Project 1 by Adib Haque &amp; Marlon Sarkor

## How the usage of Git, Docker, automated testing, & continuous integration can improve the productivity & competitiveness of a company:
Benefits of GIT: Git allows companies to view the progress of development and truly understand the process of the development life cycle. It allows for a collaborative environment, which leads to increased productivity. Features such as branching, cloning, pulling and more allows for gathering and sharing information across all development. GIT also allows a company's developers to see how much time and effort their colleagues are putthing in through a feature such as commit. This increases the sense of urgency to produce more and also motivates developers. 

Benefits of Docker: Docker containers allow for VM-like productivity but more focused and precise. Dockers use a single application which truly uses system resources efficiently. Dockers are compartmentalized and also allow for more portable applications, more efficient software usage and more. It is also possible to use multiple containers on a single OS, taking full advantage of all system resources unlike a single Virtual Machine. Overall, Dockers make companies more efficient and able to fully utilize resources, therefore making them at times more precise and focused compared to their competitors. 

Benefits of automated testing: Automated testing enables a company to save time and use resources towards new projects innovation. It eliminates a great amount of manual work, making a company more efficient and productive. Autoamted testing creates consistency and lowers the chances of human error. It can also save money for the company, due to decreased human labor and overhead. An automated process is not only consistent, but accurate in most cases if done correctly. The usage of automated testing will help a company is many aspects related to competitiveness and productivity. 

Benefits of continuous integration: Continuous Integration helps companies and developers to produce reliable code. It also allows for peer review which can assist with discovering errors or bugs. Continuous Integration along with the features mentioned above can help with verifying the accuracy of code and other projects. This also helps the company grow through innovation and mostly helps with the quality assurance of a product. 

Overall, the combination of all of these features help create an environment where developers can create code with peers to assist the company in moving forward with new products in an elegant manner. These features create a collaborative playing field, which helps developers keep up to date with current development. The use of automated testing helps eliminate a great amount of issues that stem from Human error. Continuous integration allows companies and developers to produce efficient and reliable products. 

## GitFlow Workflow Explanation
GitFlow administers the types of braches to create and how to merge them. GitFlow also has a command-line tool called git-flow which can be used a multiple popular operating systems. Git-flow is a wrapper around the popular tool GIT. GitFlow shows the workflow of the Master and Develop branches. The different features of Git allow for collaborative projects and an idea of progress throughout the development life cycle. 
![github-large](https://i.stack.imgur.com/rE8jd.png)

Developers can use branches to indivually work on projects and commit changes when needed. This feature is very convenient becuase it does not effect the original code/project. 

See below for the steps in a GitFlow project:
- Create a develop branch from the master
- Create a release branch from develop (This is more so for software releases)
- Create feature branches from develop
- When a developer is done coding a feature, it is then merged to the develop branch
- When a developer is done with the release branch, it is merged into develop and master
- If there is an issue identified in master, a hotfix branch is created from master
- Once the developers complete the hotfix branch, it is merged into develop and master.

This process shows how GitFlow is a tree format and can easily be used to track progress. The steps above are an example of let's say a Microsoft Windows Update. If the update were to go live and then a security flaw is discovered, a hotfix would need to be implemented and pushed out. This is a perfect exmaple of how GitFlow can be used efficiently. 


## Git Commands/Terminology: Definition & Examples:
### Repository
##### Repositories are containers that contain refs which are point to objects or other refs. Like a folder with files, except this folder keeps track of all its files history. This is used anytime you utilize git. 
![github-large](https://media.geeksforgeeks.org/wp-content/uploads/20191121165133/repository1.jpg)

### Clone
##### A clone is a copy of a repository that is stored locally rather then on a web server. It can also be defined as the act of making a copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. Clones are still connected to the remote version. This allows users to push local changes to the remote to keep them in sync. This is used when you would like to work on git files in a prefered editor, or when you know you will be suffering from lapses of no internet. 
![github-large](https://www.w3docs.com/uploads/media/default/0001/03/3f26b30cc1dbda3424ceef3ab4977149906a0c58.png)

### Fork
##### Forking allows you to clone a repository on the gitHub server side. Then, you can clone it to your local system and push your new repository upstream. Typically used when multiple individuals are working in the same repository and/or files.
![github-large](https://i.ibb.co/zbvRLCh/Screenshot-2020-06-07-Ash33njit-IS218-Mini-Project-1.png)

### Branch
##### A branch is essentially a lightweight pointer to a commit. This allows you to “branch out”, and make a new state of your current code, while keeping your current code unaffected. So you can theoretically work on a new features to your code without interacting with your main code directly since it is stored in a branch named master. Typically used when you want to try multiple differnt things but your not sure what's the best route and you want to compare. Or when working on a new rendition or version of software
![github-large](https://backlog.com/app/themes/backlog-child/assets/img/guides/git/collaboration/using_branches_001.png)

### Commit
##### A commit is essentially a revision to a file or set of files. Every time a commit is made it creates an ID string called the SHA. This is to allow developers to keep a record of all the changes made to a project. Used nearly everytime you use Git. In order to save changes, ypou must commit.
![github-large](https://i.ibb.co/SrXmm6Y/Screenshot-2020-06-07-Ash33njit-IS218-Mini-Project-1-1.png)

### Merge
##### What a merge does is take changes made from one branch and apply them to another branch. This is the git command software engineers can use to merge changes made in their code with their main code.
![github-large](https://i.ibb.co/hy2yH2Q/Screenshot-2020-06-07-Ash33njit-IS218-Mini-Project-1-2.png)

### Checkout
##### The checkout command allows you to update a repositories state to a specific point in the project’s development. You can use the checkout command on the command line to create a new branch, change your current working branch to a different branch, or even to switch to a different version of a file from a different branch. The "checkout" action updates all or part of the working tree. Typically used when you need to work on different branches, create new branches, or explore files. 
![github-large](https://www.jquery-az.com/wp-content/uploads/2018/06/2.0_3-Git-checkout-branch.png)

### Push
##### The push command allows you send changes in code to remote repositories. For example, if an organization has a repository on Github a developer may push their changes to it.
![github-large](https://miro.medium.com/max/1200/0*TxVJi3f_GITlW6wF.gif)

### Pull
##### The pull command allows you to fetch new code from remote files and merge them with your current work. Typically used when you want to get the latest version of a file you want to work on. 
![github-large](https://miro.medium.com/max/1189/1*LnaAe0o0ZtiXCYV71VphPw.png)

### Remote Add / Remove / Show
##### These are the commands you use to work with remotes. Remotes are repositories stored on the internet or a network. With the add command you can explicitly create remote and define a url where this new repository will be stored. The remove command removes a remote. This is useful if you have a developer no longer contributing to a project. The show command allows you to view your various remote repositories. 
![github-large](https://www.jquery-az.com/wp-content/uploads/2018/07/7.0_2-Git-remote-add.png)

### Status
##### The status command analyzes the current repository and determines whether or not the current repository needs any items committed. This is useful for a developer to see if they need to make any commits to the code or just get an update on files so they don’t lose the new augmentations they made to the code
![github-large](https://miro.medium.com/max/1212/1*38gmQq3ESFXL5hTXWdqg-Q.png)

### Master Branch
##### Master is a default name for the original local branch of a project. The master branch is ultimately the main source code of a project. After a developer has made changes to a project in separate branches they merge the code back to the master branch and that is the main 
![github-large](https://www.nobledesktop.com/image/gitresources/git-branches-merge.png)
