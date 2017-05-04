# docker-php-sample

## Overview:

The docker-compose file will bring up tagged versions of nginx and php-fpm running Ubuntu 16.04.  The php app is simply a phpinfo page.

## Usage:

- First run 'sudo _add_host_entry.sh' to add php.local to your /etc/hosts.
- Run 'docker-compose up' to start the php application
- Connect to your app in a browser at http://php.local:4001/.

