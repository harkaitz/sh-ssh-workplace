SSH WORKPLACE
=============

Manage the "Employee Computer Fleet" and their shared working directories.

## Help

ssh-h-workplace

    Usage: ssh-h-workplace [show|USER@HOST] ...
    
    Manage the "Employee Computer Fleet" and their shared working
    directories.
    
    Configuration files and directories:
    
      SSH_H_WORKPLACE       : ID SSH UNAME-S RTREE sudo|env ORG GROUP RDP|-
      SSH_H_WORKPLACE_REPOS : GROUP NAME PATH
      SSH_H_WORKPLACE_LTREE : The location of local repositories.
    
    Commands:
    
      show     Show configuration.
      mkdir    Create directory.
      mount    Mount directory.
      umount   Umount directory.
      link     Link LDIR/ORG in ~/workman
      repos    List repositories for the user.
      wtrees   Create worktrees.
      rdp      Connect by RDP.
    
    Environment variables: SSH_H_WORKPLACE{,_REPOS,_LTREE}

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
