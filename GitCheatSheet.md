https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf

https://www.git-tower.com/blog/content/posts/54-git-cheat-sheet/git-cheat-sheet-large01.png

https://drive.google.com/file/d/0BxQ69lTsNUqgeERJZ2RwTEtheVE/view?usp=sharing

[Detailed Reference](https://git-scm.com/docs)

## Short Codes

* Remote origin location
```git
git remote get-url origin
```

### PUSH

* force push
```git
git push -f <remote> <branch>
//git push -f origin master
```

### TAGS

* create tag
```git
git tag <tag name>
```

* list all tags
```git

git tag
//or

git show-ref --tags
//e7e66977c1f34be5627a268adb4b9b3d59700e40 refs/tags/osgeolive-6.5
//8f27e65bddd7d4b8515ce620fb485fdd78fcdf89 refs/tags/v8.0
```

//push every local tag to remote
```git
git push origin --tags
```

//push a specific local tag to remote
>git push origin : tagName

delete tags
>git push --delete origin Tag_AAA
