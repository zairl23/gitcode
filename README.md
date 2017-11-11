GitCode
===================

Create your simple code repository using git on Ubuntu server

Use
===========

First, git clone gitcode into your home root directory

    git clone https://github.com/zairl23/gitcode.git

Then, cd to gitcode project, make create script executable
    
    sudo chmod a+x create

Create a project named test:

    ./create test ~

`test` is your project name, `~` is the code worktree directory, then the bare git repository is placed in `gitcode/repo/test.git`, and the work directory is placed in `~/test`, so the create command meaning is

    ./create project_name work_directory's parent directory

Requirement
============

1. git

    sudo apt-get install git-core

1. ssh and running

    sudo apt-get install openssh-server


