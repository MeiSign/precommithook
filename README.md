precommithook
=============

This is a git precommithook that runs sbt test before a commit and aborts the commit if tests fail

How to use it?
==============
Put the 'sbt' script in your project root directory to make sure the tests can be run no matter if a local sbt installation is available or not.

Put the 'precommit' script in the '.git/hooks' directory of your project. This will enable the hook.
