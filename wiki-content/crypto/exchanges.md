---
layout: default
title: DEX
parent: Crypto
nav_order: 1
---

DEX (decentralized exchange) - decentralizovaná zmenáreň je služba kt. pochopiteľne umožňuje výmenu kryptomien. Základným rozdielom od CEX je že nefungujú na princípe order booku ale väčšinou sa využíva <b>liquidity pool</b> alebo sústava smart contractov. Skvelé je, že tieto zmenárne nevyžadujú KYC.

_Disclaimer - treba rozlišovať medzi DEXom a automatizovanou zmenárňou bez prihlásenia. Služby ako FixedFloat, či ChangeNOW v skutočnosti niesú DEX ale automatizovaná zmenáreň bez prihlásenia._

!! tu pozor KYC nepožadujú defaultne, môže sa však stať, že vám bloknú order a budú po vás KYC chcieť. <a href="https://ff.io/terms-of-service#terms_section_7">FixedFloat to má v podmienkach používania</a> a naozaj ak sa im coiny nezdajú tak to robia. 
<a href="https://changenow.io/faq/kyc">Rovnako aj ChangeNOW to má v pravidlách</a>.

## Akú zmenáreň použiť
Osobne mám vyskúšané zmenárne:
- <a href="https://ff.io/">FixedFloat</a> - dá sa tam posielať LN, a mám odpozorované, že majú aj zvyčajne lepší kurz ako ChangeNOW. Ponuka coinov nieje až taká vysoká ale na základné veci (BTC na Monerko) stačí. Treba však upozorniť že <a href="https://decrypt.co/218077/fixedfloat-hack-26-million-bitcoin-ethereum">boli nedávno vyhackovaný</a>, čo síce vraj nemalo dopad na používateľov (okrem toho, že boli potom niekoľko dní down) ale zamňa osobne to nieje dobré znamenie.
- <a href="https://changenow.io/">ChangeNOW</a> - tiež používam, zatiaľ spokojnosť avšak o niečo väčšie fee ale väčší výber shitcoinov.
- <a href="https://boltz.exchange/">Boltz exchange</a> - na swap medzi BTC a LN
- <a href="https://sideswap.io/peg-in-out/">Sideswap</a> - pre swapovanie medzi BTC a LBTC

Ďalej je vraj v obľube <a href="https://bisq.network/">bisq.network</a> ale k tomu sa neviem vyjadriť, nepoužíval som. Skús pozrieť <a href="http://www.bitcoinpit.net/index.php/ako-kupit-bitcoin-v-decentralizovanej-zmenarni-bisq/">sem</a>. 

Okrem toho samozrejme aplikácia <a href="https://vexl.it/">Vexl</a>, ktorá je tu vždy preteba :-)

## Ako zmenárne používať
Do zmenárne/DEXu vždy odporúčam vkladať čisto novú adresu a pred posielaním onchain BTC (alebo hoc čoho iného) odporúčam vždy najskôr skontrolovať feečka napríklad cez <a href="https://mempool.space/">mempool.space (v prípade BTC)</a> a čo sa týka:
- Fixed rate (1.0%)
- Float rate (0.5%) 

Ja osobne používam float rate a zatiaľ som vždy dostal plus ale skúsenosti môžu byť rôzne.

Ešte prikladán zoznam zmenárni kt. sa kumne dostal (neviem ako moc je up to date a ako moc sú tie zmenárne dobré/zlé okrem tých kt. som spomenul vyššie):
<a href="https://docs.google.com/spreadsheets/d/1GPZMY2yIhqRwykoGDfKdGYrFESmz6jRLk-YpwQJ7G-U/edit#gid=0">https://docs.google.com/spreadsheets/d/1GPZMY2yIhqRwykoGDfKdGYrFESmz6jRLk-YpwQJ7G-U/edit#gid=0</a>

## Ďaľšie info
Toto bol stručný základ, pokračovať v štúdiu môžeš napríklad tu:
 - <a href="https://juraj.bednar.io/zoznam-derivatovych-burz/">https://juraj.bednar.io/zoznam-derivatovych-burz/</a>, kde okrem iného nájdeš aj zoznam derivátových búrz kt. Juraj udržiava

### Cross-chain swap & bridges
- https://jumper.exchange/ - zamieňa aj medzi rôznymi Ethereum-like chainmi (napr. ETH na Ethereum Mainnet → xDai na Gnosis), agregátor viacerých zmenární. Nejde zadať cieľová suma.
- https://www.mtpelerin.com/ - swap medzi BTC-LN (sat) a eth sidechains, KYC. Ide zadať cieľová suma.
- https://app.1inch.io/ ERC20 - swap medzi rôznymi Ethereum chains. Nejde zadať cieľová suma.
- https://www.sushi.com/swap - Ethereum, Arbitrum One, Base, Polygon, Optimism, BNB, Avalanche. Nejde zadať cieľová suma.
- https://simpleswap.io/ - BTC, ETH, XMR, LTC, fiat, +hromada ďalších
- https://uniswap.org/ - ERC20 tokens. 
- https://honeyswap.1hive.eth.limo/ 
- https://bridge.connext.network/ 
- https://swapr.eth.limo/ 
- https://app.boringdao.com/ 
- https://app.shapeshift.com/

### Decentralizované zmenárne
- https://uniswap.org/
- https://bitshares.org/wallet/
- https://openledger.io/
- https://market.rudex.org/
- https://door.one/en/
- https://idex.market/
- https://loopring.io/ - spracováva aj transakcie viac ako dvoch strán, pracuje cez MetaMask, obchoduje s ETH, Loopring Coin, USDT, DAI, ChainLink, <a href="https://www.publish0x.com/cryptonators-airdrop-hunt/loopring-a-new-exchange-aims-to-revolutionize-crypto-trading-xwpnnr">viac info</a>
- https://www.sushi.com/
- https://app.1inch.io/ 
- https://honeyswap.1hive.eth.limo/
