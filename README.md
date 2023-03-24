# Here are the steps I followed in order to commit for the 1st time
# Create a remote repo for the authenticated user : 
$ curl -L \ 

  -X POST \ 

  -H "Accept: application/vnd.github+json" \ 

  -H "Authorization: Bearer yourauthtoken"\ 

  -H "X-GitHub-Api-Version: 2022-11-28" \ 

  https://api.github.com/user/repos \ 

  -d '{"name":"yourReponame","description":"<This is your first repo!>","homepage":"https://github.com","private":false,"is_template":true}'

# Create a directory and a file to commit locally using my variables:

- $ mkdir ARAP22

- $ cd ARAP22

- $ sudo nano readme

- $ git init

- $ git add readme

- $ git commit -m "My first commit" 

- $ git remote add readme https://github.com/Nevralgie/ARAP22.git

- $ git push -u readme main

# Head to your Github repositories to verify the commit.

# If you wish to modify someone's repo after the owner gave you permissions in 'Collaborators' :

- $ git clone https://github.com/yourcollaboratorusername/reponame.git

- $ cd reponame

# I used nano to modify the file:

- $ sudo nano filename

- $ git init 

- $ git add filename

# Verify that the file is in the staging area and push it :

- $ git status   

- $ git commit -m "yourmessage" 

- $ git remote add filename https://github.com/yourcollaboratorusername/reponame

- $ git push filename main

# Hello world !
