About git-svn-utils
===================

Some utilities for more tight git-svn integration.

    git-svn-fetchbranch <remote branch name>
    
Fetches the remote branch from svn, and creates a local git branch
which tracks it.


     git-svn-lsbranches
     
Simple command which lists all remote svn branches.


Installation
---------------

Assuming your install lives in ~/src/git-svn/utils, add these to your
.bashrc:

     export PATH=$HOME/srv/git-svn-utils/bin:$PATH

And to setup bash completion for branch names from svn:

    source $HOME/src/git-svn-utils/bash_completion
    
