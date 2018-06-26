                  
                                           ASSIGNMENT AWS DAY1
  

1- installation of awscli 
    root@shumail-Inspiron-N5110:~# apt install python-pip
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  libexpat1-dev libpython-all-dev libpython-dev libpython2.7-dev python-all
  python-all-dev python-dev python-pip-whl python-wheel python2.7-dev
The following NEW packages will be installed:
  libexpat1-dev libpython-all-dev libpython-dev libpython2.7-dev python-all
  python-all-dev python-dev python-pip python-pip-whl python-wheel
  python2.7-dev
  
  root@shumail-Inspiron-N5110:~# pip --version
pip 8.1.1 from /usr/lib/python2.7/dist-packages (python 2.7)


  root@shumail-Inspiron-N5110:~# apt-cache search aws*
alsa-utils - Utilities for configuring and using ALSA
awstats - powerful and featureful web server log analyzer
bonnie++ - Hard drive benchmark suite
checksecurity - basic system security checks
dbus - simple interprocess messaging system (daemon and utilities)
dbus-1-dbg - simple interprocess messaging system (debug symbols)
dbus-1-doc - simple interprocess messaging system (documentation)
dbus-x11 - simple interprocess messaging system (X11 deps)
emacs-goodies-el - Miscellaneous add-ons for Emacs
euca2ools - tools for interacting with AWS API-compatible services
eximon4 - monitor application for the Exim MTA (v4) (X11 interface)
exuberant-ctags - build tag file indexes of source code definitions
fcitx-module-cloudpinyin - Flexible Input Method Framework - cloudpinyin module
fonts-font-awesome - iconic font designed for use with Twitter Bootstrap
fonts-tlwg-sawasdee - Thai Sawasdee font (dependency package)
fonts-tlwg-sawasdee-ttf - Thai Sawasdee TrueType font
freeipmi-tools - GNU implementation of the IPMI protocol - tools
gawk - GNU awk, a pattern scanning and processing language
graphviz - rich set of graph drawing tools
graphviz-dev - transitional package for graphviz-dev rename
awscli - Universal Command Line Environment for AWS

root@shumail-Inspiron-N5110:~# apt-get install awscli
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  docutils-common python3-botocore python3-colorama python3-dateutil python3-docutils python3-jmespath python3-pygments python3-roman
  python3-rsa python3-s3transfer
Suggested packages:
  texlive-latex-recommended texlive-latex-base texlive-lang-french fonts-linuxlibertine | ttf-linux-libertine docutils-doc ttf-bitstream-vera
The following NEW packages will be installed:
  awscli docutils-common python3-botocore python3-colorama python3-dateutil python3-docutils python3-jmespath python3-pygments python3-roman
  python3-rsa python3-s3transfer
0 upgraded, 11 newly installed, 0 to remove and 10 not upgraded.
Need to get 2,609 kB of archives.
Setting up python3-botocore (1.4.70-1~16.04.0) ...
Setting up python3-s3transfer (0.1.9-1~16.04.0) ...
Setting up awscli (1.11.13-1ubuntu1~16.04.0) ...
root@shumail-Inspiron-N5110:~# aws
aws            aws_completer  


