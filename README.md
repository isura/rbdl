RBDL for ROS
============

This ROS unary stack provides the RBDL dynamics library.
See http://rbdl.bitbucket.org/ for more information.

To pull the latest RBDL version do the following:

1. Download the latest snapshot:
	https://bitbucket.org/rbdl/rbdl/get/default.tar.bz2

2. Make MD5 hash:
	md5sum rbdl-rbdl-4343520f55a9.tar.bz2
	https://help.ubuntu.com/community/HowToMD5SUM
	The file you downloaded will contain the name of the latest commit.
	In this example I downloaded commit 4343520.

3. Save the output hash from md5sum in a file named rbdl-4343520f55a9.tar.bz2.md5sum in your rbdl directory, change the numbers in the middle to match the file you downloaded.

4. Change line 3 of the Makefile to reflect your change:
	VERSION     = 4343520f55a9
