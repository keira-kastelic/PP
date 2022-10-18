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

Q8 - 
* commit a758877cb9a7e5d0262c0fc37b0fd80093ff5e66 (HEAD -> main, origin/main, origin/HEAD)
| Author: gwcorbett143 <113716419+gwcorbett143@users.noreply.github.com>
| Date:   Tue Oct 18 12:15:36 2022 -0600
| 
|     Q7 Merge Conflict
|   
*   commit 59227e77122f9d1d3aa54eb03dca647504abdc60 (origin/Feature2)
|\  Merge: 77ec13c 1adf3b4
| | Author: keira-kastelic <79609952+keira-kastelic@users.noreply.github.com>
| | Date:   Tue Oct 11 15:36:48 2022 -0600
| | 
| |     Merge pull request #2 from keira-kastelic/Grant's-Branch
| |     
| |     Edit Garb
| | 
| * commit 1adf3b422b0e5ce93666cc38e43e15ad9660da34 (Grant's-Branch)
| | Author: gwcorbett143 <gcorbett23@kentdenver.org>
| | Date:   Tue Oct 11 15:34:51 2022 -0600
| | 
| |     Edit Garb
| | 
* | commit 77ec13c88ee6a6e63bb8f5a120622053aa7b9425
|\| Merge: a55c3c5 82818fb
| | Author: gwcorbett143 <113716419+gwcorbett143@users.noreply.github.com>
| | Date:   Mon Oct 10 14:41:20 2022 -0600
| | 
| |     Merge pull request #1 from keira-kastelic/Grant's-Branch
| |     
| |     Grant's branch
| | 
| * commit 82818fbe8ecf37f6b28d0c9d52213b9998a76851
| | Author: gwcorbett143 <113716419+gwcorbett143@users.noreply.github.com>
| | Date:   Mon Oct 10 14:25:48 2022 -0600
| | 
| |     Update README.md
| | 
| * commit a351fd8404f875256e738efc22d3a91765737a67
|/  Author: gwcorbett143 <113716419+gwcorbett143@users.noreply.github.com>
|   Date:   Mon Oct 10 14:15:48 2022 -0600
|   
|       Garb's Branch
| 
* commit a55c3c56f9626155abee65ebe668a9780db3bc01
| Author: keira-kastelic <79609952+keira-kastelic@users.noreply.github.com>
| Date:   Mon Oct 10 13:59:36 2022 -0600
| 
|     Create README.md
| 
* commit c8c5f55492b892b03e5de78289806f4409a27b56
| Author: gwcorbett143 <gcorbett23@kentdenver.org>
| Date:   Fri Oct 7 11:20:23 2022 -0600
| 
|     Test
| 
* commit 2c7968e51613d11a63ff36de1713d7c0f624384f
| Author: keira-kastelic <79609952+keira-kastelic@users.noreply.github.com>
| Date:   Fri Oct 7 10:42:59 2022 -0600
| 
|     A: Making a new file and committing it
| 
* commit 05210c21127b2c09765afe3fc40dba8724a7f5e5
  Author: keira-kastelic <79609952+keira-kastelic@users.noreply.github.com>
  Date:   Fri Oct 7 10:30:11 2022 -0600
  
      Initial commit
(END)

