1. Q: Suppose you had a file, called first.md, and you made a copy of this file, named it
   second.md and made some changes to it. Next, suppose you ran diff -u
   first.md second.md
   A: Content of second.md is:

```
A
B
$
C
#
%
E
F
```

2. Q: If you accidentally add a file to the staging area, you can remove it using git reset. For example, if you accidentally add third.md, but don’t want it to be committed yet, run git reset third.md and the file will be removed from the staging area, but it will still be in your working directory.
   A: True.

3. Q: The commands git reset and git revert can only be used to undo commits in the git repository.
   A: False, git reset can also used to undo staged files.

4. Q: The commands git checkout can be used to roll back to a certain commit hash (check the documentation if you are unsure)
   A: True.

5. Q: We cannot commit changes in the working directory directly to the repo without adding it to the staging index first.
   A: True.

6. Q: git log -p and git log will give you the same output.
   A: False, git log-p will show the difference between each commit.

7. Q: git log --oneline and git log --stat will give you the same output.
   A: False, git log --oneline only shows commit id, branches, and commit message.
