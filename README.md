## HTTPS …or create a new repository on the command line

```shell
echo "# adad" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/dsz-hi/linux-command-line-and-shell-scripting-bible.git
git push -u origin main
```

## HTTPS …or push an existing repository from the command line

```shell
git remote add origin https://github.com/dsz-hi/linux-command-line-and-shell-scripting-bible.git
git branch -M main
git push -u origin main
```

## SSH  …or create a new repository on the command line
```shell
echo "# adad" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:dsz-hi/linux-command-line-and-shell-scripting-bible.git
git push -u origin main
```

## SSH …or push an existing repository from the command line

```shell
git remote add origin git@github.com:dsz-hi/linux-command-line-and-shell-scripting-bible.git
git branch -M main
git push -u origin main
```

