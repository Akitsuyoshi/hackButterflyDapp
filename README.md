# Hack Butterfly

<p align="center">
  <img alt="hackButterfly" title="hackButterfly" src="public/images/intro.png" width="auto">
</p>

## Table of Contents

- [Presentation](#presentation)
- [Introduction](#introduction)
- [Features](#features)
- [Feedback](#feedback)


## Presentation & Prerequisites

Welcome to my very first dApp tutorial! Please find the [presentation here](https://google.com//), which is build specifically around this repo. The presentation was held in person, so the 'live-coding' section won't be included for obvious reasons.

### Prerequisites

* Installed [Metamask as a chrome plugin](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en), hooked up an account, and have some [Ropsten test money](https://faucet.metamask.io/) in it.
* Be somewhat familiar with the idea behind Ethereum, Smart Contracts, and dApps
* Have a basic understanding of programming
* Ideally have an understanding of Vue.js

## Introduction

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

To me, blockchain technology is a paradigm shift in the sectors of transparency, trust, and efficiency. Inspired by the thoughts about a [transparency standard](https://www.forbes.com/sites/paulmartyn/2018/03/28/does-blockchain-provide-the-new-standard-for-transparency/#bb46c663921e) that could be achieved through blockchain, I thought about how to achieve that in small scale. Imagine a world where every university offers a transparent, always up to date, and immutable list of students and graduates. Instead of background-checking if a student realy went to Stanford, one can simply call function on a smart contractfind to receive the answer. 100% free and always updated. 

The online coding school Hack Butterfly is an MVP to model such an idea through using [Ethereum](https://www.ethereum.org/), [Solidity](https://solidity.readthedocs.io/en/v0.4.24/), [web3](https://github.com/ethereum/web3.js/), and [Vue](https://vuejs.org/).

This project and the presentation were both created during my time as a student at Code Chrysalis. (yes, Hack Butterfly is a pun on that, glad you caught it)

[You can check out the demo here!](https://hackbutterfly.herokuapp.com/)

## Features

These are the features of the current version:

* Sign up as a student through the Ropsten test network!
* Get a list of current students and alumni
* OnlyOwner: Graduate student
* OnlyOwner: Set program cost

## TL;DR

Here's some useful information to get know before getting started with the codebase 

* Owner: 0x4B8dc8d5A7d51c2FFE2A3C1f08DbFC884265967E
* Smart Contract address and ABI is in public/src/utils


## Feedback

Please feel free to send me any feedback or questions via [Discord](https://discordapp.com/users/Akzent#6791) or [email](https://www.sourcecon.com/how-to-find-almost-any-github-users-email-address/).


## Project Setup

1. You find the smart contract's codebase in public/src/utils/. I did deploy the smart contract ("sm" from now on) through [Remix](https://remix.ethereum.org/), Ethereum's IDE. I've solely put the sm for completeness into this repo. I did not deploy it locally from my machine.

2. Once you've deployed your own iteration of the sm (if you chose so), update abi.js and contractAddress.js accordingly. You might want to revisit some methods within the components as well after you made some changes to the functions within the sm. 

3. If you are overwhelmed with smart contracts and Remix, [here](https://www.youtube.com/watch?v=KkN1O8TChbM) and [here](https://www.youtube.com/watch?v=KU6bvciWgRE&list=PL0lNJEnwfVVMuX2Ds19Wj_7Mcze3FDJr3) are some videos to get started.

4. As mentioned, you do need the chrome plugin [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en) with some money in there. (make sure to be on the Ropsten Test Network)

### After you cloned the project, run:
```
yarn
```
### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Lints and fixes files
```
yarn run lint
```
