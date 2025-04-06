# 30 Essential Git Commands

Git is a version control system widely used for tracking changes in projects. Below is a list of 30 essential Git commands to help you work efficiently with repositories.

1. **Set user name and email**
   - `git config --global user.name "Your Name"` — Set the username for commits.
   - `git config --global user.email "your.email@example.com"` — Set the email for commits.

2. **Cache credentials**
   - `git config --global credential.helper cache` — Enable credential caching to avoid entering the password with each commit.

3. **Initialize a repository**
   - `git init` — Create a new empty Git repository in the current directory.

4. **Add files to the staging area**
   - `git add <filename>` — Add a specific file to the staging area.
   - `git add .` — Add all changes in the current directory to the staging area.

5. **Check repository status**
   - `git status` — Show the current status of the repository, including modified, added, or deleted files.

6. **Create a commit with a message**
   - `git commit -m "Commit message"` — Create a commit with the specified message.

7. **View commit history**
   - `git log` — View the full commit history.
   - `git log --oneline` — View a brief commit history in one line.

8. **View changes before committing**
   - `git diff` — Show the differences between the current changes and the last commit.

9. **Remove tracked files from the working directory**
   - `git rm <filename>` — Remove a file from the working directory and the index.

10. **Rename files**
    - `git mv <old_name> <new_name>` — Rename a file in the repository.

11. **Discard changes in files**
    - `git checkout -- <filename>` — Discard changes in a file, reverting it to the state of the last commit.

12. **Amend the last commit**
    - `git commit --amend` — Modify the last commit (e.g., for fixing the commit message).

13. **Undo the last commit**
    - `git reset --hard HEAD~1` — Remove the last commit and all associated changes.

14. **Reset to a specific commit**
    - `git reset --hard <commit_hash>` — Reset the repository to a specific commit.

15. **Create a new branch and switch to it**
    - `git checkout -b <branch_name>` — Create a new branch and switch to it.

16. **View a list of branches**
    - `git branch` — Show a list of all local branches.

17. **Delete a branch**
    - `git branch -d <branch_name>` — Delete a specified local branch.

18. **Merge branches**
    - `git merge <branch_name>` — Merge the specified branch into the current branch.

19. **View commit history in a graph**
    - `git log --graph --oneline --all` — View the commit history in a graphical format.

20. **Abort a merge in case of conflicts**
    - `git merge --abort` — Abort the merge process in case of conflicts.

21. **Add a remote repository**
    - `git remote add origin <url>` — Add a remote repository with the given URL.

22. **View remote repositories**
    - `git remote -v` — Show the list of remote repositories.

23. **View detailed information about a remote repository**
    - `git remote show origin` — Display detailed information about the remote repository.

24. **Push changes to a remote repository**
    - `git push origin <branch_name>` — Push changes from the current branch to the remote repository.

25. **Pull changes from a remote repository**
    - `git pull origin <branch_name>` — Fetch and merge changes from the remote repository.

26. **Fetch changes from a remote repository**
    - `git fetch origin` — Fetch changes from a remote repository without merging.

27. **Push a new branch to a remote repository**
    - `git push origin <branch_name>` — Push a new branch to a remote repository.

28. **Delete a remote branch**
    - `git push origin --delete <branch_name>` — Delete a branch from the remote repository.

29. **Rebase a branch**
    - `git rebase <branch_name>` — Rebase the current branch onto the specified branch.

30. **View Git configuration**
    - `git config --list` — Show all Git configuration settings for the current user.
