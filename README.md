
builds
======

Run these commands:

 * python setup.py tinypy pygame
  * it fails due to SDL.h

 * python setup.py tinypy 
 * python setup.py tinypy math
  * these do work. see log1...

 * python setup.py tinypy math
  * do this from a clean dir. see log2...

 * python setup.py tinypy boot
 * python setup.py tinypy math boot
  * these do work compiling a lot more
 

tags
====

    base01 before branching build01


git tips
========

Example with chromeos branch checkout and push:

    clone kernel-next and checkout origin/chromeos-3.8
    "git branch"     ---this shows detatched head
    "git reflog"     ---this shows ref history
    create local branch: "git checkout -b chromeos-3.8"
    switch to master branch: "git checkout master"

Push a specific ref:

    git push origin 8d38ead:refs/heads/master

Push a branch:

    switch to chromeos-3.8 branch. set push.default current. push.


create work directory
=====================

cp -a trunk148 work


init trunk148 directory
=======================

cp -a .../tinypy-snapshot/tinypy/trunk trunk148

