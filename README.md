# Project1

Hi, in order to clone this project go to your command line and navigate in the folder where you want your github project to be
located. 

1. Go to https://github.com/codephilip/Project1 and copy the clone/download url.
2. In your command line, type: git clone https://github.com/codephilip/Project1.git

-> You are now ready to access the files locally. 

3. choose a text editor or IDE, download it and access it using command line. 
  You can either manually import your project folder or use the command line. 
    
    For example, I am using atom text editor. So with my command line is simply navigate into my project1 folder and type the command: atom .
 
You can now play around with the code in your editor in a local environment. 



BASIC GITHUB COMMANDS

in command line navigate to local repository of project. 
1. Type: git status

-> This will show you any outstanding changes to be commited or pulled to/from github. 

2. Type: git pull 

-> This will update your local files to be upto date with github online repository.

3. When you are ready to add files to the online repository, Type: git add -A

-> to add changes from all tracked or untracked files. 

3.2 Type: git commit -m "Type message here"

-> To commit all new files to the online repository, or git commit index2.html

4. When everything is done, Type: git push

-> To upload to online repository. 




BRANCHES:

The stable version of our code is contained in the Master branch.
When we want to try out new code we do it in a new 'branch' before merging it with our stable code. 

1.How to create new branch.

in command line, navigate to github project folder and 
Type: 
      git branch -a
-> To see all the branches. The branch with the * next to it is the one you are working in. 

2.  To change the branch from/to which you are pulling/pushing code,
Type: 
      git checkout new-branch-name

3. To delete branch Type:
      git branch -D branch-name
      
