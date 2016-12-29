# install-MySQLdb-for-python2.7-in-ubuntu
T he ubuntu has installed two kinds Of python: python 2.7 and python 2.6, and the python 2.6 is default, I want to install MySQLdb for python2.7

1. unzip
   unzip MySQL-python-1.2.5.zip
   
2. install setuptools
wget --no-check-certificate https://bootstrap.pypa.io/ez_setup.py
/usr/bin/python2.7 ez_setup.py --insecure

3. install MySQLdb
 cd /home/user/MySQL-python-1.2.5
 /usr/bin/python2.7 setup.py install
 
 reference:
 https://pypi.python.org/pypi/setuptools#unix-wget;
 https://pypi.python.org/pypi/MySQL-python/1.2.5;(download MySQL-python-1.2.5.zip (md5))
 
