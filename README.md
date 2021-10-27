# GOLDGAMECOIN

Copyright (c) 2020-2021 The GolGameCoin Project.
Portions Copyright (c) 2012-2013 The Cryptonote developers


## Table of Contents
  * [Development resources](#development-resources)
  * [Vulnerability response](#vulnerability-response)
  * [Introduction](#introduction)
  * [About this project](#about-this-project)
  * [Supporting the project](#supporting-the-project)
  * [License](#license)
  * [Translations](#translations)
  * [Installing the Monero GUI from a package](#installing-the-monero-gui-from-a-package)
  * [Compiling the Monero GUI from source](#compiling-the-monero-gui-from-source)
    + [Building Reproducible Windows static binaries with Docker (any OS)](#building-reproducible-windows-static-binaries-with-docker-any-os)
    + [Building Reproducible Linux static binaries with Docker (any OS)](#building-reproducible-linux-static-binaries-with-docker-any-os)
    + [Building Android APK with Docker (any OS) *Experimental*](#building-android-apk-with-docker-any-os-experimental)
    + [Building on Linux](#building-on-linux)
    + [Building on OS X](#building-on-os-x)
    + [Building on Windows](#building-on-windows)

## Development resources

- Web: [goldgamecoin.com](https://goldgamecoin.com)
- Mail: [goldgamecoin@gmail.com]([goldgamecoin@gmail.com)
- Github: [https://github.com/goldgamecoin-project/Gold](https://github.com/goldgamecoin-project/Gold)
- Translation platform (Weblate): [translate.https://goldgamecoin.com](https://translate.goldgamecoin.com)

## Vulnerability response

- Our [Vulnerability Response Process](https://github.com/goldgamecoin-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) encourages responsible disclosure
- We are also available via [HackerOne](https://hackerone.com/gold)

## Introduction

Monero is a private, secure, untraceable, decentralised digital currency. You are your bank, you control your funds, and nobody can trace your transfers unless you allow them to do so.

**Privacy:** Monero uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain absolutely private by default.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25 word mnemonic seed that is only displayed once, and can be written down to backup the wallet. Wallet files are encrypted with a passphrase to ensure they are useless if stolen.

**Untraceability:** By taking advantage of ring signatures, a special property of a certain type of cryptography, Monero is able to ensure that transactions are not only untraceable, but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.

## About this project

This is the GUI for the [core goldgamecoin implementation](https://github.com/goldgamecoin-project/Gold). It is open source and completely free to use without restrictions, except for those specified in the license agreement below. There are no restrictions on anyone creating an alternative implementation of Monero that uses the protocol and network in a compatible manner.

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews. That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. It is generally a better idea to use a tagged release for stability.

## Supporting the project

GUI development funding and/or some supporting services are also graciously provided by [sponsors](https://www.goldgamecoin.com/community/sponsorships/):

[<img width="150" src="https://www.goldgamecoin.com/img/sponsors/tarilabs.png"/>](https://tarilabs.com/)
[<img width="150" src="https://www.goldgamecoin.com/img/sponsors/globee.png"/>](https://globee.com/)
[<img width="150" src="https://www.goldgamecoin.com/img/sponsors/symas.png"/>](https://symas.com/)
[<img width="150" src="https://www.goldgamecoin.com/img/sponsors/forked_logo.png"/>](http://www.forked.net/)
[<img width="150" src="https://www.www.goldgamecoin.com/img/sponsors/macstadium.png"/>](https://www.macstadium.com/)

There are also several mining pools that kindly donate a portion of their fees, [a list of them can be found on our Bitcointalk post](https://bitcointalk.org/index.php?topic=583449.0).

## License

See [LICENSE](LICENSE).

## Translations

Do you speak a second language and would like to help translate the Monero GUI? Check out Weblate, our localization platform, at [goldgamecoin.com](https://translate.goldgamecoin.com/). Choose the language and suggest a translation for a string or review an existing one. The Localization Workgroup made [a guide with step-by-step instructions](https://github.com/goldgamecoin-ecosystem/goldgamecoin-translations/blob/master/weblate.md) for Weblate.

If you need help/support or any info you can contact the localization workgroup on the IRC channel #goldgamecoin-translations (relayed on matrix/riot and MatterMost) or by email at translate[at]getmonero[dot]org. For more info about the Localization workgroup: [github.com/golgamecoin-ecosystem/goldgamecoin-translations](https://github.com/goldgamecoin-ecosystem/monero-translations)

Status of the translations:  
<a href="https://translate.goldgamecoin.com/engage/gold/?utm_source=widget">
<img src="https://translate.goldgamecoin.com/widgets/gold/-/gui-wallet/horizontal-auto.svg" alt="Translation status" />
</a>

