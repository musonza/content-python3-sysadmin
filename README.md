# Python 3 for System Administrators

The scripts written throughout the Python 3 for Systems Administrators
course videos. This repository also includes the helper script to
easily create a database server to follow along with the final section of the
course.

* [Helper files](/helpers)
* [Course Scripts](/scripts)
* [Final Project (pgbackup)](/pgbackup)

## Install Python from source

```bash
$ sudo su -
[root] $ yum groupinstall -y "development tools"
[root] $ yum install -y \
  libffi-devel \
  zlib-devel \
  bzip2-devel \
  openssl-devel \
  ncurses-devel \
  sqlite-devel \
  readline-devel \
  tk-devel \
  gdbm-devel \
  db4-devel \
  libpcap-devel \
  xz-devel \
  expat-devel

[root ] $ cd /usr/src
[root ] $ wget http://python.org/ftp/python/3.6.4/Python-3.6.4.tar.xz
[root ] $ tar xf Python-3.6.4.tar.xz
[root ] $ cd Python-3.6.4
[root ] $ ./configure --enable-optimizations
[root ] $ make altinstall
[root ] $ exit
```
