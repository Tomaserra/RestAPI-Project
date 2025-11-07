# RestAPI-Project
## First-time setup

### Simone and Marco - Joining an existing project
```bash
git clone https://github.com/Tomaserra/RestAPI-Project.git 
cd project
```
## Making edits to existing files
When edit .qmd or other files:
```bash
git add .
git commit -m "Describe what I changed"
git push
```
## Adding a new file
	1.	Create or save the new file inside the project folder.
	2.	Then tell Git to track and upload it:
```bash
git add newfile.qmd
git commit -m "Add new file"
git push
```
Or add all new/changed files at once:
```bash
git add .
git commit -m "Add new files"
git push
```


## Starting work on another day
Before doing anything:
```bash
cd /path/to/your/project
git pull
```
Tomás:
```bash
cd /Users/tomas_serra/Desktop/Mebiom/5th year/Erasmus/Erasmus Classes/Biomedical Informatics/RestAPI
git pull
```


Then, after editing:
```bash
git add .
git commit -m "My updates"
git push
```


