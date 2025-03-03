Basic git commends in CMD

* before push, most of commends about clone.
* after push, git repository changes

1. git clone <url>
   - make a copy of git file
   - change made in clone is only applied in clone

2. cd <fileName>
   - move into the clone file

3. fsutil file createNew <fileName> <Length>
   - make file. i.g. html, py...

4. start <fileName>
   - set to open the file

5. code .
   - run vscode
     
6. git add <file>
   - (use "git add <file>..." to update what will be committed)
     (use "git restore <file>..." to discard changes in working directory)
     
7. git commit -m <commit>
   - add commit about this change


  + git commit -am <commit>
     - add and commit same time
     - let git it changed and add commit about that

8. git status
   - could be omitted. Just check it has changed
  
9. git push
   - synchronize changed clone to main repository.


10. git pull
    - bring changed thing from git repository
   
11. git log
    - check the log
   
12. git checkout -b <Branch Name>
    - make new branch

12-1. git checkout <Name>
    - change head to branch which called Name

    
