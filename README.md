Web Shell Detector
==================
<img src="https://i.ibb.co/MkkGjtD/webshell-1.png" width="100" align="left" style="padding-right: 4px;" /> Web Shell Detector – is a php script that helps you find and identify php/cgi(perl)/asp/aspx shells. Web Shell Detector has a “web shells” signature database that helps to identify “web shell” up to 99%. By using the latest javascript and css technologies, web shell detector has a light weight and friendly interface.

Web Shell Detector is released under the MIT License <http://www.opensource.org/licenses/mit-license.php>

Contributors
------------
emposha

Konko Maji

Detection
---------

  Number of known shells: 604

Requirements
------------
PHP 5.x, OpenSSL (only for secure file submission)

Usage
-----
To activate Web Shell Detector:

1) Upload shelldetect.php and shelldetect.db to your root directory

2) Open shelldetect.php file in your browser

    Example: http://www.website.com/shelldetect.php

3) Use default username & password

    Username: admin
    Password: plutonhacker

4) Inspect all strange files, if some of files look suspicious, send them to http://www.shelldetector.com team. After submitting your file, it will be inspected and if there are any threats, it will be inserted into a “web shell detector” web shells signature database.

5) If any web shells found and identified use your ftp/ssh client to remove it from your web server (IMPORTANT: please be careful because some of shells may be integrated into system files!).

Demo
----

    https://cyberhelper.tech/demo/shelldetect/

Options
-------
 - extension - extensions that should be scanned
 - showlinenumbers - show line number where suspicious function used
 - dateformat - used with access time & modified time
 - langauge - if I want to use other language
 - directory - scan specific directory
 - task - perform different task
 - report_format - used with is_cron(true) file format for report file
 - is_cron - if true run like a cron(no output)
 - filelimit - maximum files to scan (more then 30000 you should scan specific directory)
 - useget - activate _GET variable for easy way to recive tasks
 - authentication  - protect script with user & password in case to disable simply set to NULL
 - remotefingerprint - get shells signatures db by remote
  
