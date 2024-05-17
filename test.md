#git
Git is a version control system that tracks changes in our files. It allows us to have different versions of our project stored in a central location called a repository. We can easily revert to previous versions if needed, collaborate with others on the same project, and share our code with the Git Hub community.
#branch
List, create, or delete branches
#push
Update remote refs along with associated objects 
#push
 Record changes to the repository
#pull
Fetch from and integrate with another repository or a local branch
cllone
Clone a repository into a new directory 
#init
Create an empty Git repository or reinitialize an existing one
#add
Add file contents to the index
#install git
In order to install Git i used **apt install git** command 
then i used **git init** to create a git 
and then i checked the installed git version by **git --version** command
Then i managed to reach my account in GitHub with these two commands:
**Git config --local or global user.name "my github username"**
**Git config --local or global user.email "my github email"**
Then by using Git remote add origin "https github" command i connected to my remote git by my local git
Next by **Git clone "https github"** command i copied repositories in GitHub account to local git
And then i created a new file in devops repository by using **Touch test1** command
Then i pushed data in the local file to the remote file in branch master by git **push origin master** command
And then by **git add .**i send data in untracked and working directory to staged and index
And then with **Commit -m "description of recorded steps"** command it went from staged to head.