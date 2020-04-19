# Git-and-Github

git config     :-to tell who is owner of changing the things
git config --global user.name "rob"    :- provide your user name
git config --global user.email "rob@gmail.com"	 :- provide your mail id
git config --list	:- to find out all the user name and email
git init :- chnage project into repository
cat > sample.txt 	:-for creating sample.txt file
cntrol+z 	:- after creating and writing text in sample.txt ,when you want to clos
git status 	:- for checking status
git diff   	:- for checking complete status what you have changed(only tell the differnece    
                 between working copy and repository)
working copy>statging are>repository
git diff --staged :- tell the differnec between staging copy and repository
git add sample.txt 	:-for adding sample.txt to git
git add . 	:-for adding everything in the given folder
git commit -m "some mesage" 	:- this is used fro commiting file and leaving a message
git commit -am "some message" :-for direct sending working copy to repository.
ls 	:- for listing all the files
ls -la  :- for listing all the secret files
cd Documents 	:- for going to the documents folder(next path)
cd .. 	:-for getting back to the previous folder path
git log 	:- for checking the commit that we did or for rollouts
git log --author="rob" :- for checking the commit done by author rob only
git help 	:-for help
pwd :- for checking currently where are we.
git rm roy2.txt :- to remove the file roy2.txt
                  after tyhe deleting we have to commit
git commit -m :-to save the delete 
git mv roy.txt roy2.txt :- for renaming the roy.txt to roy2.txt
git mv roy4.txt temp :-for moving the roy4.txt file to temp folder 
git mv royThird.txt temp/love.txt :- moving royThird.txt to temp folder and renaming to love
git checkout -- index.html :- movie repository copy to working copy,,so let's say you have done some mistake in so want to roll out to previous state.   
sudo chmod o+rw /var/www :- to give permission to the file
service apache2 start:-fro starting the apache server    
git reset HEAD profile.html :- move folder from staging area to working copy    
git checkout d7638fd8922 -- index.html :- if you have commited and want to go back to previous commited state. where d7638fd8922 is previous commit number
 git remote add githubRepo https://github.com/AnkurKumar23612/Tutorial.git :- for adding something from local copy to github   where githubRepo is remote name

git remote :-to check the remote name   

git push -u githubRepo master :-to push all the files from laptop to github       

git push origin master :- to push if you have made changes in the file after pushing to the github  

git branch develop :-to make new branch owner.

git checkout develop :-to switch from master branch to develop branch

git checkout -b dhaka :-to make new branch owner.

git merge develop :-to merge develop bransh to master branch

git push githubRepo master --force :-to send the updated file to github


