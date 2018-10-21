# GitHub Tutorial

_by Gabriela Bochen_

---
## Git vs. GitHub

 * Git 
    * version control method used for tracking changes in folders and files.
    * Saves "Snapshots" of code
    
* Github 
    *   is a platform used for storing code in a cloud (on the web) 
    *   Requires Git
    *   Visually tracks code
     

  
  
  
 
---
## Initial Setup



1. Open and log into Cloud9 
2. Open and log into Github
4. In Github, open settings and on the left side bar open "SSH and GPG keys"
5. Press green button "New SSH Key"
6. Type in title. Make it relavent to your Local 
7. For the "Key": Switch into cloud9 > Press gear icon > SSH keys tab > copy and paste the second SSH Key provided 
8. Switch back into Github and paste the SSH Key
9. In Cloud9 open Workspace
10. In the command line type _"ssh -T git@github.com"_ A message should apprears that says you've successfully authenticated. 


---
## Repository Setup
##### Creating a Repository and files on c9
 Before making a directory/repository, the command line must show that you are currently in workspace. It
 should look like this **INSERT IMAGE HERE**   If you are not in Workspace you must use `cd ..` until you reach the worskapce. 
 
 When that is done, the directory is ready to be created   
 By using the command `mkdir [INSERT NAME]` you are creating a new directory.   
 
Next `cd [NAME]`   By doing this, it allows you to move into that directory.   

Following that, you must use the comand `git init` This will create a repository were you can create, save, store and edit work or files.

Now in this repository you can create a file.   
The command `touch [NAME]` is to make that file.  
Open the file and edit as wished.  

Next, Save add and commit: 
* to Save either press ⌘S or turn on autosave
* To add `git add .` 
* to commit `git commit -m "[MESSAGE]"`

##### __Creating a Repository on Github__

Now after recording the changes to your _local_. The next step is creating a Repository on Github. This will allow for the current work to be sent up to Github which known as the _remote_.   


1. Go to Github 
2. click to top right "+" 
3. Choose new Repository 
4. name the repository the same name as you repository in c9 (local). 
5. After pressing the "create repository" button gitbuh brings you to a page like **THIS**
6. At the top there is an option for either an HTTPS or SSH link those the link for the SSH 
7. Then copy and paste the two links found in the middle of the page to the command line . They should look like this : 
 `git remote add origin git@github.com:gabrielab6582/name.git   ` and 
`git push -u origin master`  

Now Github has been connected to c9. 

--- 

## Workflow & Commands



---
## Rolling Back Changes