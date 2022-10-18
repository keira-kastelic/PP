# PP

Question 1: What does clone set the variable origin to represent?
   it will represent a refrance to a remote reposotory called orgin
   
Question 2: What does the command git push--set-upstream orgin master do? WHat does remote tracking mean in this context?
  The command sets the default remote branch to you current local branch. 
  Remote tracking tracks the remote repository by the local branch defined by upstream branches.
  
Q3 - Explain and illustrate what's happening in the commit tree when this command executes.
   It works by targetting and accessing only the main branch data

Q4 - Are your commits overwritten by the remote master?
   Git pull with never overwrite changes in the main branch. Only git reset can do that. 
   
Q5 - Is this a merge or a rebase?
   Merge
   
Q6 - Person B: checkout the local master branch. Is it updated as well, or still behind remote master?
   It is 1 step behind

Q7 - Run git branch. Did your local copy of your branch delete when Person A deleted the remote branch? No
If not, delete the local copy of the branch using git branch -d BRANCHNAME.
You told us not to worry about thsi step because terminal wasn't cooperating.
