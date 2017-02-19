Harley Refresh 
======================================================



### Workflow
**Add local files** >> **Commit local files** >> **Pull remote files** >> **Push local files**

<br>

### Open the terminal
1. Navigate to the project folder in Explorer (e.g. C:\Documents\harleyRefresh).
2. Right click anywhere inside the folder. Select 'Git Bash here'. A terminal window should pop up.

<br>

### Add local files
3. Run the following command in the terminal window: `git status`. Files that are either modified or newly-created will display as red text.
4. Any new files you add to the local folder will be *untracked*, and any exisiting files that you modify will be *unstaged*. To push your local changes to the repository, Git must first be tracking the files (meaning it can detect any differences between your local files and the ones stored in the repository), and the files themselves must be *staged* for commit. 
5. You can *track* and *stage* files by using `git add <file>`. You can specify a single file path (e.g. `git add about.html`), or you can add all unstaged/untracked files with `git add .`. Tracking a new file also automatically stages it for commit.

<br>

### Commit local files
6. With the files added, you can now *commit* your changes. Think of it like an advanced save. Run the following command: `git commit -m <message>`, where <message> is a short description of your changes. If you now run `git status`, the files you added previously should now appear in green.

<br>

### Pull remote files
7. Before pushing your changes to the repository, you have to pull. You must have the most up to date version of the remote repository before you can push your changes. To pull from the repository, simply run the follwing command `git pull`.

<br>

### Push local files
8. 
