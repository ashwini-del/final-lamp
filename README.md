vim /etc/ssh/sshd_config
vim .ssh/authorized_keys
systemctl restart sshd

When installing LAMP on a Debian-based system, you should choose the versions of Apache, PHP, and MySQL that are available in the official repositories of the distribution. These versions are typically tested and supported by the distribution maintainers and are known to work well together.

For example, on Debian 10 (Buster), the default versions of Apache, PHP, and MySQL are Apache 2.4.38, PHP 7.3.19, and MySQL 8.0.19. These versions are compatible with each other and work well together.

there are version dependencies for Apache, PHP, and MySQL when installing a LAMP stack on Red Hat-based systems. Red Hat provides supported versions of the LAMP stack components through their official repositories.

For example, on Red Hat Enterprise Linux (RHEL) 8, the supported versions of the LAMP stack components are:

Apache HTTP Server 2.4.37
PHP 7.2
MySQL 8.0
These versions have been tested and are supported by Red Hat for use together in a LAMP stack

many Linux distributions, the default MySQL package has been replaced with MariaDB, which is a fork of MySQL that is fully compatible with MySQL commands and APIs. The reason for this is that MySQL was acquired by Oracle Corporation, and some users and developers preferred to use a community-driven alternative.l