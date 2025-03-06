# Bitcoin-Proof-of-Stake
LiteBitcoin integration

https://LiteBitcoin.org

What is LiteBitcoin?
LiteBitcoin - new network to Bitcoin transitioned to Proof of Stake. All BTC have been mined using real BTC keys.

LiteBitcoin (LBTC) Bitcoin migrated with Proof of Stake (PoS)

The only way to mine BTCS is to use real BTC keys. Use the 'importprivkey' command to import your BTC key and start mining on the LBTC network. Please move your funds to a safe address before importing your key.

For more information see https://www.litebitcoin.org

License
LiteBitcoin Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

Development Process
The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are created regularly to indicate new official, stable release versions of Bitcoin PoS Core.

The contribution workflow is described in CONTRIBUTING.md and useful hints for developers can be found in doc/developer-notes.md.

Testing
Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.

Automated Testing
Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check. Further details on running and extending unit tests can be found in /src/test/README.md.

There are also regression and integration tests, written in Python, that are run automatically on the build server. These tests can be run (if the test dependencies are installed) with: test/functional/test_runner.py

built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

Manual Quality Assurance (QA) Testing
Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.

About
LiteBitcoin Core integration

Litebitcoin.org
Resources
 Readme
License
 MIT license
Security policy
