[![Brixcoin](brixcoin_logo_horizontal.png)](https://www.brixco.in)


Brixcoin6.0 (0.12.3.2)
======================

Master - [![Build Status](https://travis-ci.org/awsafrica/brixcoin6.0.svg?branch=master)](https://travis-ci.org/awsafrica/brixcoin6.0) Dev - [![Build Status](https://travis-ci.org/awsafrica/brixcoin6.0.svg?branch=Dev)](https://travis-ci.org/awsafrica/brixcoin6.0) - DISCORD [![Discord](https://img.shields.io/discord/446594952969846785.svg)](https://discord.gg/KFNFn2H) - ISSUES [![GitHub issues](https://img.shields.io/github/issues/awsafrica/brixcoin6.0.svg)](https://github.com/awsafrica/brixcoin6.0/issues)

Website: https://www.brixco.in<br>
Explorer: http://explore.brixco.in<br>
Mining Pool: http://mine.wegolise.co.za<br>
Discord Channel: https://discord.gg/KFNFn2H<br>
Facebook: https://www.facebook.com/brixcoin<br>
Twitter: https://twitter.com/@brixcoin

What is Brixcoin?
----------------

Brixcoin is an experimental digital currency that enables anonymous, instant
payments to anyone, anywhere in the world. Brixcoin uses peer-to-peer technology
to operate with no central authority: managing transactions and issuing money
are carried out collectively by the network. Brixcoin Core is the name of the open
source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Brixcoin Core software, see https://www.brixco.in/get-started-with-brix-coin/.


License
-------

Brixcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/awsafrica/brixcoin5.0/tags) are created to indicate new official,
stable release versions of Brixcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Translators should follow the [blog post](https://www.brixco.in/brixcoin-worldwide-collaboration-translations/).
