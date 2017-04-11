# SSBSE'17 Challenge Wiki
Wiki aimed at sharing general info about the SSBSE'17 challenge systems. 

Details and CfP of the challenge track can be found at [ssbse17.github.io/challenge/](http://ssbse17.github.io/challenge/)

## LibreOffice

### Code

Source code repo: [github.com/LibreOffice/core](https://github.com/LibreOffice/core)

Code overview: [wiki.documentfoundation.org/Development/Code_Overview](https://wiki.documentfoundation.org/Development/Code_Overview)

Building instructions: [wiki.documentfoundation.org/Development/How_to_build](https://wiki.documentfoundation.org/Development/How_to_build)

Plugin to help developing and debugging LibreOffice from Eclipse: [github.com/LibreOffice/loeclipse](https://github.com/LibreOffice/loeclipse)

Static analysis with CLANG and LLVM: [wiki.documentfoundation.org/Development/Clang_Code_Analysis](https://wiki.documentfoundation.org/Development/Clang_Code_Analysis)

### Testing 

Regression testing guidelines: [wiki.documentfoundation.org/QA/Testing/Regression_Tests](https://wiki.documentfoundation.org/QA/Testing/Regression_Tests)

C++ unit testing: [wiki.documentfoundation.org/Development/Unit_Tests](https://wiki.documentfoundation.org/Development/Unit_Tests)

Python unit testing: [wiki.documentfoundation.org/Development/Python_Unit_Tests](https://wiki.documentfoundation.org/Development/Python_Unit_Tests)

Code coverage report: [lcov.libreoffice.org](http://lcov.libreoffice.org/)

Computing code coverage: [wiki.documentfoundation.org/Development/Lcov](https://wiki.documentfoundation.org/Development/Lcov)

### Trackers

Gerrit code reviews: [gerrit.libreoffice.org](https://gerrit.libreoffice.org)

Issues/Bugs tracker: [bugs.documentfoundation.org](https://bugs.documentfoundation.org/describecomponents.cgi?product=LibreOffice&format=guided)

## SQLite

SQLite uses [Fossil](https://www.fossil-scm.org/), a distributed version control system that was specifically designed to support SQLite development. 

Project repo: [sqlite.org/src/tree](https://www.sqlite.org/src/tree)

### Code

Source code: [sqlite.org/src/dir?name=src](https://www.sqlite.org/src/dir?name=src)

SQLite architecture: [sqlite.org/arch.html](http://www.sqlite.org/arch.html)

Building instructions: [sqlite.org/src/tree?ci=trunk](https://www.sqlite.org/src/tree?ci=trunk) under **Compile**

Commits timeline: [sqlite.org/src/timeline](https://www.sqlite.org/src/timeline?y=ci)

### Testing

SQLite claims to be extensively tested, where the whole test suite has 745 times more code than the core SQLite system. Several testing strategies are employed on SQLite, including but not limited to: Out-of-memory tests, I/O error tests, Crash and power loss tests, mutation testing and Valgrind analysis. However, most of this test suite is claimed to be proprietary. 

SQLite provides a basic test suite to be used at development time: [sqlite.org/src/dir?name=test](https://www.sqlite.org/src/dir?name=test)

For more details on SQLite tetsing in general, please refer to (sqlite.org/testing.html)[http://www.sqlite.org/testing.html]

### Trackers

SQLite employs a strict and detailed bug reporting and feature request system, where all reports/requests are carefully reviewed by developers before they are added to the list. More details at [sqlite.org/src/wiki?name=Bug+Reports](https://www.sqlite.org/src/wiki?name=Bug+Reports).

List of all bugs and feature requests: [sqlite.org/src/rptview?rn=1](http://www.sqlite.org/src/rptview?rn=1)

## Guava

One may find below relevant links for the challenge track; however, please refer to Guava's full [wiki](https://github.com/google/guava/wiki) for more details.

### Code

Source code repo: [github.com/google/guava](https://github.com/google/guava)

API JavaDoc: [google.github.io/guava/releases/21.0/api/docs/](http://google.github.io/guava/releases/21.0/api/docs/)

### Testing

Test suite: [guava-testlib](https://github.com/google/guava/tree/master/guava-testlib) and [guava-tests](https://github.com/google/guava/tree/master/guava-tests)

### Trackers

Issue tracking: [github.com/google/guava/issues](https://github.com/google/guava/issues)

General discussion forum: [groups.google.com/forum/#!forum/guava-discuss](https://groups.google.com/forum/#!forum/guava-discuss)

## Flask

For the full documentation of Flask please refer to [flask.pocoo.org/docs/0.12/](http://flask.pocoo.org/docs/0.12/)

### Code

Source code repo: [github.com/pallets/flask](https://github.com/pallets/flask)

### Testing

Test suite: [github.com/pallets/flask/tree/master/tests](https://github.com/pallets/flask/tree/master/tests)

Flask provide guidelines to [run the test suite](https://github.com/pallets/flask/blob/master/CONTRIBUTING.rst#running-the-testsuite) and [compute test coverage](https://github.com/pallets/flask/blob/master/CONTRIBUTING.rst#running-test-coverage)

### Trackers

Issue tracking: [github.com/pallets/flask/issues](https://github.com/pallets/flask/issues)
