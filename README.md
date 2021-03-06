# Example Geb and Grails 2 Project

[![Build Status][build_status]](https://drone.io/github.com/geb/geb-example-grails/latest)

# Description

This is an example of using Geb to functionally test Grails applications. It shows the use of Spock and JUnit 4 tests.

Grails Wrapper is a part of this example which means that you don't need to have Grails installed on your machine. It also means that the Grails version used to run it will be the one this project is tested with.

The build is setup to work with Firefox.

# Usage

To run the tests you can execute:

    ./grailsw test-app functional:

Replace `./grailsw` with `grailsw` in the above examples if you're on Windows using `cmd.exe` (with powershell, the above statement should work).

## Questions and issues

Please ask questions on [Geb user mailing list][mailing_list] and raise issues in [Geb issue tracker][issue_tracker].


[build_status]: https://drone.io/github.com/geb/geb-example-grails/status.png "Build Status"
[mailing_list]: https://groups.google.com/forum/#!forum/geb-user
[issue_tracker]: https://github.com/geb/issues/issues
