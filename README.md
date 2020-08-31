# Konjungate Core v1.0.1.3

Name: Konjungate<br/>
Ticker: KONJ<br/>
Type: Hybrid, POS / POW / Masternodes<br/>
Algorithm: bmw512<br/>
Total Coin Supply: 21 billion<br/>

Rewards per Block:
250 KONJ / BLOCK (shared as follow)

POW 62.5 KONJ decreasing 10% every 6 month
POS 48.75 KONJ after 6 month increasing to 68.75 KONJ after this: decreasing 15% every 6 month 
MN. 113,75 KONJ after 6 month increasing to 153.75 KONJ after this: increasing 17% every 6

Masternode Collateral: 2750000 KONJ

Charity fee (taken from POW): 25 KONJ to support contemporary ART.<br/>
Please visit https://www.machfeld-foundation.net to see our supported Projects.

Official Website:<br/>
https://www.konjungate.net

## What is Konjungate?
KONJUNGATE - The Artbased Blockchain To change the funding of Artists and Institutions. Based on the cyber novel MACHFELD by Michael Mastrototaro © 1999

Konjungate will chance the funding of contemporary Art and Art-Institutions using blockchain technology to change the way of contemporary art funding.

See our projects at:<br/>
https://wendy.network<br/>
https://www.machfeld-foundation.net<br/>

KONJUNGATE is based on the cyber novel MACHFELD written 1999 by Michael Mastrototaro. Strangely, the main character of the book is called Nakomoto and thus resembles the pseudonym of the BITCOIN inventor Satoshi Nakomoto. What a coincidence, right? Anyway. In his cyber novel, Michael Mastrototaro describes 9 years before Bitcoin appears on the cryptocurrency horizon the mining of KONJUNGATE. Now 20 years after publishing the novel online, KONJUNGATE appears as a Media Art project to decentralize the funding of international contemporary Artists and Institutions and to give a strong artistic statement in times of budget cuts.



## LINKS

Official Website:<br/>
https://www.konjungate.net/

Official Mining Pool:<br/>
https://pool.konjungate.net/<br/>
https://ahamay.net/

Block Explorer:
http://explore.konjungate.net/<br/>

Bitcoin Talk announcment:
https://bitcointalk.org/index.php?topic=5148524.msg51263942#msg51263942<br/>

---------------->>>-----<<<<<<---------------------

(So called) Social Media Links:

Telegram: https://t.me/joinchat/CZxxC03HTpvdGDWlXg0tgQ 

Facebook: https://www.facebook.com/konjungate/ 

Twitter: https://twitter.com/konjungate

YouTube: https://www.youtube.com/channel/UCnm-eA9EGNwSHu3KKzkm8Zg

---------------->>>-----<<<<<<---------------------

EXCHANGES

CREX24:
https://crex24.com/exchange/KONJ-BTC<br/>
https://crex24.com/exchange/KONJ-ETH




## License

Konjungate Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

## Development Process

The master branch is meant to be stable. Development is normally done in separate branches. Tags are created to indicate new official, stable release versions of Konjungate Core.

The contribution workflow is described in CONTRIBUTING.md.

## Testing

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.

## Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check

There are also regression and integration tests of the RPC interface, written in Python, that are run automatically on the build server. These tests can be run (if the test dependencies are installed) with: qa/pull-tester/rpc-tests.py

The Travis CI system makes sure that every pull request is built for Windows and Linux, OS X, and that unit and sanity tests are automatically run.

## Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.
