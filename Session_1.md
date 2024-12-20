
**1. Introduction to GIT & GITHUB**
•	GIT: A distributed version control system that helps track changes in source code during software development. It allows multiple developers to work on a project simultaneously without overriding each other's changes.
•	GITHUB: A web-based platform that uses Git for version control. It offers additional features such as bug tracking, task management, and collaboration tools. 
________________________________________
**2. Versioning**
•	Concept: Versioning is the process of assigning unique version numbers to specific states of software. It helps in tracking changes, identifying specific sets of changes, and managing releases.
•	Benefits:
o	Keeps a history of changes.
o	Helps in collaborative development.
o	Simplifies bug tracking and fixes.


**3. Local repository to git:**

```
 ssh-keygen
 cd .ssh

 cat id_ed25519.pub

#add this content in your git profile 

 git config --global user.name "sudarshanlnx"
 git config --global user.email "sudarshanlnx@gmail.com"

 mkdir gitdemo
 cd gitdemo
 git config --global init.defaultBranch master

 git init
 touch file1
 touch file2
 touch file3
 touch file4

 git add .

 git commit -m "initial_commit"

 git remote add origin https://github.com/sudarshanlnx/gitsession.git

 git pull origin master --allow-unrelated-histories

 git push -u origin master
```

**4. Cloning method:**

```
 mkdir gitdemo2
 cd gitdemo2
 git clone git@github.com:sudarshanlnx/gitsession2.git

 cd gitsession2/

 touch pythonfile1
 touch pythonfile2
 touch pythonfile3

 git add .

 git commit -m "new_change"

 git push

 git pull
```
