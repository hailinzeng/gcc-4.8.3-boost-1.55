gcc-4.8.3-boost-1.55
====================

Bash script to install gcc-4.8.3 and boost-1.55 on CentOS 5.x, CentOS 6.x and Mac OS X.

To use it:

    $ mkdir -p work/gcc
    $ cd work/gcc
    $ git clone https://github.com/hailinzeng/gcc-4.8.3-boost-1.55
    $ cd gcc-4.8.3-boost-1.55
    $ make

For more detailed information see http://joelinoff.com/blog/?p=1514.

Dependency:

    $ yum install -y redhat-lsb wget

It takes a few hours to finish.

Other choice: install devtoolset
====================

    yum -y install centos-release-scl
    yum -y install devtoolset-8-gcc devtoolset-8-gcc-c++ devtoolset-8-binutils

This takes only a few minutes.
