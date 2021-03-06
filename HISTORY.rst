.. :changelog:

History
-------


0.4.1 (2017-06-03)
------------------
* numerous package upgrades
* fix typos

0.4.0 (2017-05-02)
------------------
* add support for remote host - #72
* add asyncio trove classifiers - #68

0.3.3 (2017-03-31)
------------------
* fix type for port and aux-port - #59
* allow empty response body - #56
* uprev numerous packages, nothing significant
* improve runserver shutdown logic
* db settings without message example - #53

0.3.2 (2017-03-22)
------------------
* fix ``prepare_database`` for fresh ``start`` projects

0.3.1 (2017-03-22)
------------------
* correct aiohttp version in ``start`` template

0.3.0 (2017-03-21)
------------------
* **breaking change**: v0.3.0 only supports ``aiohttp>=2.0.0``
* **breaking change**: ``runserver`` not longer works with ``settings.yml`` config files, environment variables
  are now used in it's place
* clean up config arguments
* refactoring to support aiohttp 2

0.2.1 (2017-03-16)
------------------
This will be the final version which supports ``aiohttp < 2``

* correct setup and readme links
* pin aiohttp version to ``<2.0``

0.2.0 (2017-02-19)
------------------
* allow "app_factory" to be just a plain ``aiohttp.Application`` (or a function creating an application as before)
* fix compatibility with aiohttp 2.0.0a - still not working fully with latest aiohttp

0.1.4 (2017-02-11)
------------------
* resolve conflicts with aiohttp 1.3.0
* test build matrix to test with all recent version of aiohttp and master
* dependency updates
* fix for ``fmt_size`` with size ``None``

0.1.3 (2017-01-18)
------------------
* add ``app.cleanup()`` to pre-checks
* add ``--pre-check/--no-pre-check`` flag

0.1.2 (2017-01-11)
------------------
* move to ``grablib`` for downloading ``livereload.js``
* update  aiohttp-session from 0.7.1 to 0.8.0 (#9)
* update aiopg from 0.12.0 to 0.13.0 (#11)
* update aiohttp-jinja2 from 0.8.0 to 0.13.0 (#12)
* fix formatting and typos in numerous commends and start's README
* fix template variable in ``requirements.txt``
* check tag matches ``version.VERSION`` before a release

0.1.1 (2017-01-06)
------------------
* fix template variables so ``settings.yml`` include db connection settings and ``requirements.txt`` is correct
* fix ``requirements.txt`` template to be compatible with pyup
* add basic help to readme
* allow environment variable substitution into settings

0.1.0 (2017-01-05)
------------------
First proper release.
