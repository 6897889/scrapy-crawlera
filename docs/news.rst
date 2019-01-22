.. _news:

Changes
=======

v1.4.0 (2018-09-20)
-------------------

- Remove X-Crawlera-* headers when Crawlera is disabled.
- Introduction of DEFAULT_CRAWLERA_HEADERS settings.

v1.3.0 (2018-01-10)
-------------------

- Use CONNECT method to contact Crawlera proxy.

v1.2.4 (2017-07-04)
-------------------

- Trigger PYPI deployments after changes made to TOXENV in v1.2.3

v1.2.3 (2017-06-29)
-------------------

- Multiple documentation fixes
- Test scrapy-crawlera on combinations of software used by scrapinghub stacks


v1.2.2 (2017-01-19)
-------------------

- Fix Crawlera error stats key in Python 3.
- Add support for Python 3.6.


v1.2.1 (2016-10-17)
-------------------

- Fix release date in README.


v1.2.0 (2016-10-17)
-------------------

- Recommend middleware order to be ``610`` to run before ``RedirectMiddleware``.
- Change default download timeout to 190s or 3 minutes 10 seconds
  (instead of 1800s or 30 minutes).
- Test and advertize Python 3 compatiblity.
- New ``crawlera/request`` and ``crawlera/request/method/*`` stats counts.
- Clear Scrapy DNS cache for proxy URL in case of connection errors.
- Distribute plugin as universal wheel.
