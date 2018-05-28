# dWeb Library Name

[![dWebShield-Official](https://img.shields.io/badge/DWEB-Official-brightgreen.svg)](https://https://github.com/benchlab/dweb)[![dWebShield-Auth](https://img.shields.io/badge/DWEB-Auth-brightgreen.svg)](https://https://github.com/benchlab/dweb)<br>
[![dWebShield](https://github.com/benchlab/dweb-shields/blob/master/shields/dweb-protocol-shield.svg)](https://github.com/benchlab/dweb)

This area is reserved for a short description of the dWeb library, protocol, decentralized website or decentralized application you are launching on the dWeb.

## Table of Contents

- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)
- [API](#api)
- [Related Projects](#related-projects)
- [Why Decentralized Internet](#why-the-internet-must-have-a-decentralized-alternative)
- [Bench On The dWeb](#bench-on-the-dweb)
- [License](#license)
- [Copyright](#license)

## Background
Here we describe the background behind the library, protocol, website or application this README is connected to. It can be between 3-4 sentences but shouldn't be too long. 

## Installation

```
npm i --save dweb-library-name
```
```
yarn add dweb-library-name
```
```
dpack add dweb-library-name
```

## Terms
- termOne - Short description for termOne. 
- termTwo - Short description for termTwo.

## Usage

```js

dWeb Library Code Here

```

## API 
**Note:** If your library or repository doesn't have any sort of API, this section can be deleted. Don't forget to remove from the table of contents. 

#### `var vault = ddrive(dstorage, [dkey], [options])`

This is a description of what it does.

This is a longer description of what it does. Should be several sentences and give an intro to the following lines, which should explain the process behind the code and what the end result is. 

- This should describe the first part of the process.
- This should describe the next part of the process.
- This might describe some arguments that are made in the above API call:

  - `fileName`: this should be the name of the file we are storing within the given `dDrive` (Distributed Drive).
  - `dwOpts`
    - `recordKey`: the [record key](https://github.com/benchlab/ddrive#recordkey) of the given `dDrive`.
    - `revelationKey`: the [revelation key](https://github.com/benchlab/ddrive#recordrevelationkey) of the given `dDrive`.
  - `dvault`: the current `dDrive` being accessed.


**Important**: These functions need to return a [`dwRam`](https://github.com/benchlab/dwram/) instance.

Options include:

``` js
{
  thin: true, // this allows the ddrive to only retreive data that it is requested to retreive. 
  thinMd: true // this allows the ddrive to only retreive data via a metadata feed that it is requested to retreive.
  MDSCS: 65536 // the number of items to use in the  metadata `dRecord` `Least Recently Used` cache.
  CSCS: 65536 // the number of items to use in the content `dRecord` `Least Recently Used` cache.
  MTCS: 65536 // the number of items to use in the `affixTree`'s `Least Recently Used` cache.
}
```

**Note**: Snapshotted `dDrive` vault can be "thin". You can do this by enabling the `thin: true` option. In this way, records that are being fed to the `dDrive` won't be accepted unless it's specifically asked to do so. If you want the thinnest possible `dDrive`, it would also be wise to enable `thinMd: true` for the same effect as `thin:true`, except with MetaData. 


## Related Projects
- [dweb-project1](https://github.com/benchlab/dweb-project1) - dWeb Project One description
- [dweb-project2](https://github.com/benchlab/dweb-project2) - dWeb Project Two description
- [dweb-project3](https://github.com/benchlab/dweb-project3) - dWeb Project Three description
- [dweb-project4](https://github.com/benchlab/dweb-project4) - dWeb Project Four description
- [dweb-project5](https://github.com/benchlab/dweb-project5) - dWeb Project Five description

## Why The Internet Must Have A Decentralized Alternative
Today, the internet is more censored than ever and it's only getting worse. Our mission with the [dWeb Protocol](https://github.com/benchlab/dweb) was to create a truly powerful P2P protocol, around [benOS](https://github.com/benchlab/benos), [dBrowser](https://github.com/benchlab/dbrowser) and many of benOS' underlying libraries to bring the most powerful P2P products to life. In the last few months, by rebuilding P2P technologies that have existed since the early 2000s, we have built a powerful suite of decentralized libraries for benOS and the Bench Network, that will only improve over time. But we also brought new ideas to life, like:

- [dDrive](https://github.com/benchlab/ddrive)
- [dExplorer](https://github.com/benchlab/dexplorer)
- [dDatabase](https://github.com/benchlab/ddatabase)
- [dSites](https://github.com/benchlab/dsites)
- [dPack](https://github.com/benchlab/dpack) 
- [benFS](https://github.com/benchlab/benfs)
- [DCDN](https://github.com/benchlab/dcdn)
- [Rocketainer](https://github.com/benchlab/rocketainer) 
- [RocketOS](https://github.com/benchlab/rocketos) 
- [dNames](https://github.com/benchlab/dnames) 
- [P2PDNS](https://github.com/benchlab/p2pdns) 
- [dWebFS](https://github.com/benchlab/dwebfs) 
- [dWebDB](https://github.com/benchlab/dwebdb) 
- [MeteorIDE](https://github.com/benchlab/meteorIDE) 
- [Kepler](https://github.com/benchlab/kepler) 
- [Neutron](https://github.com/benchlab/neutron) 
- [Designate](https://github.com/benchlab/designate) 
- [Nova](https://github.com/benchlab/nova) 

and more! These were the protocols and libraries that we needed to create a completely decentralized operating system, where everything was distributed, protected and people were once again in control of their data. benOS is made up of over 1100+ different libraries that we are releasing on a day-by-day basis as we move them to a stable/production state. While financial support is great for this open source project, we need to developers who want to be the first to build the `dApps` and `dSites` of the future. We have to take back what our forefathers originally designed for freedom, by making our code the law, instead of weak and highly centralized applications where law can be applied because the code lacked the foundation to implement the law itself. Join us for a truly historic journey on the [BenchLabs Telegram](https://t.me/benchlabs). See you there. 

### Bench On The dWeb
[dweb://bench.dnames.io](dweb://bench.dnames.io) // dNames Short Link 
[dweb://3EDAE09848B77401445B7739CAFCE442DDE1752AED63025A1F94E6A86D7E9F04](dweb://3EDAE09848B77401445B7739CAFCE442DDE1752AED63025A1F94E6A86D7E9F04) // dWeb Key Link 

In order to make the links above clickable or to view these links period, you will need [dBrowser](https://github.com/benchlab/dbrowser) (Available for Mac OSX, Linux, Windows and soon to be available on iOS/Android)

#### "The Code Is The Law" - Stan Larimer - Godfather of BitShares.

## License
[MIT](LICENSE.md)

## Copyright 
Copyright (c) 2018 Bench Computer, Inc. All rights reserved. 
