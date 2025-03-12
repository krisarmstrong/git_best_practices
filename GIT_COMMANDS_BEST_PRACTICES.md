# Git Commands & Best Practices

## Essential Git Commands

### Initializing a Repository
```sh
git init
```
Initializes a new Git repository in the current directory.

### Cloning a Repository
```sh
git clone <repo_url>
```
Creates a copy of an existing repository on your local machine.

### Checking the Status
```sh
git status
```
Displays the state of the working directory and staging area.

### Staging Changes
```sh
git add <file>
```
Adds a file to the staging area. To stage all changes:
```sh
git add .
```

### Committing Changes
```sh
git commit -m "Commit message"
```
Creates a snapshot of the staged changes with a descriptive message.

### Pushing Changes
```sh
git push origin <branch>
```
Uploads local branch commits to the remote repository.

### Pulling Changes
```sh
git pull origin <branch>
```
Fetches and integrates changes from a remote repository.

### Creating a New Branch
```sh
git branch <branch_name>
```
Creates a new branch.

### Switching Branches
```sh
git checkout <branch_name>
```
Switches to the specified branch.

### Merging Branches
```sh
git merge <branch_name>
```
Integrates changes from another branch into the current branch.

### Viewing Commit History
```sh
git log
```
Shows the commit history.

### Undoing Changes
#### Reset Last Commit (Keep Changes)
```sh
git reset --soft HEAD~1
```
Moves HEAD back by one commit but keeps changes staged.

#### Reset Last Commit (Discard Changes)
```sh
git reset --hard HEAD~1
```
Deletes the last commit and all associated changes.

## Best Practices
- Commit frequently with meaningful messages.
- Use feature branches for new development.
- Keep main branches clean and up-to-date.
- Review pull requests before merging.
- Use `.gitignore` to exclude unnecessary files.
- Regularly fetch and pull from the remote repository to avoid merge conflicts.

## Related Documents
- [README.md](README.md)
- [CONTRIBUTIONS.md](CONTRIBUTIONS.md)

## License
This project is licensed under the MIT License.
