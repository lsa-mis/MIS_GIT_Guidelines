# Github

## Protectiong Branches 

Github has a setting that protects a branch from accepting force-pushes as well as protecting the branch from being deleted. It is recommended that this protection be enabled on the 'Master' branch as well as any 'deploy' branches. Essentially, any branch that is used in a production type of scenario. (Any branch that you don't want to have messed up over time.) Conversely, this is NOT recommended for feature branches or branches that are intended to be temporary.

To enable this protection 

1.) Select the repository
2.) Select the branch that you want to protect
3.) Select 'Settings'
4.) Select 'Branches' from the 'Options' navigation bar
5.) Select the Master (or the branch that you wish to protect) from the 'Protected branches' dropdown
6.) Check the 'Protect this branch' option

![Protecting a branch](../images/protecting_branches.png "Protecting a branch")