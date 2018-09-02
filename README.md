
## 1. How do you see the files changed within each commit from git log?

Try this command: 
    git log  --stat       
It gives the files that are changed with the commit command.
   
Try this command:
    git log   --patch      
It gives not only the files committed but also the details of what was changed.    

## 3. What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)

HEAD means current branch. When switching branches, the HEAD changes to point to the tip of the new branch.
