# GIT-LFS

#### How to do it?

Step 1: Install Git-LFS
```
sudo apt-get install git-lfs
```

Step 2: Initialize Git-LFS in Your Repo
```
git lfs install
```

Step 3: Track Large File Types
```
git lfs track "*.bz2"
git lfs track "*.zip"
```

Step 4: Add Commit Push
```
git add file_name.bz2
```
```
git commit -m "uploading"
```
```
git push 
```