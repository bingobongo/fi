Fi
==

**Fi** stands for fancy indexing ([Apache Module mod_autoindex](http://httpd.apache.org/docs/2.0/mod/mod_autoindex.html#indexoptions)). It makes default directory listing index pages look nice. Fi is fluid and not fixed. It is a minimalist mod of [Windex](https://github.com/desandro/windex) without PHP or gaudy icons. Fi is clear as gray – a calmative index for stressed eyes. It is optimized for modern Web browsers and mobile devices.


Beware
------

Enabling directory indexes on a live site can be a serious security risk.  
**Be sure to enable Fi only where you want all the child directories and files to be viewable!**


Package Overview
----------------

	/README.md
	/apple-touch-icon.png
	/favicon.ico
	/footer.html
	/header.html
	/htaccess
	/standard.css


Installation
------------

1. Move the entire `fi/` folder into the directory tree (domain root) of your site.
2. Move the file `/htaccess` into the directory where you want to enable directory listing and rename it to `.htaccess`.
3. Now browse to a directory that does not contain an index file and where Fi is enabled in.


License
-------

This software is free to use and modify. You may not charge for or sell this software, nor any derivation of it. If you do modify it, we would love to hear about it. Give us a holler and let us know.

Fi is a mod of [Windex by Scott Evans and David DeSandro](https://github.com/desandro/windex), which is a mod of [Indices by Scott Evans](http://antisleep.com/indices/).
