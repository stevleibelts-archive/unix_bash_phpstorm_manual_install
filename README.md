unix_bash_phpstorm_manual_install
=================================

simple bash script collection to easy up upgrading existing phpstorm

usage
-----

* a group called "developer" should exist on your system
* the users who should work with phpstorm should be member of the group "developer"
* download newest version from (jetbrains.com)[http://www.jetbrains.com/phpstorm/download/download_thanks.jsp?os=linux]
* cd into this repostiory
* execute following code in your shell
    bash updatePhpStorm.sh /path/to/new/version/PhpStorm-x.y.z.tar.gz
* for first installation, execute following code in your shell
    sudo ln -s /opt/phpstorm/bin/phpstorm.sh /usr/bin/phpstorm

version history
---------------

* 2014-03-19 - initial commit (its working on my machine)
