# Hello Git

## Step 1
```sh
$ git config --global user.name "XXX"
$ git config --global user.email "XXX@gmail.com"
$ cat ~/.gitconfig
```


## Step 2
create file
```sh
$ mkdir flieName
$ cd flieName
```

## Step 3

Initialization
```sh
$ git init
```

Create README.md
```sh
$ touch README.md
```

Check status now
```sh
$ git status
```

Save README.md
```sh
$ add README.md
```

Check status now
```sh
$ git status
```

No commits yet 
Changes to be committed use $ to unstage
```sh
$ git rm --cached README.md
```


Update README.md
```sh
$ git commit -m "add README.md(modify)"
```

join 
```sh
$ git remote add origin https://github.com/name/git-tutorial.git
$ git push -u origin main
```



## Git常用指令

- 查看Git版本：git --version
- 查詢當前狀態：git status
- 初始化數據庫：git init
- 將檔案加入索引：git add .
- 將索引檔案更新：git commit -m "修改內容"
- 檔案上傳遠端：git push
- 更新本地：git pull
- 抓取GitHub：git clone 網址
  
