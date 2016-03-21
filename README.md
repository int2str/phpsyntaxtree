# phpSyntaxTree
_phpSyntaxTree_ is a web application that creates syntax tree graphs 
from phrases entered in labelled bracket notation. phpSyntaxTree 
generated graphs can be used in linguistic homework, assignments 
and other documents.

See the COPYING file for license information.

_phpSyntaxTree_ can be used on the web, without installing any 
software at http://ironcreek.net/phpsyntaxtree .

## Local Installation
If you prefer to run phpSyntaxTree locally, or on your own server,
simply follow the instructions below.

### Requirements
- Web server with support for .htaccess overwritable mime types
  like Apache, nginx etc.
- PHP 4.3+/PHP 5+ with support for the GD library and TrueType
  font support (http://php.net)

### Installation
Unpack the archive into a suitable directory on your web server.
Be sure that the directory is configured to allow configuration
overwrites using a .htaccess file.

Change the permissions on the phpsyntaxtree/var/ directory to be
writable by the web server user (ex. apache, nobody, or similar).
phpSyntaxTree will create a counter.dat file there as well as
other temporary files.

## Support, Questions etc.
If you encounter any bugs or problems, please file a bug report
on the phpSyntaxTree project page:
http://github.com/int2str/phpsyntaxtree

Or, send email to andre@ironcreek.net
