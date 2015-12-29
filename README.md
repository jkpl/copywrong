# CopyWrong

## What?

This is a list of software that was [free software](http://www.gnu.org/philosophy/free-sw.en.html) and is now proprietary.

When free software becomes proprietary it means that you, as a user of the software, no longer have all four essential freedoms to:

1. run the program as you wish, for any purpose.
2. study how the program works, and change it so it does your computing as you wish.
3. redistribute copies so you can help your neighbour.
4. distribute copies of your modified versions to others.

Additionally, if you are a user of free software that has become proprietary, you are now in a supplier lock-in and may be facing further usage restrictions, the risk of viruses / spyware, as well as large fees to your supplier.

## How?

There are two legal ways that free software can become proprietary:

1. the copyright owners release a new version of the software using a license that is not a free software license.
2. the original software license wasn't [copyleft](https://www.gnu.org/copyleft/), and some entity later distributes a modified version of the software under a proprietary license.

## How can I help?

Luckily, there are several ways that you can help.

1. If you are starting a new free software project, use a [copyleft](https://www.gnu.org/copyleft/) license.
2. Do not assign copyright of your free software contributions to a third party until you have read the FSF guide to [assigning copyright](http://gnu.org/philosophy/assigning-copyright.html) and are comfortable with the situation.
3. Document free software that has become proprietary on this list and inform your community of the danger they are facing if they continue to use the proprietary software.
4. Create a fork of the software from the last point at which it was free software. Make all your changes using a copyleft license, so that your changes can not be used in a proprietary distribution. Trust that developers will prefer your fork, even if the proprietary version may have more features in the short term.

## The Lists
### Made Proprietary by its Owners

| Name   | Supplier | Free License | Proprietary License | Forks | Notes |
|--------|--------|--------------|---------------------|-------|-------|
| [Slick](https://github.com/slick/slick) | [TypeSafe](https://www.typesafe.com/) | [BSD 2 Clause](https://opensource.org/licenses/BSD-2-Clause) | [TypeSafe Subscription Agreement](http://typesafe.com/public/legal/TypesafeSubscriptionAgreement.pdf) | [FreeSlick](https://github.com/smootoo/freeslick) | The Slick library remains free software, but database drivers were converted to a proprietary license. |
| [FoundationDB](https://en.wikipedia.org/wiki/FoundationDB) | Apple | [Apache 2.0](http://opensource.org/licenses/Apache-2.0) | [not available](http://techcrunch.com/2015/03/24/apple-acquires-durable-database-company-foundationdb/) | unknown | last known free release on [Maven Central](http://search.maven.org/#browse%7C-1374863701) |
| [LaunchD](https://en.wikipedia.org/wiki/Launchd) | Apple | [Apache 2.0](http://opensource.org/licenses/Apache-2.0) | [OS X SLA](http://images.apple.com/legal/sla/docs/OSX1011.pdf) | unknown | last known free release in [Apple Open Source](https://opensource.apple.com/source/launchd/) |
| [Nessus](https://en.wikipedia.org/wiki/Nessus_%28software%29) | Tenable Network Security | [GPL](http://opensource.org/licenses/GPL-3.0) | [commercial, details not available](https://store.tenable.com/) | [OpenVAS](http://www.openvas.org/) | |


### Third Party Proprietary Distributions

| Name   | Free Supplier | Proprietary Supplier | Proprietary License | Notes |
|--------|-------------|--------------------|---------------------|-------|
| LLVM   | [LLVM](http://llvm.org) | Apple | [XCode SLA](http://images.apple.com/legal/sla/docs/xcode.pdf) | The [LLVM license intentionally encourages proprietary forks](http://llvm.org/docs/DeveloperPolicy.html#copyright-license-patents) |
