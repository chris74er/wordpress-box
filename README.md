# Wordpress Box

Installation of wordpress via ansible.

Documentation see also
* https://galaxy.ansible.com/oefenweb/wordpress

## Installation on local system for testing

Prerequisites
* [Git](https://git-scm.com/downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

Perform the following steps in the terminal (Linux / macOS) or in the GitBash (Windows).
```
git clone https://github.com/TIBHannover/wordpress-box.git
cd wordpress-box
vagrant up
```

When the installation is complete (a few minutes, depending on the download speed), wordpress can be opened in the browser

<http://192.168.98.117/>

Login

<http://192.168.98.117/wp-admin> => admin / changeme