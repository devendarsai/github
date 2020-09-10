# Github
This repository consists of useful git operations and related operations related to git

- Set the username of the git as global:
  $git config --global user.name "user.name"

- View the username of the git:
  $ git config --global user.name

- Set the email of the git as global:
  $ git config --global user.email "email@email.com"

- View the email of the git:
  $ git config --global user.email

- Clone the repository using HTTPS:  
      $ git clone https://github.com/in28minutes/MavenIn28Minutes.git  
      Cloning into 'MavenIn28Minutes'...  
      remote: Enumerating objects: 44, done.  
      remote: Counting objects: 100% (44/44), done.  
      remote: Compressing objects: 100% (34/34), done.  
      Recremote: Total 459 (delta 8), reused 22 (delta 2), pack-reused 415  
      Receiving objects: 100% (459/459), 864.17 KiB | 886.00 KiB/s, done.  
      Resolving deltas: 100% (125/125), done.  

- Verify the new upstream repository you've specified for your fork.  
      $ git remote -v  
      origin  https://github.com/in28minutes/MavenIn28Minutes.git (fetch)  
      
- To add the files to stage:
	git add filename

- To committ the changes in the stage area
	git -m "message"
- To make the changes to central repository i.e., github.com on internet.
	git push
- To know the status of git in local repository
	git status
- To know the branhes 
	git branch
- To create a new branch
	git branch ranchname
- To switch to a branch
	git checkout branchnametoswitch

