
QUAR-Core 1.0.0
===============================



What is QUAR?
----------------

QUAR is part of the new age of cryptocurrency. It is eco-friendly due to the use of 
masternodes and also provides a base for QUAR-pay, a revolutionary new 3rd party payment
processing system that will pave the way for the mainstream adoption of crpytocurrency

Stats
------
###### Ticker: QUAR
###### Block-Time: 3 minutes
###### Block-Reward: 20 QUAR
###### Max-Supply: 25,000,000 QUAR
###### POW-Hashing-Algo: X16s
###### Instamine-protection: 2 days
###### Masternode-Collateral: 2000 QUAR
###### Dev-fund: 0.5%

Block rewards
-------------
###### 0-1: 125,000
###### 1-144: 5 QUAR
###### 145-1250000: 20

POW/POS Distibution
-------------------
###### Initial: 50/50
###### After-6-months: 25/75
###### After-12-months: 100% POS

Ports
-----
Mainet:
###### Defult: 98987
###### RPC: 97978
Testnet
###### Defult: 9859
###### RPC: 43432

License
-------

QUAR Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate bran
[Tags] are created to indicate new official,l.0.0 stable release versions of QUAR Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows
and Linux, OS X, and that unit and sanity tests are automatically run.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

# QUAR-core