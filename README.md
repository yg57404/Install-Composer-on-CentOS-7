# Install-Composer-on-CentOS-7
Install Composer on CentOS 7


Introduction:

Composer is a tool for dependency management in PHP. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.

Requirements:

CentOS 7
cURL
PHP (including php-cli)

Installation:
The installation process of Composer is relatively simple. First, let's get in the good habit of updating our server.

    sudo yum -y update

Switch into the temp directory.

    cd /tmp

Install Composer using cURL

    sudo curl -sS https://getcomposer.org/installer | php

Want to make Composer globally accessible?

    mv composer.phar /usr/local/bin/composer

Conclusion:
Composer is an essential tool for any PHP developer. It is very easy to install and you will save countless hours over the years automating your dependencies. Happy developing!
