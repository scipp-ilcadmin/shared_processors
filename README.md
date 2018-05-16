# Summary

This is version controlled history, where each branch represents a module of code or a person's in the groups code. The master branch is reserved for finished modules.

In order to setup the repo, there are only 3 steps. Setting up keys, cloning the repo, preparing your first branch.

# Setting up keys

Generate an ssh key pair if you have not already using the command `ssh-keygen`


Go to github profile settinging and add the key to the `SSH and GPG keys` section in your github settings.


Paste the output form  `cat ~/.ssh/id_rsa.pub` into your github account; this command will display your public key in the console.


Once this is done and you are a collaborator with this repo by contacting the admin you can clone the repo using ssh keys.


# Cloning the repo


Clone the repo in the folder `~/ilc_main/scipp_ilcsoft_framework/src/` using the command `git clone git@github.com:scipp-ilcadmin/shared_processors.git`.

**Repeat** clone the git repo once you are in `~/ilc_main/scipp_ilcsoft_framework/src/`.


Once cloned you need to make a bracnch so you don't mess up the collective repo.

# Preparing your branch

To make a branch run `git checkout -b your_name`.


To commit, `git add file` then `git commit -m first_commit`.

Once your are ready to push, `git push -u origin your_name`.


To merge your branch with the master because you want to share your code with the collective group, goto github and make a pull request.


If you are collaborating with another group member you can pull from eachothers branches without effecting the master brach by chaning the branch you are on.


For example if you want to collaborate with team_member then run `git checkout team_member` to switch to their branch. Now you can pull their code from the repo.


Note: To commit changes to all the files in your folder run `git add -A` before `git commit -m "messages on days"`.

