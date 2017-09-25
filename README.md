Demo project for Codeception
============================

This is demo project for examples of unit testing with [Codeception](http://codeception.com/) full-stack framework.

Install Codeception to project
------------------------------
`$ composer require --dev "codeception/codeception"`

Codeception commands
--------------------

`$ ./vendor/bin/codecept bootstrap` - creates files for tests

`$ ./vendor/bin/codecept generate:test unit DemoTest` - generates unit test-case with name `DemoTest`

`$ ./vendor/bin/codecept build` - generates files for tests running

`$ ./vendor/bin/codecept run unit` - run unit tests

Useful links
------------

[Assert methods](http://codeception.com/docs/modules/Asserts)