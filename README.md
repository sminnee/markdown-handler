Markdown Handler
================

This little script adds an Apache handler that lets you view Markdown files with a .md extension
more prettily on your webserver.

It's based on a PHP Markdown implementation by [Michel Fortin](http://www.michelf.com/).

Installation
------------

 * Copy .htaccess to your root, or update your httpd.conf file with its contents, if you prefer.
 * Copy the markdown directory into your webroot.

Now visit a .md file on your webserver; you should see it as properly styled HTML.