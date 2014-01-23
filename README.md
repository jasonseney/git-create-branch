git-create-branch
=================

Creates (and switches to) a new branch both locally and on remote

Usage: `git create-branch foobar`

Example:

    src (lorem) $ git create-branch foobar
    Switching to master...
    Switched to branch 'master'
    Creating new branch 'foobar'...
    Switched to a new branch 'foobar'
    Pushing to remote origin...
    Total 0 (delta 0), reused 0 (delta 0)
    To ssh://git@github.com:user/project.git
     * [new branch]      foobar -> foobar
    Branch foobar set up to track remote branch foobar from origin by rebasing.
    src (foobar) $ 

### Notes:

Place in your bin directory to create the git alias.
