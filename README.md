# Why create this project ?

As shown in https://github.com/composer/packagist/commit/86244a3695fcaaac9c5ba4257a4314eae1c6d981, the official Composer project is no longer a purely technical open source project. It has mixed some people's political views and tried to force everyone to accept his political views. I don't support war, nor any country. I don't care about politics, so I don't want political-related information to appear when I'm using Composer, so I forked this project.

# How to use a CLEAN Composer phar ?

run `wget https://github.com/open-composer/composer/releases/download/2.2.9/composer.phar && sudo mv composer.phar /usr/local/bin/composer`

> Notice: The `self-update` command is not supported at the moment, it may revert to the politicized version after running.

Composer - Dependency Management for PHP
========================================

Composer helps you declare, manage, and install dependencies of PHP projects.

See [https://getcomposer.org/](https://getcomposer.org/) for more information and documentation.

[![Continuous Integration](https://github.com/composer/composer/workflows/Continuous%20Integration/badge.svg?branch=main)](https://github.com/composer/composer/actions)

Installation / Usage
--------------------

Download and install Composer by following the [official instructions](https://getcomposer.org/download/).

For usage, see [the documentation](https://getcomposer.org/doc/).

Packages
--------

Find packages on [Packagist](https://packagist.org).

Community
---------

Follow [@packagist](https://twitter.com/packagist) or [@seldaek](https://twitter.com/seldaek) on Twitter for announcements, or check the [#composerphp](https://twitter.com/search?q=%23composerphp&src=typed_query&f=live) hashtag.

For support, Stack Overflow offers a good collection of
[Composer related questions](https://stackoverflow.com/questions/tagged/composer-php), or you can use the [GitHub discussions](https://github.com/composer/composer/discussions).

Please note that this project is released with a
[Contributor Code of Conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct/).
By participating in this project and its community you agree to abide by those terms.

Requirements
------------

PHP 5.3.2 or above (at least 5.3.4 recommended to avoid potential bugs)

Authors
-------

- Nils Adermann  | [GitHub](https://github.com/naderman)  | [Twitter](https://twitter.com/naderman) | <naderman@naderman.de> | [naderman.de](https://naderman.de)
- Jordi Boggiano | [GitHub](https://github.com/Seldaek) | [Twitter](https://twitter.com/seldaek) | <j.boggiano@seld.be> | [seld.be](https://seld.be)

See also the list of [contributors](https://github.com/composer/composer/contributors) who participated in this project.

Security Reports
----------------

Please send any sensitive issue to [security@packagist.org](mailto:security@packagist.org). Thanks!

License
-------

Composer is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Acknowledgments
---------------

- This project's Solver started out as a PHP port of openSUSE's
  [Libzypp satsolver](https://en.opensuse.org/openSUSE:Libzypp_satsolver).
