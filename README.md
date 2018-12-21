# useful_linux_scripts

# Git Scripts
You may download and copy following scripts into your `/usr/bin` , `/usr/local/bin` OR any folder listed in "PATH" environmental variable. Then you may use calling them as "git <feature_name>" like `git next-version`.

## Git - Next Version
This script creates a new hotfix after increasing latest released version by one and switches to that new branch. If you use update flag then it will update both master and development branches and then will create new hotfix. To use this feature you must also have [./git-update](git update) feature installed.

[git next-version](./git-next-version)

*Usage:* `git next-version [-u|--update]`

## Git - Update
This script updates both MASTER and DEVELOPMENT branches as set in your git flow config and switches to DEVELOPMENT branch.

[git update](./git-update)

*Usage:* `git update`
