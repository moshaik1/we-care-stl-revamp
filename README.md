# we-care-stl-revamp

# cloning repo
$ git clone **repo url**


# basic git commands

 - cd to correct file
 - $ git add .                  #adding file to staging area
 - $ git commit -m '**message**'  #commiting and adding message
 - $ git push 


# create your own feature branch whenever making changes and merge into master branch

# never make changes directly in master branch!!!

- $git branch                            # check what branch you are currently in
- $git checkout -b **feature branch name** # create new feature branch
- $code .                                # used to open vscode
- $ git add .                            # adding file to staging area
- $ git commit -m '**message**'            # commiting and adding message
- $ git push -u origin **branch name**     # pushing changes to feature branch
- $ git pull origin main                 # changes from main branch brought into feature branch

# make pull request on the github website

- $ git checkout main                    # go back to main branch
- $ git pull                             # update master with changes
- $ git branch -D **branch name**          # delete feature branch from local repo