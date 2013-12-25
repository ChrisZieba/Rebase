Rebase
======

Rebase is a quick way to download and extract data from text files, then import them into your own database. The formats used in the text files are not standard delimited, and thus are parsed first according to configuration settings, and imported into your database table.

Packages Needed
---------------

- psycopg2 (As of right now only Postgres is supported)


Usage
-----
Set your local configuration variables in config.py and then run

	$ python rebase.py

Licence
-------

Rebase is released under the [MIT license](http://opensource.org/licenses/MIT).