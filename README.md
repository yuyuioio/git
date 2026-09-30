# git

Project repository.

## Push updates to GitHub

After editing and saving your project files, open PowerShell and run:

```powershell
Set-Location 'Z:\user\desktop\git'
git status
git diff
git add README.md
git commit -m "Update README"
git push
```

Replace `README.md` with the files you want to commit. To include all changes,
use `git add .` after checking the file list for private files and credentials.
Change the commit message to describe your update.

`git commit` saves a local version; `git push` uploads local commits to GitHub.

Repository: https://github.com/yuyuioio/git
