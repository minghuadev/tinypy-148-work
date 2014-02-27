

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

