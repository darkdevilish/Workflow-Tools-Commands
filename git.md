Initiate a new git repository:
```console
git init
```

Add all files to repository:
```console
git add -A
```

See git status:
```console
git status
```

Make a commit with a message:
```console
git commit -m "Message"
```

Make a commit and add all files with a message:
```console
git commit -am "Message"
```

Make a commit without message:
```console
git commit --amend --no-edit
```

Create a new branch:
```console
git checkout -b branch_name
```

Switch branch:
```console
git checkout branch_name
```

Merge branch:
```console
git merge branch_name
```

Create alias to commands:
```console
git config --global alias.alias_name commandName
```

List all branches:
```console
git branch --all
```

See all modified files on branch:
```console
git diff --name-only master...
git diff --name-only master...branch_name
```

See all commited files changes:
```console
git log --oneline
git show commit_id
```

Push to repo:
```console
git remote add origin https://github.com/username/repo_name.git
git push -u origin master
git push -u origin --all(to push all branches too)
git push -u origin +branch_name(after already pushed to github to not have conflict)
```
