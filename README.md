# MultiPressDev

## Overview

Run all the [WordPress](https://wordpress.org) versions in a single
VM. Allows easily cross version WordPress plugin development or
multi-version testing.  Runs in an Ubuntu 14.04 VM.

## Install

### Prerequisites

You should have git, of course, as well as
[Vagrant](https://www.vagrantup.com/) installed before starting.

### Download and Boot

WARNING - every "provision" or "up" of vagrant will DELETE your WordPress
Database!

1. Clone this repo
1. `cd` into the repo
1. type `vagrant up`
1. Add the /etc/hosts per the vagrant up output
1. Go to http://wordpress.dev in a browser
1. Enjoy


## Roadmap
* Allow automatic install of plugins and themes
* Add more WP versions
* Keep WP versions local instead of downloading from wp.org?

## Release History

### 1.1 - 4.2.15
* Add loop in provision script
* Fix missing "wordpress" folder

### 1.0 - 4.1.15
* Initial release to port from using latest to static versions of WP
* Only support 4.2.1 and 4.1.4 for now
