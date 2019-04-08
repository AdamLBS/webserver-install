# webserver-install
* [Requirements](#system-requirements)
* [Features](#features)
* [Supported versions](#supported-versions)
* [Installing](#installing)
* [Launch](#launch)
* [Updating](#updating)
* [Bugs](#bugs)
* [License](#license)

# Requirements

* Unix-like OS

* curl




# Features 

* Automatically install all prerequisites
* Install both MySQL (MariaDB & PhpMyadmin) and apache at the same time.
* Using the latest stable versions of Apache, MariaDB, PHP and PHPMyAdmin.


# Supported versions
* PHP 7
* Apache 2
* Latest version of MariaDB

# Installing

* **curl** is required to download the script.

* If you are logged in as root 
```bash
curl https://uploads.admlbs.fr/download.php?file=apache --output /usr/bin/apache && chmod 0777 /usr/bin/apache
```

* If it's not the case : 

```bash
sudo curl https://uploads.admlbs.fr/download.php?file=apache --output /usr/bin/apache && chmod 0777 /usr/bin/apache
```

# Launch

* To launch the script and install a server you must use sudo or being root

```bash
apache install
```

* To see all commands please type 

```bash
apache help
```
# Updating

* To update the script you must use sudo or being root

```bash
apache update
```
# Bugs


* Please report all bugs to adam@admlbs.fr


# License

This programm is distribued under GNU General Public License v3.0
