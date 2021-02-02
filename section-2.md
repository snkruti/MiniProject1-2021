## GitFlow, Git Commands, and Terminology

## What is Gitflow?

Gitflow is a branching model for Git. It allows for parallel development, collaboration, release staging area, and support for emergency fixes. 

#### Parallel Development:
Gitflow makes parallel development really easy by isolating new work from finished work. New work is done in feature branches, and is only merged back into main body of code when the creator is happy with the code and thinks its ready for release. 

#### Collaboration:
Feature branches make it easier for developers to collaborate on the same feature and easily see what other collaborators are doing, becasue changes that are made are only the ones to get the feature working.

#### Staging Area:
The develop branch is the staging area for the features that have been completed, but aren't released yet. When the next release is branched off of develop, it will automatically consist of all of the new stuff that has been finished.

#### Emergency Fixes:

Github supports hotfix branches which allows you to make any emergency changes, knowing that the hotfix will only contain your emergency fix. There’s no risk of accidentally merging in new development at the same time.
