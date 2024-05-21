# Setting_Up_Repository

```diff

- Creating Repository with cloning, creating branches, committing and reverting commits, pulling and pushing changes downstream and upstream, fetching, merging and renaming branches, creating, reviewing merging, reverting, pull requests etc.

```

## Creating_Repositories

```diff
+ Since i am familiar git creating repo, i directly created mine from Github (from create_repo) called Setting_Up_Repository.

```

## Cloning_Repositories

```diff

+ Cloning the repo from Github to local machine.

$ git clone <myRepoName>

```

## Creating_Branches

```diff
+ Creating branches using *"git branch <branch>"* which i created a branch called "alt".

$ git branch alt

```

## Committing_and_Revert_Commits

```diff
+ Git commit using this:

$ git commit -m <commit_message>

+ Git revert will revert the latest commit.

$ git revert HEAD

- I reverted the commit from "Repo Demonstration" to "Repo Demonstration to Readme file".

```

## Pulling_and_Pushing_Changes_Upstream_and_Downstream

```diff

+ git pull the whole cloud server down to my local server while inside the repository.

$ git pull

+ git push the whole commits and files upstream - this goes directly to the Users repository on cloud servers like Github.

$ git push

+ git push whole commits downstream - this is been pushed from cloud to local server using the git pull.

```

## Merging\_,_Renaming_Branches

```diff

+ using the git merge features to merge contents in one branch to another.

$ git switch alt
$ git merge main

+ Rename branches using:

$ git branch -m <new_branch_name>

```

## Reviewing_Merging_and_Reverting_Pull_Requests

```diff

+ Review merges using git log:

$ git log <origin_name[main_or_master]>

+ Reverting commit on pull request:

"STEPS:"
1. Go to the pull request on Github.
2. Click on the "Files changed" tab.
3. Click on the "..." button on the right side of the file.
4. Click on "Revert to this commit".
! 1. Under your repository name, click "Pull requests".
! 2.
```
