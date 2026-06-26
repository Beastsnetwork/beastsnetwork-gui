# Beastsnetwork GUI

Copyright (c) 2014-2024, The Beastsnetwork Project

## Table of Contents
  * [Development resources](#development-resources)
  * [Vulnerability response](#vulnerability-response)
  * [Introduction](#introduction)
  * [About this project](#about-this-project)
  * [Supporting the project](#supporting-the-project)
  * [License](#license)
  * [Translations](#translations)
  * [Installing the Beastsnetwork GUI from a package](#installing-the-beastsnetwork-gui-from-a-package)
  * [Compiling the Beastsnetwork GUI from source](#compiling-the-beastsnetwork-gui-from-source)

## Development resources

- Web: [beastsnetwork.win](https://beastsnetwork.win)
- Mail: [dev@beastsnetwork.win](mailto:dev@beastsnetwork.win)
- Github: [https://github.com/Beastsnetwork/beastsnetwork-gui](https://github.com/Beastsnetwork/beastsnetwork-gui)
- IRC: [#beastsnetwork-gui on Libera](irc://irc.libera.chat/#beastsnetwork-gui)
- Translation platform (Weblate): [translate.beastsnetwork.win](https://translate.beastsnetwork.win)

## Vulnerability response

- Our [Vulnerability Response Process](https://github.com/Beastsnetwork/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) encourages responsible disclosure
- We are also available via [HackerOne](https://hackerone.com/beastsnetwork)

## Introduction

Beastsnetwork is a private, secure, untraceable, decentralised digital currency. You are your bank, you control your funds, and nobody can trace your transfers unless you allow them to do so.

**Privacy:** Beastsnetwork uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain absolutely private by default.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25 word mnemonic seed that is only displayed once, and can be written down to backup the wallet. Wallet files are encrypted with a passphrase to ensure they are useless if stolen.

**Untraceability:** By taking advantage of ring signatures, a special property of a certain type of cryptography, Beastsnetwork is able to ensure that transactions are not only untraceable, but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.

## About this project

This is the GUI for the [core Beastsnetwork implementation](https://github.com/Beastsnetwork/beastsnetwork). It is open source and completely free to use without restrictions, except for those specified in the license agreement below. There are no restrictions on anyone creating an alternative implementation of Beastsnetwork that uses the protocol and network in a compatible manner.

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews.

## Supporting the project

Beastsnetwork is a 100% community-sponsored endeavor. If you want to join our efforts, the easiest thing you can do is support the project financially. Donation information will be added soon.

GUI development funding and/or some supporting services are also graciously provided by sponsors.

## License

See [LICENSE](LICENSE).

## Translations

Do you speak a second language and would like to help translate the Beastsnetwork GUI? Check out Weblate, our localization platform, at [translate.beastsnetwork.win](https://translate.beastsnetwork.win/). Choose the language and suggest a translation for a string or review an existing one.

Status of the translations:  

<a href="https://translate.beastsnetwork.win/engage/beastsnetwork/?utm_source=widget">
<img src="https://translate.beastsnetwork.win/widgets/beastsnetwork/-/gui-wallet/horizontal-auto.svg" alt="Translation status" />
</a>

## Installing the Beastsnetwork GUI from a package

Packages are available for various distributions. Packaging for your favorite distribution would be a welcome contribution!

## Compiling the Beastsnetwork GUI from source

*Note*: Qt 5.12 is the minimum version required to build the GUI.

See the [compilation guide](https://github.com/Beastsnetwork/beastsnetwork-gui/blob/master/docs/compiling.md) for detailed build instructions for your platform.
