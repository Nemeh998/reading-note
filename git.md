
#  What is Git?


 
  >* ## Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. And it works on local operations.
  
#### Getting started  :checkered_flag:

to start using git you must download it to your computer that fit your operating system.

Download Git In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

##### Git can be installed in three ways:
-Install as a package
-Install via another installer
-Download and compile the source code.
```
Example :To check settings, use the (`git config --list`) command.
```
![git](https://notme20n.files.wordpress.com/2020/01/git.jpeg?w=1024)






# **Git branch** 
 * >###  Lists all your project branches and highlights your current branch. If you just cloned a project, you are going to be in the master branch (your source of truth). It is not advised to work directly on the master branch because there is a big chance you would have a broken project while you are adding some progress. Instead, you want to create a different branch, work on your changes or new feature and when you are done and everything is working as expected, merge that branch into master.










######[The Life Cycle of File Status](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)



# Remote Repositories
>**In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.**
1. By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

2. By using git remote -v, you can view all the remote URLs next to their corresponding short names.
###Seeing Your Remotes
```
$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
```