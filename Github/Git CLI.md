# Git Command Line Interface

GitHub Git Cheat Sheet : https://education.github.com/git-cheat-sheet-education.pdf



### <u>Setup</u>

**Set Username :** 

```
git config --global user.name “teknicus”
```



**Set User Email :**

```
git config --global user.email “mailme@thomasrob.in”
```



**Initialize :**

```
git init
```



**Add Files :**

- Add a particular file	

  ```
  git add <file>		
  ```

- Add all files in folder 

  ```
  git add --all  
  ```

- Add all the Folders, Subfolders and files. 

  ```
  git add --all :/ 
  ```



**Commit :** 

```
git commit -m "first commit"
```



**Attach remote repository :**

```
git remote add origin https://github.com/teknicus/<repo>.git
```



**Push to remote repository :**

```
git push -u origin master
```

