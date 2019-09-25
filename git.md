# GIT :
**WHAT IS GIT ?** 
![GIT](https://git-scm.com/book/en/v2/images/areas.png)

*Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it*
Git thinks about its data more like a stream of snapshots. 
**Downloading git :** 
 order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.
Git can be installed in three ways:
1. Install as a package
1. Install via another installer
1. Download and compile the source code.
### Cloning;

*You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

 git clone
 *After you edit a file, Git flags it as modified because of changes made after the previous commit.
You stage the modified file.Then, you commit staged changes.*

**To determine the state of files, utilize the git status command:**
 
 git status

**Track all files in a repository by using the following command:**

git add

**After staging one or multiple files, you should commit the changes and record what you did within the commit message:**

git commit -m “made change x,y,z”

**Next, you would push changes to a remote repository.**

git push origin master
