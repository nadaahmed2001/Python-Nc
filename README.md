# Tell me how to remove them locally and remotely.
-> To remove a branch locally:
- if the branch is fully merged:
  ` git branch -d dev `
- if the branch is not fully merged
  ` git branch -D dev `
  
-> Delete branches remotely
- `git push origin --delete dev`
- `git push origin --delete test`



# Tell me how to checkout another branch without commit changes
-> Stash your changes before switching
then checkout to another branch  
`git checkout branchName`


# Tell me how to list tags.
`git tag`

# Tell me how to delete tag locally and remotely.
-> to delete tag loccally:
  - `git tag -d v1.7`
    
-> to delete tag remotely:
 - `git push origin --delete v1.7`


# Add an image in the README.md file.
![tierno conejito](https://github.com/user-attachments/assets/1238c6ea-d01a-4e29-8e7a-ad009486ef87)
