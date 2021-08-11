# Zendrix_Workflow
Prototype git architecture for monthly product release

This workflow would has the following branches;
- Master: This is the main production branch. Only release branch commits and hot fix commits can be merged into master branch
- Release: This branch should be forked from development branch on the 24th of each month and be merged with the master branch (production) at release time on the 25th of every month.  
- Development: This will be used for managing all feature branches and testing code before deploying to production branch
- Feature: This branch(s) can only be created from the development branch at any commit as the need arises. Branch should be deleted after merging commits back into development branch.
- Hot Fix: This branch should only be created from the master branch to make quick software patches. The commits from this branch should be merged to both the master branch and development branch.

# Additional Notes
Always delete feature branch when no longer in use
