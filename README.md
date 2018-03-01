# GitStudy
I will research remote function of git by remote method.
and I will create a branch to test the branch function.
First I am going to create a new branch named testing and push to the remote repository by following instructions.

1. create a new branch and switch to the new branch.
   git checkout -b testing

2. Modifying the Readme file and after saving , pushing the file to the remote repository.


Next , I create a new branch name joke on the GitHub web site , and create a new file on the joke branch.

Next , on the client , I cloned the repository and git create a remote branch (origin/master) and a track branch name master reference to the remote branch.

and I found out git fetch all the reference of the remote branch but didn't create the track branch for these remote branch .

but I can create it by following method.

1. git checkout --track origin/testing     -- to create track branch named testing .
2. git checkout -b testing origin/testing

above instruction get the same result.

so on the testing branch , I merged the Joke branch by following instruction.

git merge orign/Joke

so for , the file on the orign/joke add to the testing branch.

next I delete the joke branch. 

git push --delete Joke
