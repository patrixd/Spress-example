Spress Example
==============
Blog site generated by [Spress](https://github.com/yosymfony/Spress)

How to build
------------
You need download [Spress](https://github.com/yosymfony/Spress) and install
verdors with composer `$ composer.phar update`.

Get Spress-example:

```
$ git clone https://github.com/yosymfony/Spress-example.git
$ cd Spress-example
$ spress-directory/bin/spress site:build
```
The result site will be save in `_site/` directory.

Run
---
The best way to see your result is use the PHP built-in server:

```
$ cd Spress-example
$ php -S localhost:8080 -t _site
```