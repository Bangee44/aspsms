# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

1.0.5 (in progress)
------------------

1.0.4 (Jun. 2017)
------------------

- [#10](https://github.com/nadar/aspsms/pull/10) Changed server URL to a newer server URL (found here: http://www.aspsms.ch/de/soap/). The older URL uses an outdated SSL connection which can cause errors with newer clients.
Curl errors are now assigned to the response, so exception messages can include the curl error message.

1.0.3 (Feb. 2017)
--------------------

- Minor PHPDoc improvement.
- Minor Code changes and UnitTests.
- Update version constraint.

1.0.2 (Sept. 2017)
-------------------

- Fixed not yet submitted delivery status error Aspsms doesn’t return all parameters when an sms is not submitted yet.
- Fixed account credits reporting Error codes are now no longer interpreted as credits.
- Spelling fixes  Some grammar fixes
- Added new tests and changed exceptions Added new unit tests for commit 4a43a72 and f3be2d1  Streamlined thrown exceptions. Changed Delivery Status „submissionDate“ because it is sometimes already set.
- Longer sms Fixed errors when working with sms longer than 160 chars. Fixed delivery status report with multiple tracking numbers.

Thanks to @mergeMarc 

1.0.1 (Apr. 2016)
--------------------

+ Fixes

1.0.0 (Feb. 2015)
--------------------

+ First release.
