Symfony Propel Edition
========================
![Build Status](https://travis-ci.org/symfony/symfony-demo.svg?branch=master)](https://travis-ci.org/symfony/symfony-demo) ~ Version 3.1.2 supported



This is my configuration to use Symfony 3 with Propel ORM.

To use Propel ORM instead of Doctrine ORM/DBAL, you may edit ``app/config.yml`` and ``app/AppKernel.php`` and require a package in your ``composer.json``  file.

But, this repository is here, because it's already did, so just fork/clone the repository
Then, add a line to your ``app/config/parameters.yml`` and add this line to ``parameters`` block :

``
database_driver: mysql
``

Or replace ``mysql`` with other sql server

Which differences ?
--------------

* Doctrine ORM/DBAL replace with Propel ORM
