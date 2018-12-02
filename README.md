# OpenLDAP-for-Ubuntu-18.04
**December 2nd, 2018**

With setting up OpenLDAP along with phpldapadmin in **Ubuntu Server 18.04**, you will be faced with deprecation errors revolving around **PHP 7.2**. This tutorial will show exact step-by-steps of how I got around those errors, as a creator on <a href="https://github.com/breisig/phpLDAPadmin">github</a> forked a version of phpldapadmin that eliminates the deprecated commands and allows it to work with the current PHP version.

![Quick Rundown](https://i.imgur.com/r3W4Sz9.jpg)

|**asciinema step-by-step terminal-based tutorial**| 
|-|
<a href="https://asciinema.org/a/HC5e82L9mFl85gnsdZKRBqtKY"><img src="https://asciinema.org/a/HC5e82L9mFl85gnsdZKRBqtKY.png" width="400"/></a>

1) <a href="https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04">https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04</a>
2) <a href="https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-18-04">https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-18-04</a>
3) **>** sudo apt install samba smbldap-tools
4) <a href="https://www.techrepublic.com/article/how-to-install-openldap-on-ubuntu-18-04/">https://www.techrepublic.com/article/how-to-install-openldap-on-ubuntu-18-04/</a>
5) **>** sudo apt-get install php7.2-ldap
6) <a href="https://www.techrepublic.com/article/how-to-install-phpldapadmin-on-ubuntu-18-04/">https://www.techrepublic.com/article/how-to-install-phpldapadmin-on-ubuntu-18-04/</a>
