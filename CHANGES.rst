Changelog
=========

master
------

* Rewrite imports from _io module to io. (#1, merge of #32). Thanks Radhans
  Jadhao.

* Add Config.cli_context() as a hook for custom CLI initialization and cleanup
  logic (#28; merge of #29). Thanks Rodney Folz.

17.12.2
-------

* Exclude "frozen importlib" functions in default code filter.

* Fix passing args to script run with ``monkeytype run`` (#18; merge of
  #21). Thanks Rodney Folz.

* Fix generated annotations for NewType types (#22; merge of #23). Thanks
  Rodney Folz.

17.12.1
-------

* Fix using MonkeyType outside a virtualenv (#16). Thanks Guido van Rossum for
  the report.

17.12.0
-------

* Initial public version.
