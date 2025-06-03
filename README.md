# Guidance 
To use `SeedWorks`  in this project, simply add a remote like this:  <br />  `git remote add seedworks git@github.com:bahmanbs/SeedWorks.git`. <br />
then add a subtree just like the following: <br /> `git subtree add --prefix Src/SeedWorks seedworks main --squash`.
this way the `SeedWorks` remains maintainable and can be developed completely Independently and any changes will easily be reflected to remote and others can pull latest version of it.<br />

to `push` any changes to SeedWorks: <br />
`git subtree push --prefix=Src/SeedWorks seedworks main`

and use `pull` to get latest changes : <br />
`git subtree pull --prefix=Src/SeedWorks seedworks main --squash`
