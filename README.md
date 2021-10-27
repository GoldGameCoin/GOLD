# GOLDGAMECOIN

Copyright (c) 2020-2021 The GolGameCoin Project.
Portions Copyright (c) 2012-2013 The Cryptonote developers


## Table of Contents
  * [Development resources](#development-resources)
  * [Vulnerability response](#vulnerability-response)
  * [Introduction](#introduction)
  * [About this project](#about-this-project)
  * [Project focus](#Project focus-project)
  * [Supporting the project](#supporting-the-project)
  * [License](#license)
  * [Translations](#translations)
  
## Development resources

- Web: [goldgamecoin.com](https://goldgamecoin.com)
- Mail: [goldgamecoin@gmail.com]([goldgamecoin@gmail.com)
- Github: [https://github.com/goldgamecoin-project/Gold](https://github.com/goldgamecoin-project/Gold)
- Translation platform (Weblate): [translate.https://goldgamecoin.com](https://translate.goldgamecoin.com)

## Vulnerability response

- Our [Vulnerability Response Process](https://github.com/goldgamecoin-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) encourages responsible disclosure
- We are also available via [HackerOne](https://hackerone.com/gold)

## Introduction

Gold Game Coin is a private, secure, untraceable, decentralised digital currency. You are your bank, you control your funds, and nobody can trace your transfers unless you allow them to do so.

**Privacy:** Gold Game Coin uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain absolutely private by default.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25 word mnemonic seed that is only displayed once, and can be written down to backup the wallet. Wallet files are encrypted with a passphrase to ensure they are useless if stolen.

**Untraceability:** By taking advantage of ring signatures, a special property of a certain type of cryptography, Gold Game Coin is able to ensure that transactions are not only untraceable, but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.

## About this project

This is the GUI for the [core goldgamecoin implementation](https://github.com/goldgamecoin-project/Gold). It is open source and completely free to use without restrictions, except for those specified in the license agreement below. There are no restrictions on anyone creating an alternative implementation of GoldGameCoin that uses the protocol and network in a compatible manner.

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews. That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. It is generally a better idea to use a tagged release for stability.

## Project focus

This project has been created for everyone, but especially to promote the cryptocurrency and E-SPORT market in a changing world focused on the virtual market.
That is why GoldGameCoin, sponsors and cooperators are looking forward to starting this project with all of you.
We will make a significant change in the way we view games and cryptocurrencies.
Some examples of how the Gold Game Coin will be used
- Rewards in tournaments.
- Purchases on the sponsoring websites.
- Change from virtual currency to currency in progress.
and much more...

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

Do you speak a second language and would like to help translate the GoldGameCoin GUI? Check out Weblate, our localization platform, at [goldgamecoin.com](https://translate.goldgamecoin.com/). Choose the language and suggest a translation for a string or review an existing one. The Localization Workgroup made [a guide with step-by-step instructions](https://github.com/goldgamecoin-ecosystem/goldgamecoin-translations/blob/master/weblate.md) for Weblate.

If you need help/support or any info you can contact the localization workgroup on the IRC channel #goldgamecoin-translations (relayed on matrix/riot and MatterMost) or by email at translate[at]goldgamecoin[dot]com. For more info about the Localization workgroup: [github.com/golgamecoin-ecosystem/goldgamecoin-translations](https://github.com/goldgamecoin-ecosystem/goldgamecoin-translations)

Status of the translations:  
<a href="https://translate.goldgamecoin.com/engage/gold/?utm_source=widget">
<img src="https://translate.goldgamecoin.com/widgets/gold/-/gui-wallet/horizontal-auto.svg" alt="Translation status" />
</a>

## Webentries

It is strongly strongly STRONGLY encouraged that if you make a change, you - at the minimum - test it on your local machine before submitting a PR. Sometimes unexpected things may happen due to a change. If you change a page, check the whole page on multiple screen sizes and browsers to make sure there wasn't any collateral damage.

### Tor
This website is available natively on Tor. The onion address is in `_includes/onion.html` and a signed document containing the same address is in `/onion.txt`. The address in these 2 files must *always* match. The `onion.txt` files also includes the onion address of the 'downloads' subdomain.

If you want to post getgoldgamecoin's onion address somewhere on the website, don't simply write it, instead include it using `{% include onion.html %}`. This avoids problems with typos and allow us top change the address only in one file if necessary.

	@@ -56,7 +56,7 @@ The entire website, except for the Goldpedia entries, is translatable on Webla

Translators are required to have:

- A basic understanding of Gold Game Coin technologies and wallets
- A basic knowledge of markdown syntax
- A basic knowledge of HTML syntax

	@@ -75,8 +75,8 @@ Go to the /i18n folder and find the two letter code for the language you wish to
### 3. Translate the file
Here you can do your translation. Depending on the page, you may have to maneuver around some HTML or markdown. In general, anything between two tags (such as `<p>TRANSLATE THIS</p>`) should be fine. Testing is VERY important, so do NOT skip it. If during testing, the page appears different from the original English page (besides the translated text, of course), you did something wrong and may have to start again.

#### 3.1. Notes for Goldpedia Entries
Goldpedia entries have two specificities:

* The Front Matter:  
Goldpedia Fron should be translated for both *entry:* and *summary:* elements. However, *terms:* should be extended with their translation, leaving the English words **untouched**.
	@@ -135,7 +135,7 @@ Navigate to the \_i18n folder and duplicate the en.yml file. Rename the duplicat
**The original folder and yml file themselves should still be there. They should not be renamed. There should be a new folder and yml file in addition to the ones that were already there.**

### 4. Open an issue on the repo where the website is hosted
After you've done all the above, you'll need to [open an issue on the repository](https://github.com/Goldgamecoin-project/gold-site/issues) asking to add the language you are working on to Weblate, where the core of the website is translated.

## Housekeeping

	@@ -255,16 +255,16 @@ In the event that you think your User Guide should be in a new Category that doe

Repeat the above process for each language version of this index page.

## How to make a Goldpedia Entry

### 1. Make a Global file
Navigate to the /resources/goldpedia folder and make a new file. Be sure the file name has no spaces and the ending is .md
Fill this file with this exact content:
```
---
layout: goldpedia
title: titles.goldpedia
entry: goldpedia.entries.ENTRY
---
@goldpedia_article
	@@ -307,7 +307,7 @@ summary: "PUT SUMMARY OF YOUR ENTRY HERE IN QUOTES"
```

### 5. Add the title to _i18n/en.yml
Now you need to add the title of the page to the `_18n/en.yml` file. It *must* be in the `goldpedia` section and must be the same as the `ENTRY` you added early in the `/resources/goldpedia` folder (goldpedia.entries.ENTRY). Keeping as example a Goldpedia called "Daemon", you have to add in the `goldpedia` block `daemon: Daemon`.

## How to update the Workgroups page

	@@ -339,7 +339,7 @@ If an entry is `completed`, a green tick simble will be displayed on its left. i

If you need to add a month, add `<h3 id="months">{% t roadmap.MONTH %}</h3>` above your roadmap entry. `MONTH` is one of the 12 months, you'll find the list in the `_18n/en.yml` file. In the `roadmap` section.

The roadmap can be translated on Weblate [on Weblate](https://translate.goldgamecoin.com/projects/gold/goldgamecoin-site/).

## How to add a question to the FAQ
The structure of the FAQ is a bit more complex than it used to be and contains anchors, variables and a TOC. A step by step guide would be too complex to follow. A basic knowledge of HTML is necessary to edit the page. If you wish to add a new FAQ please open an issue in the repository or/and contact the Website workgroup.
