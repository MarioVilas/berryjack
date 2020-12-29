berryjack
=========

berryjack is simple twitter media downloader.
It access to Twitter media timeline via HTTP/JSON instead of Twitter API.

* Not required some script environment, This script use basic UNIX commands only.
* No limit for getting timeline. DO NOT USE FOR LARGE AMOUNTS OF ACCESS. 

Dependency
----------

* Commands:
  * bash
  * wget
  * grep
  * sort
  * uniq
  * sed
  * head
  * test
  * mkdir
  * basename

* Filesystem:
  * /tmp

Setup
-----

Clone the repository and add executable permission to berryjack.

    git clone https://github.com/dyama/berryjack.git
    cd berryjack
    chmod a+x berryjack

Usage
-----

    ./berryjack [options] twitter_name[, ...]

Options
-------

* -l
Only list up media URLs, No download.

* -d dir
Set directory to downloads.

* -u
The media files saved into new directory named 'twitter\_name' in the specified directory.

* -o
Get original size media.

* -U, -P
Twitter account usernema/E-mail and password for login.

License
-------

* MIT License

Author
------

dyama <dyama@member.fsf.org>
http://dyama.org/
