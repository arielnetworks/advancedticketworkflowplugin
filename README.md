AdvancedTicketWorkflowPlugin
============================

This repository is a clone of the Trac-Hacks SVN repository.

http://trac-hacks.org/svn/advancedticketworkflowplugin

see also: http://trac-hacks.org/wiki/AdvancedTicketWorkflowPlugin


### Tips

To fetch/rebase from original svn repository:

    git config --add svn-remote.svn.url http://trac-hacks.org/svn/advancedticketworkflowplugin
    git config --add svn-remote.svn.fetch :refs/remotes/git-svn
    git checkout -b mylocalbranch
    git svn fetch svn
    git svn rebase svn

To get original source code after fetch remote svn repository:

    git checkout -b origlocalbranch git-svn
