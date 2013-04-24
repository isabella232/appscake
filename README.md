![AppScale Logo](http://www.appscale.com/img/appscale-logo.png)

#Appscake - Web Frontend for AppScale Tools #

## About ##

"AppsCake makes deploying AppScale a piece of cake"

AppsCake is a simple and lightweight web application that allows users to
interact with AppScale tools over the web. This way even those users who
are not familiar with general cloud principles or those who are not
comfortable working with a traditional command line interface can get
started with deploying AppScale clouds and AppScale cloud applications.

AppsCake has been developed using the python programming language and is
based on Django. 

## Prerequisites ##
- Python 2.7
- Django 1.5 (get the tar ball here: https://www.djangoproject.com/download/1.5.1/tarball/)
- Git

# Install process ##
Run ```bash get_tools.sh```.

### For Mac OSX ###
Install the tools by going into appscale-tools/osx
```bash appscale_install.sh```

### For Debian based systems ###
Install the tools by going into appscale-tools/debian and running
```bash appscale_install.sh```
If your default installation of python is not 2.7, then you will have to 
install boto, SOAPpy, yaml, and termcolor by hand for 2.7.

Fetching source code of dependencies:
```
wget https://pypi.python.org/pypi/termcolor
git clone https://github.com/boto/boto.git
wget http://pyyaml.org/download/pyyaml/PyYAML-3.10.tar.gz
https://pypi.python.org/packages/source/s/setuptools/setuptools-0.6c11.tar.gz#md5=7df2a529a074f613b509fb44feefe74e
git clone https://github.com/kiorky/SOAPpy.git
```

### Other distros ###
See the install script for MacOSX for the required dependencies. Contact us if you 
have problems at: support@appscale.com or visit our IRC channel #appscale on freenode.net.

License
-------
This software is licensed under the [New BSD License][BSD]. For more
information, read the file ``LICENSE``.

[BSD]: http://opensource.org/licenses/BSD-3-Clause
