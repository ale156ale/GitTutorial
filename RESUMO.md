Created by Alexandre Antonio Barelli in 06/08/2023
base Github instructions

create a new repository on the command line
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

echo "# teste" >> README.md  ## insert text in README.md
git init                     ## inicialize a git
git add README.md            ## add file to commit  git add . ## add all files
git commit -m "first commit" ## commit = prepare to send to remote
git branch -M main           ## rename "master" branch to "main"
git remote add origin git@github.com:ale156ale/teste.git  ## link origin (local) to remote (github server)
git push -u origin main      ## send commited files to github server, firt push "-u origin" is mandatory, after only "git push origin main"

push an existing repository from the command line
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

git remote add origin git@github.com:ale156ale/teste.git
git branch -M main
git push -u origin main

concepts
-=-=-=-=-

main / master = main line in project
branch = way ou road to develop. branch main/master is head way
merge = join another branch to main branch
remote = github server
origin = local repository
add = add files to commit
commit = prepare files to present or incluide in a branch. Prepare to send to remote server.
push = send files to server
pull = request files from server
clone = clone local a remote remository (your or the anothers).
fork = join another person repository to you repository
pull request = send fork (your repository) changes to onner person repository.

