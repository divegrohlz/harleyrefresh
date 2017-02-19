Harley Refresh 
======================================================

A quick walkthrough of everything you need to get yourself up and running. As always, give me a shout if you need a hand with anything.

<br>

## Workflow

<br>

#### Open the terminal
* Open the project folder in Sublime Text.
* Navigate to the project folder in Explorer (e.g. C:\Documents\harleyRefresh).
* Right click anywhere inside the folder. Select 'Git Bash here'. A terminal window should pop up.

<br>

#### Run Gulp
* In the terminal window, run the following command `gulp`.
* This will compile all of your files in the src/ folder, and add them to dist/. 
* dist/ is production code. You never want to modify anything in here. Always work from src/.
* After compiling, the gulp task should automatically open the browser and begin watching for any changes you make to src/.
* If you make any changes to the src/ files, gulp will automatically recompile the code, and automatically refresh your browser. 
* If you want Gulp to stop running the watch task, press **ctrl + c** inside the terminal window.

<br>

#### Custom code
* Add any custom css styling to **./src/scss/main.scss**.
* Add any custom javascript to **./src/js/app.js**.

<br>

## Github

<br>

#### Open the terminal
1. Navigate to the project folder in Explorer (e.g. C:\Documents\harleyRefresh).
2. Right click anywhere inside the folder. Select 'Git Bash here'. A terminal window should pop up.

<br>

#### Add local files
* Run the following command in the terminal window: `git status`. Files that are either modified or newly-created will display as red text.
* Any new files you add to the local folder will be **untracked**, and any exisiting files that you modify will be **unstaged**. To push your local changes to the repository, Git must first be tracking the files (meaning it can detect any differences between your local files and the ones stored in the repository), and the files themselves must be **staged** for commit. 
* You can **track** and **stage** files by using `git add <file>`. You can specify a single file path (e.g. `git add about.html`), or you can add all unstaged/untracked files with `git add .`. Tracking a newly-created file also automatically stages it for commit.

<br>

#### Commit local files
* With the files added, you can now *commit* your changes. Think of it like an advanced save. Run the following command: `git commit -m <message>`, where <message> is a short description of your changes. If you now run `git status`, the files you added previously should now appear in green.

<br>

#### Pull remote files
* Before **pushing** your changes to the repository, you have to first **pull**. **Pulling** grabs the remote repository contents and merges them into your local folder. To pull from the repository, simply run the following command `git pull`. Send me a message if there are ever any conflicts at this point.

<br>

#### Push local files
* You have now tracked your local files, staged them for commit, committed them, and pulled the latest version of the repository into your local project folder. All that is left to do now is run the following command: `git push`. 

<br>

#### Example
* Click [here](http://i.imgur.com/jdh38RF.png) for an example of me modifying the readme.md file, and pushing the changes to the repository.


