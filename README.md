NPCoin Core staging tree V1.0.3 
================================

https://www.npcoin.info

Copyright (c) 2018-2019  IT Transfer Sdn Bhd 

[![License][license-badge]][license-page]

[license-page]: LICENSE
[license-badge]: http://img.shields.io/badge/License-MIT-brightgreen.svg



What is NPCoin?
----------------

NPCoin (NPC) is a utility Cryptocurrency.

There are thousands of altcoins, and NPC is one of it. NPC is created to be an utility coin for daily usage, especially for Asean Regions.

### Coin Specs
<table>
<tr><td>Max Coin Supply</td><td>150,000,000 NPC</td></tr>
<tr><td>Algo</td><td>PoS</td></tr>
<tr><td>Average Block Time</td><td>2 Minutes</td></tr>
<tr><td>Maturity</td><td>10 Confirmations</td></tr>
<tr><td>Reward</td><td>0.0001 NPC</td></tr>
<tr><td>P2P port</td><td>13130</td></tr>
<tr><td>RPC port</td><td>23130</td></tr>
<tr><td>Premine</td><td>150,000,000 NPC*</td></tr>
</table>

For more information, as well as an immediately useable, binary version of
the NPCoin client sofware, see https://www.npcoin.info.


Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in same branches. [Tags](https://github.com/npcoincoreteam/npcoin-core/tags) are created to indicate new official,stable release versions of NPCoin Core.

Developers work in their own trees, then submit pull requests when they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a good thing.  Developers should expect to rework and resubmit patches if they don't match the project's coding conventions [coding.txt](/doc/coding.txt) or are controversial.

The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are regularly created to indicate new stable release versions of NPCoin.

Feature branches are created when there are major new features being worked on by several people.

From time to time a pull request will become outdated. If this occurs, and the pull is no longer automatically mergeable; a comment on the pull will be used to issue a warning of closure. The pull will be closed 15 days after the warning if action is not taken by the author. Pull requests closed in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after 15 days from their last activity. Issues closed in this manner will be labeled 'stale'.


### Building & Deploy

See  [readme-qt](/doc/readme-qt.rst) for instructions on building NPCoin QT,the intended-for-end-users, nice-graphical-interface, reference implementation of NPCoin.

See doc/build-*.txt for instructions on building npcoind,the intended-for-services, no-graphical-interface, reference
implementation of NPCoin.

Copy this nodes to your wallet .conf file
If you have problem to sync your wallet with NPCoin blockchain - use the following nodes to fix it.

```
- addnode=64.188.21.223:13130
- addnode=151.106.0.98:13130 
- addnode=155.94.211.29:13130
- addnode=155.94.211.26:13130 
- addnode=111.90.146.123:13130
- addnode=111.90.146.127:13130
- addnode=66.63.162.236:13130
- addnode=209.127.18.168:13130
```

Testing
-------

Testing ([README](/src/test/README)) and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.


### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.

License
-------

NPCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Disclaimer
-------------------

NPCoin project is The Future Financial System Currency.
Invest at your own risk.

Report An Issues 
================

This is the first [release](https://github.com/npcoincoreteam/npcoin-core/releases) of NPCoin Core if you find any bugs, Please report using the issue tracker on GitHub:

https://github.com/npcoincoreteam/npcoin-core/issues
