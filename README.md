# Git basics for a PR

### Git config
`$ git config --global user.name "User name"`

`$ git config --global user.email "User email"`

Set git identity
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20config.png)
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20config%20list].png)


### Git init
`$ git init`

initialize a new git repo
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20init.png)


### Git clone
`$ git clone [remote-identifies]`

Clone the remote repo in our local
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20clone.png)



### Git statuses
`$ git add [filename]`

Change file from working directory status to stagin




`$ git commit --message 'A relative work message'`

Change file in staging status to repository
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20commit.png)



### Git remotes
`$ git remote -v`

Shows up a list of all remotes registered in your repo




`$ git remote add [remote-name] [branch-name]`

Adds a new remote to the repository
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20remotes.png)



`$ git push [remote] [branch-name]`

Push all your registered changes to the given remote in a given branch.
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20push.png)


`$ git fetch origin [remote-branch-name]`

Get an specific branch from a given remote
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20download%20remote%20branch.png)


### Mixing changes

`$ git merge [branch-name]`
Merge changes from the given branch to the actual branch
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20merge%20changes.png)



### "Save" current work

`$ git stash`

Save the local modifications away en reset to match head commit.
![alt text](https://github.com/TheUrbina20/git-basics/blob/master/images/git%20stash.png)
