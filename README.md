###Setting up the repo.
Generate an ssh key pair if you have not already using the command `ssh-keygen`

Go to github profile settinging and add the key to the `SSH and GPG keys` section in your github settings.

Paste the output form  `cat ~/.ssh/id_rsa.pub` into your github account; this command will display your public key in the console.

Once this is done and you are a collaborator with this repo by contacting the admin you can clone the repo using ssh keys.

Clone the repo in the folder `~/ilc_main/scipp_ilcsoft_framework/src/` using the command `git clone git@github.com:scipp-ilcadmin/shared_processors.git`.
**Repeat** clone the git repo once you are in `~/ilc_main/scipp_ilcsoft_framework/src/`.

Once cloned you need to make a bracnch so you don't mess up the collective repo.
To make a branch run `git checkout -b your_name`.

To commit, `git add file` then `git commit -m first_commit`.

