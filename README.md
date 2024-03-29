# Git Learning Repository

Welcome to the Git Learning Repository! This repository has been created with the purpose of experimenting with various Git commands.

## Getting Started

**Clone the Repository:** Begin by cloning this repository to your local machine using the following command and experiments with various Git commands:

```
git clone <repository_url>
```

## Cheat Sheet

For a quick reference guide on how to use Git, check out our [Cheat Sheet](https://www.digitalocean.com/community/cheatsheets/how-to-use-git-a-reference-guide). This guide covers essential Git commands, making it easier for you to grasp the basics.

Happy learning and happy coding! 🚀

git add <additional_files>

**Add changes to last commit:**

1. **Stage Your Additional Changes:**

   ```bash
   git add <additional_files>
   ```

2. **Amend the Previous Commit with the New Changes:**

   ```bash
   git commit --amend --no-edit
   ```

3. **Push the Changes (If Appropriate):**
   If the commit hasn't been pushed to a remote repository, you can push the changes as usual. If it has been pushed, carefully consider the implications of amending the commit and possibly disrupting the work of collaborators.

**Undo Last Commit:**

Delete a previous commit and update the remote repository

1. **Identify Commit:** Find the commit's identifier using.

   ```bash
   git log
   ```

2. **Create Backup (Optional):** Create a backup branch using.

   ```bash
   git checkout -b backup_branch
   ```

3. **Reset Commit:** Use to remove the commit and its changes.

   ```bash
   git reset --hard <commit_hash>
   ```

4. **Force Push:** Push changes to remote with.

   ```bash
   git push origin <branch_name> --force
   ```
