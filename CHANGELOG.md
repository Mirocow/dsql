## 1.0.1

This is now our first stable release. It features clean-ups from 1.0.0:

* selectTemplate() is replaced with mode()
* upadted docs to use $c->query() instead of "new Query()" (better use pattern)
* added examples for having()
* added method reset()
* added method option()
* Expressionable now receives parent $expression as argument
* documented orExpr(), andExpr()
* documented template_* properties
* improved PSR compatibility
* escapeChar is dropped (too generic)
* introduced softEscape and made escape more strict
* improved and cleaned up documentation
* updated REDAME highlighting our USP

## 1.0.0-alpha2

Mainly clean up the code and added more tests.

## 1.0.0-alpha

Massive release that delivers all the major functionality we will need
for 1.0. We have now the full functionality implemented and a very
extensive test-suite consisting of almost 100 tests.

* Implemented all the basic functionality to start using DSQL.
* new Expression class. Define, build and render any SQL expression.
* refactored Query class. Added field(), where() and other methods.
* Added all documentation: http://dsql.readthedocs.org/
* implemented query rendering
* implemented query execution and fetching
* https://github.com/atk4/dsql/compare/0.1.1...release/1.0.0-alpha
* https://github.com/atk4/dsql/issues?utf8=✓&q=milestone%3A1.0-alpha+is%3Aclosed+is%3Aissue


## 0.1.1

* Added first sample Query.php class
* Added first sample TestQuery.php class
* Integrated with Travis for running tests
* Integrated with codeclimate for code analysis and code coverage
* Integrated badges into README
* Integrated http://dsql.readthedocs.org/

## 0.1.0

* Initial Release
* Bootstraped Documentation (sphinx-doc)
