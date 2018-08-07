
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
###### Masternode-Collateral: 3000 QUAR
###### 2 Day Instamine protection: Block Reward = 5 QUAR
###### Dev-fund: 0.5%

POW/Masternode Distibution
-------------------
###### Initial: 50/50
###### After-6-months: 25/75

Addnodes
--------
your wallet should connect and sync automaticly although if it dosn't try adding these nodes into the wallet configueration file using `addnode=(selected ip)
###### 206.189.26.208
###### 95.179.153.42
###### 37.187.144.227
###### 145.239.244.130
###### 37.187.144.227
###### 195.164.246.183
###### 25.114.9.84
###### 46.105.55.113
###### 173.212.247.217

Ports
-----
Mainet:
###### Defult: 39393
###### RPC: 39394


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
