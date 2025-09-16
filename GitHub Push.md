# To push code to a Git repository, follow these steps:

1. **Initialize Git (if you haven't already):**
   ```bash
   git init
   ```

2. **Add your files:**
   ```bash
   git add .
   ```
   This stages all changes for the next commit. You can also specify individual files instead of using `.`.

3. **Commit your changes with a descriptive message:**
   ```bash
   git commit -m "Your commit message"
   ```

4. ** Do If Need - Pull any changes from the remote repository to ensure your local branch is up-to-date:**
   ```bash
   git pull origin main
   ```
   Replace `main` with your branch name if it's different. Resolve any merge conflicts if they arise.

5. **Push your changes to the remote repository:**
   ```bash
   git push 
   ```
   OR
   ```bash
   git push origin main 
   ```
   Replace `main` with the branch name you're working on if it's different (e.g., `master` or `dev`).

If you encounter any errors, make sure you have the necessary permissions and that your branch is up-to-date with the remote repository.

# Merge dev into dev-1
1. **Switch to your `dev-1` branch:**

```bash
git checkout dev-1
```

2. **Merge the latest changes from `dev` into `dev-1`:**

```bash
git merge dev
```

3. **Resolve any merge conflicts** (if Git prompts you) and commit the merge:

```bash
git add .
git commit -m "Merge dev into dev-1"
```
