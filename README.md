# How to use GIT and GITHUB

## Notes for some basic steps

### 1. Clone your projects located in GIT to your local computer
```
git clone URL
```

### 2. Add your file from Working Area to Stage Area
```
git add filenmae
git add .
```

### 3. Commit
```
git commit -m "message for commit"
```

### 4. Push
```
git push origin main
```

## Some other GIT tips

### show our commit history (origin : GITHUB, HEAD : local)
```
git log
```

### find out some comments
```
git commit -help
```

### move your HEAD to the past history; just see the past commit code
```
git checkout commitID
git checkout main
```

### reset your HEAD
```
git reset --hard HEAD^
git reset --hard HEAD^^
```
> after hard delete, forcing push to the origin
```
git push origin main --force
```