**Level One : Detach yo’ HEAD** <br>
This image demonstrates the Detached HEAD state in Git.
When you checkout a specific commit (C4) instead of a branch, HEAD becomes detached and points directly to that commit.
This is useful for reviewing old code or testing changes without affecting any existing branch. <br>

**Command used:** <br>
```git checkout C4```
<br>
<img width="1920" height="925" alt="Screenshot 2025-12-23 203820" src="https://github.com/user-attachments/assets/cb24ef2f-8e84-4ad4-92fb-63003d0ea3d7" />
<br>

**Level Two : Relative References (^)** <br>
This image shows how relative references work in Git using the caret (^).
HEAD^ moves the HEAD pointer to the previous (parent) commit of the current commit. <br>

**Commands used:** <br>
```git checkout C4```
```git checkout HEAD^ ```
<br>
<img width="1920" height="929" alt="Screenshot 2025-12-23 213505" src="https://github.com/user-attachments/assets/e0be95a6-fb80-41a3-8a1c-38608fb2b768" />
<br>

**Level Three : Relative References #2 (~)** <br>
This image demonstrates the use of relative references with ~ to move multiple commits back and how branches can be forcefully moved to a specific commit.
It shows updating main and bugFix branches using commit references without creating new commits. <br>

**Commands used:** <br>
```git branch -f main C6```
```git checkout HEAD^```
```git branch -f bugFix HEAD~1```
<br>
<img width="1920" height="932" alt="Screenshot 2025-12-23 220048" src="https://github.com/user-attachments/assets/e44d9a11-1b37-4600-b6bd-7e11e19a0c11" />
<br>


**Level Four : Reversing Changes in Git** <br>
This image explains how Git undoes changes using reset and revert.
git reset moves the branch pointer backward, while git revert creates a new commit that reverses a previous change (safe for shared branches). <br>

**Commands used:** <br>
```git reset HEAD^```
```git checkout pushed```
```git revert pushed```
<br>
<img width="1918" height="920" alt="Screenshot 2025-12-23 221923" src="https://github.com/user-attachments/assets/e75da3b6-46dd-4cd9-a838-0d56b8cacf02" />
<br>

