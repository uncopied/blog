---
date: 2021-06-04
description: "Uncopied has released two examples of a TEAL smart contract to manage artistic royalties and 'droit de suite' on Algorand NFTs."
featured_image: "/images/photo-1501366062246-723b4d3e4eb6.jpg"
tags: ["Algorand","TEAL"]
title: "Royalty smart contract in TEAL for Algorand NFTs"
---

## A Quick Note on Uncopied

In February 2021, we started to demo a new kind of Certificate of Authenticity (CoA) to several artists, galleries and museums. 
Our prototype combined a [chirograph](/about/chirograph/) and an Algorand Standard Asset (ASA) to secure the origin of a physical or digital artwork.  

The prototype worked great and we received some valuable feedback. We could feel the strong expectations from the Algorand community, as we were hoping to launch in May 2021.

However, we found that the prototype's monolithic architecture would limit our ability to integrate with partners in the spirit of a distributed ecosystem.

In the past few months, the [team](/about/team/) has been working hard, refactoring Uncopied into a clean set of APIs and scalable Golang micro-services. The UI was also refactored from plain ReactJS to a NextJS framework. We're now hoping to soft-launch by the end of June 2021. 

### Proof of Provenance and Conservation

Uncopied provides digitally immutable certificates for original artworks. Our goal is to participate in the emergence of a stronger artistic ecosystem based on trust, secure proof of provenance and long term, tamper-proof [physical and digital conservation](/blog/blockchain-museum-collection-inventory/).

To focus on our core services, we've decided that the Uncopied ASA will be used exclusively to secure the certification. 
Uncopied ASAs will always be non-tradable. 

    Uncopied ASA != tradable Non-Fungible-Token (NFT)

We're interested in collaborating with artists, galleries and museums who will issue their own NFTs. Uncopied will provide the Proof of Provenance (as well as some other cool conservation or copyright protection services). 

Algorand is a great platform to do that. Fantastic projects are underway (a fine art gallery, fractionalised art, distributed exchange or DEX, etc.).
They will provide more ecological alternatives to the huge energy consumption we see on Ethereum to 'mint' NFTs. 
We're happy and proud to already be collaborating  with some of them. There are other cool projects underway on other carbon-friendly blockchains ([hicetnunc](https://www.hicetnunc.xyz/) on Tezos, [SIGN art](https://www.sign-art.app/) on Waves, etc.).

## Getting royalties and 'droit de suite' to be paid on Algorand

Although Uncopied doesn't intend to become a new NFT marketplace in like Rarible or Opensea, we want to make sure our solution integrates well with the most complex distributed use cases. 

'Droit de suite' or Artist's Resale Right (ARR) is a right granted to artists to receive a fee on the resale of their works of art.

We wanted to prototype a smart contract that would manage complex royalties and 'droit de suite' for artists. We were interested to see if such a contract could work in the context of a Distributed Exchange (DEX). 

We've reached out to [Jesulonimi Akingbesote](https://github.com/Jesulonimi21) to help. Jesulonimi is a Google Associate Android Developer and a recipient of the Algorand Development Award.

We started from Algorand provided examples and tutorials:
- Assets and Custom Transfer Logic by Jason Weathersby, Algorand (https://developer.algorand.org/solutions/assets-and-custom-transfer-logic/)
- AlgoRealm, an NFT Royalty Game by Cosimo Bassi, Algorand (https://developer.algorand.org/solutions/algorealm-nft-royalty-game/)

We've released two prototype smart contracts for the Algorand community:
- Firstly, a rather simple case where the artist receives percentage on any secondary market sales (https://github.com/uncopied/smart_contract)
- Secondly, in partnership with [EPOCH Gallery](https://epoch.gallery/), a complex contract splitting the initial sale and the secondary market sales between seven artists and the gallery according to a custom royalty breakdown (https://github.com/uncopied/epoch_smart_contract)

Both smart contracts are released under an Apache 2.0 open-source licence. 

Please find Jesulonimi's explanations below:

{{< youtube id="674lob3OsmQ" autoplay="false" >}}

Feel free to join the Github repository if you would like to contribute. Please report any issues if you find them.

Photo by Jeremy Bishop on Unsplash.
 
