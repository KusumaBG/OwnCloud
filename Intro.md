# Introduction
ownCloud is an open source file synchronization and share software. This software caters to different types of users from free ownCloud Server edition users, to large enterprises and service providers operating the ownCloud Enterprise Subscription. ownCloud provides a safe, secure, and compliant file synchronization and sharing solution on servers that you control.
## Known Differences in ownCloud 10.0.10
ownCloud version 10.0.10 now has the following noteworthy changes:
*	Supports PHP 7.2
*	Provides new local user creation flow
*	Enables use of HTTP API for search functionality
*	Ensures enhanced security using native Brute-Force protection
*	Provides improved reliability for file upload feature
*	Provides option to prevent sharing with an undesirable group
*	Enables system administrators to reset or change password

For details about more changes, see Release Notes in [ownCloud Server Administration Guide](https://doc.owncloud.com/server/10.0/admin_manual/release_notes.html).
## Features of ownCloud 10.0.10
Some of the key features of ownCloud 10.0.10 are as follows:
*	Enables users to add the app to the Android homescreen
*	Compatible with PHP 7.1
*	Provides support for MySQL 4-byte UTF8: (utf8mb4 for example, Emoticons)  
*	Admin, personal pages, and app management are now merged together into a single "Settings" entry
*	Admin page displays the output of the server's status.php
*	Enables using email address for password recovery
*	Provides ability to disable password reset
*	Supports Redis Cluster
*	ownCloud log entry reorder
*	ownCloud log file rules to split into separate files
*	occ scanner optimized memory usage for large scans by using autocommits
*	Third party apps are not disabled anymore when upgrading

For more details, see [ownCloud 10.0 Features](https://github.com/owncloud/core/wiki/ownCloud-10.0-Features) page.
# System Requirements
Platform |	Options
----------|---------
Operating System |	Centos Linux 6 and 7,  Debian 7 and 8, Fedora 27 and 28, Red Hat Enterprise Linux 6 and 7, SUSE Linux Enterprise Server, 12 with SP1, SP2 and SP3, openSUSE Tumbleweed and Leap 15.0, 42.3, Ubuntu 16.04 and 18.04
Database	MySQL or MariaDB 5.5+ | Oracle 11g, PostgreSQL, SQLite
Web server | Apache 2.4 with prefork Multi-Processing Module (MPM) and mod_php
PHP Runtime*	| 5.6, 7.0, 7.1, and 7.2 (most preferred)
## Memory Requirements
Memory requirements for running an ownCloud server varies depending on the numbers of users and files, and volume of server activity. ownCloud requires a minimum of 128MB RAM, however, a minimum of 512MB is recommended.
## Database Requirements
Note the following requirements if you are running ownCloud together with a MySQL or MariaDB database:
*	Disabled or BINLOG_FORMAT = MIXED or BINLOG_FORMAT = ROW configured Binary Logging (See: [MySQL / MariaDB with Binary Logging Enabled](https://doc.owncloud.com/server/10.0/admin_manual/configuration/database/linux_database_configuration.html#db-binlog-label))
*	InnoDB storage engine (The MyISAM storage engine is not supported, see: [MySQL / MariaDB storage engine](https://doc.owncloud.com/server/10.0/admin_manual/configuration/database/linux_database_configuration.html#db-storage-engine-label))
* “READ COMMITTED” transaction isolation level (See: [MySQL / MariaDB “READ COMMITTED” transaction isolation level](https://doc.owncloud.com/server/10.0/admin_manual/configuration/database/linux_database_configuration.html#db-transaction-label))
See [deployment considerations](https://doc.owncloud.com/server/10.0/admin_manual/installation/deployment_considerations.html) and [deployment recommendations](https://doc.owncloud.com/server/10.0/admin_manual/installation/deployment_recommendations.html) for other considerations and recommendations.
