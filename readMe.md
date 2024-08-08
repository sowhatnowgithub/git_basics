the readme is necessary for :) 
![Git logo](https://github.com/user-attachments/assets/613025ac-f5a2-4f28-841b-4eef5335c16e)

github/gitignore
 contains the all the ignoring files
```
git clone <url> #this will copy the files on to the pwd 
```
From here basics of git
We have to configure git (please do not include comments)

the following should be added into .git present in ur home directory 

inplace of  name write ur github account
```
  1 [user]
  2         name = sowhatnow_git\n
  3         email = noone@noreply.com #here give the email
  4 [core]
  5         autocrlf = input  #this will make sure there is no diff between linux and windows , while we share data
  6 [diff]
  7         tool = vscode #this is the defualt editor, well there is something if u want u have to create a path variable that will open vscode , when we hive command vscode , if u dont use , then it will be default
```

```
git init #this will download the git files essential 
git add file1 file2
git add *.js
git add . #this will add every file into the staging area

git status #this wil give files pos in staging area
git status -s #this will give short pos

git commit -m "message " #this will commit changes with a one-line message
git commit #this will commit changes without message

git commit -am "message" #skip the staging area

git rm file1 #removes from the staging and pwd 
git rm --cached file #removes from the staging

git mv file file1 #coping contents
git log
```
```
git diff --staged
```
a is previous , b is what is in stagged area , + indicates old ,- indicates current , 1,3 -> indicates taken from the file and printed 1 to 2nd lines
