# Git Tutorial :
## First I want to talk about Version Control:

 __Version Control__:Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.
 
 # There are three types of Version Control:
 
 * __Local Version Control:__
Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

* __Centralized Version Control:__
 This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.
 
 * __Distributed Version Control:__
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

# what is Git?:

* Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.

* Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN

* Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit

* Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

* States

Files in Git can reside in three main states: committed, modified and staged.

Committed

Data is securely stored in a local database

Modified

File has been changed but not committed to the database


Staged

Flagged a file’s changed version to be committed in the next snapshot

![github](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)


# [TO KNOW THE HISTORY OF GIT AND HOW WE GETTING STARTED CLICK ON THE LINK ](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#3) 

## Local Repository Structure:

 1. Working Directory: The actual files reside here.
 
 1. Index: The area used for staging
 
 1. Head: Points to the most recent commit
 
 ![github](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)
 
 # Remote Repositories:
 
 In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from
 
 
 [To Show All Details Go Through This Link ](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#3)
