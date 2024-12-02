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
-> Stash your changes before switching branches: 
`git stash`
