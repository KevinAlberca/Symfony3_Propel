Symfony Propel Edition
========================

This is my configuration to use Symfony 3 with Propel ORM.

To use Propel ORM instead of Doctrine ORM/DBAL, you may edit ``app/config.yml`` and ``app/AppKernel.php`` and require a package in your ``composer.json``  file.

But, this repository is here, because it's already did, so just fork/clone the repository
Then, add a line to your ``app/config/parameters.yml`` and add this line to ``parameters`` block :

``
database_driver: mysql
``

Or replace ``mysql`` with other sql server

For your database schema, the file of propel is
``
/src/AppBundle/Resources/config/propel/schema.xml
``

Which differences ?
--------------

* Doctrine ORM/DBAL replace with Propel ORM
