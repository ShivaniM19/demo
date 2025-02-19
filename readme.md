this is git project 
username=shivani
useremail=adbc@gmail.com
## Merging a New Branch with Main Branch

To merge a new branch into the main branch, follow these steps:

1. Switch to the main branch:
   ```bash
   git checkout main
   ```

2. Pull the latest changes:
   ```bash
   git pull origin main
   ```

3. Merge the new branch:
   ```bash
   git merge <new-branch-name>
   ```

4. Resolve any conflicts (if they occur).

5. Commit the merge (if conflicts were resolved):
   ```bash
   git commit
   ```

6. Push the changes:
   ```bash
   git push origin main
   ```
