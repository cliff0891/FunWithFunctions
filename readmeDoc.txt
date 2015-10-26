# Read Me File to Start a program 

 Example: fun with functions

1. Start Eclipse

2. Change the workspace
	:file>switch workspace
3. Start a new project: FunWithFunctionsProject
	fILE>NEW>java project
		:use default runtime environment,
			:then click finish
4. Add a new class with our new project selected: FunWithFunctionsProject
	:file> new > class
		:Name it, select the public static void main option and finish.


 Now begin Git and GitHub
1.Open the command prompt.
	:Start >search for cmd> strike enter
1. Go to your project folder:
	 E:\COMSC\FunWithFunctionsProject
		E: to change to the thumb drive
		dir to list the directory
		 E:\COMSC\FunWithFunctionsProject

2.git init to begin a new local repo

E:\COMSC\FunWithFunctionsProject>git init
Initialized empty Git repository in E:/COMSC/FunWithFunctionsProject/.git/

3.git add . to add material.
E:\COMSC\FunWithFunctionsProject>git add .

4.git config user.name
E:\COMSC\FunWithFunctionsProject>git config user.name "cliff0891"

5.git config user.email
E:\COMSC\FunWithFunctionsProject>git config user.email yuyunc@student.swosu.edu

6. Start a browser
7.to GitHub.  www.github.com
8.login to your person account
9.add a new repo
10.follow the online instructions on how to:
push an existing repository from the command line

E:\COMSC\FunWithFunctionsProject>git remote add origin https://github.com/cliff0
891/FunWithFunctions.git

E:\COMSC\FunWithFunctionsProject>git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/cliff0891/FunWithFunction
s.git'

E:\COMSC\FunWithFunctionsProject>git add .

E:\COMSC\FunWithFunctionsProject>git commit -m "first commit"
[master (root-commit) caee02c] first commit
 5 files changed, 77 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .project
 create mode 100644 bin/FunWithFunctionsProject.class
 create mode 100644 readmeDoc.txt
 create mode 100644 src/FunWithFunctionsProject.java

E:\COMSC\FunWithFunctionsProject>git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


E:\COMSC\FunWithFunctionsProject>
E:\COMSC\FunWithFunctionsProject> git push --set-upstream origin master
Username for 'https://github.com': cliff0891
Password for 'https://cliff0891@github.com':
Counting objects: 9, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 1.78 KiB | 0 bytes/s, done.
Total 9 (delta 0), reused 0 (delta 0)
To https://github.com/cliff0891/FunWithFunctions.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

E:\COMSC\FunWithFunctionsProject>


