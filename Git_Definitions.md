**Git Definitions**
  * Repository
    * The repository is the central storage location for your project.  It is the original project file from which clones will be created and worked on by developers.  As sections of the project are refined and updated, the changes approved by the project owner(s) will be updated to this central repository.  Once the entire repository is fully fleshed out, the project will be finished.
  * Clone
    * The clone is a local copy of the project contained within the repository on which the developer will work.  It is warehoused on the developer’s computer, typically in a directory with the nomenclature your-name/your-repo.  This file is sometimes referred to as a “working directory” or a “working tree".
  * Fork
    * Allows the developer to contribute to a public repository without potentially damaging work done on the main repository by creating a copy of the main repository on the developer’s computer, and under the developer’s account. Once forked, the developer must clone the forked project in order to manipulate it. 
  * Branch
    * A branch, or branches, are often made within a developer’s local copy, to allow them to test strategies or edits before committing changes to the main code in the master repository. 
  * Commit
    * This command will record the changes made in the local branch back to the master repository. 
  * Merge
    * This command allows the developer to combine separate branches together. It is a useful command in that it also identifies conflicts between the branches in need of resolution for the proposed code to work. This functionality is also useful in that it is designed to preserve coding history whenever possible, limiting change management to conflicts.
  * Checkout
    * This command allows the developer to switch between branches.  By entering the command git checkout <branch name> , the developer switches to that identified branch, allowing them to work on that identified branch. When this command is run, the HEAD pointer moves to the last commit made in the branch the developer is working in.
  * Push
    * This command is used to update the master repository with the developer’s updated project version from the local copy. 
  * Pull
    * This command allows the developer to request and retrieve code from a repository owner, in order to review and potentially make changes.  The repository owner will receive notification of said pull through Git Hub, and will decide whether or not to merge their repository with the proposed changes. If the repository owner elects not to merge the proposed changes into the master repository, they will click on the “Closed Pull Request” button with which they are presented, effectively rejecting the proposed change. 
  * Remote Add/Remove/Show
    * This command is used when the main repository is forked (duplicated) for remote editing}.  It is used to keep the remote fork on the developer’s computer synchronized with the original repository and any concurrent that may have been made by others upstream. 
  * Status
    * This command will give the developer a real time status of the files located in the developer’s working directory, specifically as it relates to the master file.  It will indicate whether the developer’s “branch” is current, detect any new files, tell the developer what has changed since the last status was run, and notify the developer if there are any updates pending commit. 
  * Master Branch
    * A master branch is created by default whenever a new repository is set up.  It is the main line of code from which all the follow on lines of development stem, and are committed, each branch of the master branch with it’s own separate commits.  The HEAD noted on the Master Branch is identified as the last position of committed code. 


 




 
 



	