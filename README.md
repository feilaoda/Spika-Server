Spika-Server
============

[![Build Status](https://api.travis-ci.org/cloverstudio/Spika-Server.png?branch=master,develop)](https://travis-ci.org/cloverstudio/Spika-Server)
[![Coverage Status](https://coveralls.io/repos/cloverstudio/Spika-Server/badge.png?branch=develop)](https://coveralls.io/r/cloverstudio/Spika-Server?branch=develop)

Spika is a full-fledged messenger app under MIT license.  
For any detail please refer our web site.

http://spikaapp.com/

# Development setup


## configure Vagrant.

install required software.

- VirtualBox
- Vagrant 1.3.x+

## boot VM

boot a virtual machine on your workstation.

<pre>
git clone #{this_repo}
cd #{this_repo}
vagrant up
</pre>

## Setup Database

Access to instller for Spika server.

[http://localhost:8080/wwwroot/install](http://localhost:8080/wwwroot/install)

## confirm database is working

Open this url.
[http://localhost:8080/wwwroot/api/](http://localhost:8080/wwwroot/api/)

You will see something like this.

<pre>
{"message":"No token sent","error":"logout"}
</pre>
