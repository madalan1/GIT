Git is a distributed version control system.
There are 3 types of vcs: local, centralized(all your source code is stored in a single central server and if that goes down you will not have any other version of your code) and distributed(developers will have entire copy of the project where you can pull, push your changes to the remote repo)
Git is an open-souurce-tool and github is a service where you can store your source code remotely.
First we need to cretae a local git repository
To initialize the git repository in the root of the folder use "git init"
Add a new file using touch command "touch newfile.txt"
To check the status of the file use "git status"
Add a file to stagingarea/index using "git add <filename>
You can commit using the commit message for beteer understanding of the modifed code or changes. git commit -m 'first commit'
you need to configure username and email address 
git config --global user.email <mail-address>
git config --global user.name <username>.