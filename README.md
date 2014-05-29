svn-sublime-text-scripts
========================

Handy little SVN scripts you can use in conjuction with Sublime Text
Tested with svn 1.7.9, other versions may need tweaks

Made by: eduwass@gmail.com

GNU GENERAL PUBLIC LICENSE Version 3

Description
========================
The package contains 7 scripts which do the following:
- svnadd : Adds all unversioned files
- svncommit : Runs diff/patch/export/tests (if wanted) and then commits
- svndeleteunversioned : Deletes all unversioned files
- svndiff : Displays diff on your favourite editor (subl)
- svnexport : Exports to given destination (passed either by parameter or prompted)
- svnmylast : Displays your last commits (use at your own risk, can be very slow)
- svnpatch : Creates patch in given destination (passed either by parameter or prompted)
- svnstatusall : Run it on a dir with a lot of repositories and it will 'svn status' all found repositories
- svnupdateall : Run it on a dir with a lot of repositories and it will update all found repositories

Installation:
========================
Edit these files and make sure you set the variables according to your setup:
- svncommit
- svndiff
- svnmylast
- svnstatusall
- svnupdateall


Aliasing scripts to use them directly from command-line:
========================
If you use bash you can set them up as aliases.
Edit your ~/.bash_aliases file and add a link to each of the scripts (change the path first!):

	alias svnadd='/home/edu/source/scripts/svnadd'
	alias svncommit='/home/edu/source/scripts/svncommit'
	alias svndeleteunversioned='/home/edu/source/scripts/svndeleteunversioned'
	alias svndiff='/home/edu/source/scripts/svndiff'
	alias svnexport='/home/edu/source/scripts/svnexport'
	alias svnmylast='/home/edu/source/scripts/svnmylast'
	alias svnpatch='/home/edu/source/scripts/svnpatch'
	alias svnstatusall='/home/edu/source/scripts/svnstatusall'
	alias svnupdateall='/home/edu/source/scripts/svnupdateall'
