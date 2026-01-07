# lerobot

## Some bash commands
```
# in the home directory create a projects folder
mkdir projects
# create lerobot folder
mkdir lerobot
# show files with ls (list dir)
ls -lat

# github told us to do for init a git repository:
echo "# lerobot" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/shiradi08/lerobot.git
git push -u origin main

# update git
git add <file>
git commit -m "<message>"
git push
```

## Editor in the command line
```
nano <filename>
```

## Add a local python in the project
```
python3 -m venv venv
```
