# Git Practise
---

**NOTE:** 
remote-repo-ssh => example : git@github.com:codeAlok/git-practise.git

* To initialize git folder/track files
    ```bash
    git init
    ```

* To check status of repository
    ```bash
    git status
    ```
* To check log/ previous commit details
    * In brief
        ```bash
        git log
        ```
    * In short/oneline
        ```bash
        git log --oneline
        ```
* To get remote repository to local system.
    ```bash 
    git clone remote-repo-ssh
    ```

* Add file to staging area.
    * All files at once
        ```bash
        git add .
        ```
    * selected file/folder
        ```bash
        git add file/folder_path
        ```

* Commit to save changes with message
    ```bash
    git commit -m "message-whatever-changed"
    ```

* Connect local repository to remote repository
    ```bash
    git remote add origin remote-repo-ssh
    ```

* Push your code with changes onto Remote repository on github 
    ```bash
    git push origin master
    ```