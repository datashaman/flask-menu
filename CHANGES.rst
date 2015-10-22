Changes
=======

Version 0.4.0 (released 2015-07-23)

- Flask-Classy support and automatic detection of parameters for
  `url_for`.  (#33)
- Improves how the default active state of items is determined.  (#32)
- Adds `.dockerignore` excluding among others Python cache
  files.  This solves a problem when using both `tox` and `docker` to run
  the test suite on the same host.  (#29)

Version 0.3.0 (released 2015-03-17)

- New method `has_active_child(recursive=True)` in `MenuEntryMixin`.  (#25)
- Fixed documentation of blueprint example. (#21)
- Configuration for Docker and demo app. (#22 #29)
- Fixed template example and added code block types.  (#14)

Version 0.2.0 (released 2014-11-04)

- The Flask-Menu extension is now released under more permissive
  Revised BSD License. (#12)
- New support for additional keyword arguments stored as `MenuItem`
  attributes. (#19)
- Richer quick-start usage example. (#16)
- Support for Python 3.4. (#6)
- Documentation improvements. (#3)

Version 0.1.0 (released 2014-06-27)

- Initial public release.