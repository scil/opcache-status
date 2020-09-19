OPcache Status  [![Packagist](http://img.shields.io/packagist/v/rlerdorf/opcache-status.svg)](https://packagist.org/packages/rlerdorf/opcache-status)
---------------

A one-page opcache status page for the PHP 5.5 opcode cache.

You don't need the opcode cache installed to help out with this.
See the data-sample.php file for a dump of the data.

I know it is rather ugly, so please spruce it up. But I would like
to keep it relatively small and to a single file so it is easy to 
drop into a directory anywhere without worrying about separate css/js/php
files.

[![Screenshot](https://raw.githubusercontent.com/jamesrwhite/opcache-status/improve-readme/screenshot.png)](https://raw.githubusercontent.com/jamesrwhite/opcache-status/improve-readme/screenshot.png)

## Change log

### v0.2.0

from: https://github.com/LC43/opcache-status

- Fixed warnings when opcache was off
- Improve clear cache feedback
- ~~Improve flush cache[https://github.com/LC43/opcache-status/commit/5a9a87d42ab65c054726ada1681eaeb34b44feb6]~~ not mixed into here 

### TODO

 - The ability to sort the list of cached scripts by the various columns
 - A better layout that can accommodate more of the script data without looking cluttered
 - A tuning suggestion tab (need to add a couple of things to the opcache output first though)

