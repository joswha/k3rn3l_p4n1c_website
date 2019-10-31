CONTRIBUTE
===
* Every contributor should create his own branches to develop the features he want. Every branch should be associated with one or more issues.
* Branch naming (#??? represents main issue associated with the branch):
    - New feature:`feature#???`
    - Bug fix: `fix#???`
    - Improvement: `improve#???`
    - Proof of concept: `poc#???`
    - Patch old version: `patch#???`
    - Unit testing: `testing#???`
* Branch names could optionally contain other information about what is developed, like `feature_LoginSystem#12`
* Create new branch using `git checkout -b <branch_name>`
* When you are creating a pull request for your features, please specify the issue(s) number that it fixes in the title, like `Create basic skeleton #1`. This will allow automated closing of the issue when the pull request is merged
* All branches must be created from devel and pull requests must be merged only into devel! Only at the end of each milestone a merge into master branch should be made.
