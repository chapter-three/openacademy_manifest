Open Academy Manifest
=================
This repository contains manifest information to be used by the
Repo version control tool - http://en.wikipedia.org/wiki/Repo_(script). 

In order to get the latest and greatest from the Open Academy, you need
to install Repo and then run the following commands in your Drupal root:

> repo init -u git://github.com/chapter-three/openacademy_manifest.git

> repo sync

If you want to do development on a branch and have the appropriate
credentials to push code, you run the following comamnd and then use
git normally to pull/push/add/commit code:

> repo start BRANCH_NAME PROJECT_NAME

There is a lot of documentation online about Repo, but two of the best
places to look are here:

* http://source.android.com/source/using-repo.html
* http://source.android.com/source/version-control.html
