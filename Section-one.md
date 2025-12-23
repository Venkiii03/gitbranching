# gitbranching
Learning git branching 

**Level One - Git Commits** </n>
This screenshot shows the Learn Git Branching tutorial demonstrating basic Git commits on the main branch. A linear commit history (c0 → c3) is created, illustrating how each git commit advances the branch pointer.

**Commands Used** <br>
git commit <br>
git commit <br> <br>
<img width="1919" height="925" alt="Screenshot 2025-12-22 214448" src="https://github.com/user-attachments/assets/314cadd4-00da-4edb-8807-b395d3545bf0" />


**Level Two - Branching in Git**
This screenshot demonstrates creating and switching to a new branch in Git. A new branch named bugFix is created from the main branch and checked out, showing both branches pointing to the same commit (c1) with bugFix as the active branch.

**Commands Used** <br>
git checkout -b bugFix <br> <br>
<img width="1918" height="921" alt="Screenshot 2025-12-22 214641" src="https://github.com/user-attachments/assets/8775bc57-b427-472a-be26-2f92be857993" />


**Level Three - Merging in Git**
This screenshot illustrates a complete Git workflow involving branching, committing on different branches, and merging. A bugFix branch is created and committed first, followed by a commit on main. Finally, the bugFix branch is merged back into main, resulting in a merge commit and a non-linear commit history.

**Commands Used** <br>
git checkout -b bugFix <br>
git commit <br>
git checkout main <br>
git commit <br>
git merge bugFix <br> <br>
<img width="1919" height="930" alt="Screenshot 2025-12-22 215235" src="https://github.com/user-attachments/assets/240c2896-a56e-48ec-a015-3da10042b5e7" />


**Level Four - Rebase Introduction**
This screenshot demonstrates the use of Git rebase to move a feature branch (bugFix) on top of the latest main branch commits. The commit history is rewritten so that the bugFix commit appears after the main branch commits, resulting in a cleaner, linear history.

**Commands Used** <br>
git checkout -b bugFix <br>
git commit <br>
git checkout main <br>
git commit <br>
git checkout bugFix <br>
git rebase main <br> <br>
<img width="1917" height="922" alt="Screenshot 2025-12-22 215613" src="https://github.com/user-attachments/assets/f9709464-42a7-40fe-913b-f5d5ddfe10a4" />
