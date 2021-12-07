---
date: 2021-12-07
description: "December 3, 2021 - Elian Carsenat, Founder, UNCOPIED;
Joey Heinen, Digital Preservation Manager, LACMA ; Joel Ferree, Program Director, Art & Technology Lab
Art + Technology"
featured_image: "/images/ma-51306.jpg"
tags: ["Museum"]
title: "NFTs and the Museum Part 5: Art Collections on the Blockchain"
---
NFTs present challenges for collectors beyond the logistics of ownership and exchange, but also in terms of long-term sustainability and authorship of these artworks. Questions arise as to what stake various blockchain technologies have in guaranteeing that these unique assets have a life beyond the immediate, and questions around the transmutability of these assets onto other blockchain systems remain murky. For this installment of [NFTs and the Museum](https://www.lacma.org/lab/nfts-and-museum), LACMA Digital Preservation Manager Joey Heinen interviewed Elian Carsenat, computer scientist and founder of [UNCOPIED](https://uncopied.art/), an authentication system for digital artworks (including NFTs).

>This article is a Los Angeles County Museum of Art (LACMA) UNFRAMED reblog. You can read the [original article](https://unframed.lacma.org/2021/12/03/nfts-and-museum-part-5-art-collections-blockchain) or its [French translation](/fr/blog/lacma-unframed-nfts-and-museum-part-5-art-collections-blockchain/).

{{< figure src="/images/ma-51306.jpg" title="Ostracon Recording a Barter Transaction, Egypt, New Kingdom, 19th Dynasty (1315–1201 BCE), Los Angeles County Museum of Art, Gift of Carl W. Thomas, photo © Museum Associates / LACMA" >}}


**Joey Heinen:** As blockchain technologies become more dominant in the art market and in data systems and protocols, I am interested to see the emergence of discussions around open data and shared repositories as opposed to just thinking about rarified assets and objects. Tell me about the work you are doing related to NFTs and blockchain. What gap are you trying to fill?

**Elian Carsenat:** UNCOPIED started from a different perspective. Back in July 2020, I was looking for a solution for a digital artwork made in collaboration with Dario Rodighiero (metaLAB (at) Harvard University) and Eveline Wandl-Vogt (Austrian Academy of Science; Ars Electronica Research Institute Knowledge for Humanity). The objective was to distribute the digital image freely as Creative Commons, yet make limited-edition physical prints which could be proved to be limited. So the initial problem was to tie a physical object with its unique ID, a certificate of authenticity and some metadata about the object.

In our current world, any physical object can be copied or faked. Similar technology which allows one to forge a rare edition of Galileo’s scientific work can be used to photocopy certificates as well.

A first idea was to use a split tally stick, with a barcode. An early human invention (Upper Palaeolithic, refined until modern times), split tally sticks were used to record bilateral debts. A stick (squared hazelwood sticks were most common) was marked with a system of notches and then split lengthwise. This way, the two halves both record the same notches and each party to the transaction received one half of the marked stick as proof. The longer part was called stock and was given to the party which had advanced money. In England, tally sticks were in use till the 19th century and we inherited the term “stock exchange” from these small pieces of wood.

Expanding on this idea, I discovered another medieval system which seemed easier to adapt. The chirograph is a medieval document, which has been written in triplicate on a single piece of parchment, with the Latin word “chirographum” written across the middle, and then cut through to separate the parts. Here is an example of such document:


{{< figure src="/images/Final_concord_on_land_in_Lincoln_31_Edw_I.jpg" title="An English property conveyance in triplicate chirograph form, 1303" >}}

So UNCOPIED started with the design of a quintuplicate chirograph to create secure paper labels with a unique ID and QR codes cut in two halves instead of the word chirographum. As the chirograph is made from a single sheet of paper, this physical property of uniqueness can be applied to any object.

For example, the world’s largest drink brand produces 100 billion plastic bottles a year. Let’s imagine they would like to distinguish “the last 100 plastic bottles they will ever produce” and make it a “readymade” in the spirit of Marcel Duchamp. They could use a limited-edition chirographic label. The digital proof of uniqueness is on a public blockchain. The physical proof of uniqueness is distributed among several people, who each own a piece of the chirographic puzzle. With a quintuplicate chirograph, up to four people can participate in a form of consensus (the Famous Drink Brand who issues the certificates, the Collector, UNCOPIED, and a trusted fourth party). Each of these four persons can prove or disprove if the chirographic label comes from a different sheet of paper.

Our initial use case for blockchain technology was to create unique IDs for physical objects and their chirographic labels. The problem of unicity affects NFTs as well: an NFT is essentially a unique ID associated with a unique wallet address. Nothing prevents creating multiple NFTs associated with the same digital object on the blockchain, or even on multiple blockchains. This process (be it “copyminting,” plagiarism, or even self-plagiarism) is really hard to circumvent, as any image or digital object with a tiny difference is effectively a different object. You need a reverse search engine (like Google Image Search or Tineye) to identify similar images.

So the idea gradually became a mission statement: creating an open source solution to certify the authenticity of both physical and digital objects, combining the physical chirograph with QR code, blockchain, IPFS, and a reverse search engine.

**Joey:** I see. So the approach in utilizing open-source technologies is more or less to streamline the process and allow for more open, collaborative authentication of these types of artworks?

**Elian:** Yes, taking into account that this open collaboration should be international from the start. The choice of open source helps with the long term maintainability of a software application stack designed to evolve over a long period of time.

**Joey:** As someone tasked with ensuring the longevity and authentic representation of our digital artworks, I keep apprised of discussions in the digital preservation field. One approach considers the key factors in determining whether a certain format or technology is sustainable, and two of these factors that come to mind when thinking about NFTs and cryptocurrency are “adoption” (as in, how widely it has been adopted and used by am engaged community of users) and “transparency” (for example, open-source versus proprietary platforms). Where do you see these considerations entering into these emerging NFT-related technologies? Is there even any space to consider longevity and sustainability in the marketplace at this point in time, or is it too much of a moving target?

**Elian:** UNCOPIED is an open-source solution built on other open-source solutions or industry standards. We would like our service to include a 10-year “promise” for digital conservation and technical suitability. Obsolescence in IT over a 10-30 year period is almost inevitable: XML and XSD schemas, for example, are now gradually replaced by JSON—although the underlying goals to share data and structure are similar.

Algorand blockchain technology is also an important part of our architecture. Algorand solves the blockchain trilemma (security, scalability, and decentralization) without any compromise, and it cannot fork, which is an important feature for a NFT platform. There are other blockchain networks promising similar levels of efficiency (Tezos, Solana, and others). Once the matter of blockchain efficiency is solved, the issue of storing the digital assets themselves (images, sounds, videos, 3D models) remains.

At this point we see IPFS and GitHub as our key technology for long term storage. IPFS, the InterPlanetary File System, is a distributed storage based on open source software. GitHub is a central player with massive adoption, which has teamed up with other partners to create the Arctic Vault, a very long-term archival facility 250 meters deep in the permafrost of an Arctic mountain.

We see several other players in the market trying to offer on-chain solutions to the problem of permanent public storage. A project like Arweave bet that storage cost will gradually decrease to zero to offer a fixed cost today to store public data “forever.” Other projects like Crust or FileCoin include economic incentives (in the form of crypto “mining”) for storing and sharing data on behalf of the community. It is hard at this point to assess how and when on-chain solutions will address these three requirements: permanent public storage and energy efficiency, but also legitimate censorship to comply with certain legal obligations.

**Joey:** Do you find other players in the NFT market taking these issues of sustainability seriously? Is long-term sustainability of the digital asset a secondary concern?

**Elian:** Yes, I believe the NFT community, starting with the artists themselves, is taking the issue of sustainability seriously. All the more recent NFT “minting” platforms are using Pure Proof-of-Stake blockchains, as they are more energy efficient by about factor of 100,000 and they are cheaper to use as well.

Many older NFT startups who used to mint on Ethereum found it necessary to workaround the platform’s high gas fees and transaction costs. For example Sorare—the collectible football player cards startup which just raised $680 million—is planning to scale out from Ethereum using a Level 2 solution.

But the lower the cost of minting NFTs, the more digital trash we could see coming our way. Do we really need such information logorrhea? With a cost to mint one NFT close to $0.001, every social media post could be a NFT, with high level of digital trash, fakes, and plagiarism. The cost and carbon footprint to mint is negligible compared to the other costs (moderating, storing, indexing, processing), so NFTs could just be an extra layer to our exponential digital consumption.

The concept of NFTs can help us in our quest of digital frugality. After all, if we live in a finite world, the only economic growth that can be infinite is the immaterial—so the quest is worthwhile.

**Joey:** Yes, it will be interesting to see in the long run how questions of digital curation will enter into this discussion, or what questions of value will make these determinations for us.

**Elian:** UNCOPIED is a neutral platform, allowing for diverse content, which reduces the platform’s liability compared to a digitally curated platform. We still have a moral and legal responsibility to respond to inappropriate content reports. A curated platform can be considered legally responsible for the content, in case of copyright infringement or illegal content. The use of distributed ledgers and file systems could be seen as a dilution of legal responsibility. But the moral responsibility remains to whoever introduces new content into our physical or digital world.

Jeff Widener's 1989 “Tank Man” photograph is part of human history—it is priceless. Such an impactful image of tomorrow’s international affairs could be issued as a NFT: it would have a commercial value as well. It will be subject to the same censorship attempts. In 2011, Facebook temporarily censored Gustave Courbet’s 1866 painting The Origin of the World, which portrays a woman’s vulva. Could legitimate censorship decisions be left to algorithms? How do we enforce human governance into the NFT market to balance value, curation, moderation, and conservation?

Distributed file systems could make arbitrary censorship more difficult. Blockchain technology could offer new governance models to support human decisions on legitimate censorship or to recognize value. At least, that’s the optimistic view.

**Joey:** It’s interesting to hear about UNCOPIED and related innovations such as Algorand and the IPFS (Interplanetary File System) in that they seem to take cues from linked open data and ideas around shared ownership and leveraging support. What kind of opportunities exist in bridging the worlds of cryptocurrency and the semantic web?

**Elian:** We collaborate actively with AIS (the Art Identification Standard consortium) which aims to create shared ownership of the artwork identifiers by leveraging the new W3C standards for decentralized identifiers (DIDs) and self-sovereign identity. Self-Sovereign Identity is an emerging concept associated with the way identity is managed in the digital world. According to the Self-Sovereign Identity approach, users should be able to create and control their own identity, without relying on any centralised authority. Applied to the art market, it allows the different actors and stakeholders to make verifiable claims about an artwork about its provenance and authenticity. For example, an artwork can be documented with an x-ray scan that is cryptographically signed, and a potential buyer can verify the identity of the organization who made the x-ray scan.

**Joey:** Are there discussions about multiple-edition NFTs, or shared ownership of a work? What is the distinction between multi-party authentication and multi-party ownership, and what is the potential for linking NFT collections—for example, an artist whose NFT-based work is collected across several owners who are perhaps utilizing it through different blockchain systems. Is it possible to assign one primary author across all these systems?

**Elian:** Metadata is information about other data: it is the data that describes a particular NFT or artwork. It can be as simple as a title, description, image, and a few other properties. Or it could be a much more detailed description, with links to other metadata. We follow the work done by [schema.org](https://schema.org/) for linked open data. We also keep close watch on [linked.art](https://linked.art/) as an emerging metadata standard to describe cultural heritage. For example, with schema.org’s VisualArtwork, the metadata field “artEdition” can be used to describe a limited-edition NFT, which can be interpreted as shared ownership. The artwork can have multiple creators, which can then be interpreted as a collective artwork. [EPOCH, “FREEPORT,” 2021; 1/5](https://algoexplorer.io/asset/245558017) was the first entire virtual Art exhibition sold as an NFT: it corresponds to both those characteristics (a collective artwork, and a sense of collective ownership through a limited edition and artist proofs).

Metadata can be used also to clarify the semantics of tokenization. What does it mean to have a token in one’s cryptographic wallet: does it mean ownership ? Is holding an object the same as owning an object? Does the token owner have any rights to what the object represents? Who is responsible for addressing the aspect of digital obsolescence: the NFT artists, the NFT platform, or the NFT collector ?

Some answers to these very important questions cannot be represented as data or code. They are addressed in various documents (an NFT platform’s terms and conditions, ultimately some legal challenges and decisions). But linked metadata can accrue, and we’ll probably see those provenance documents, legal decisions, expertise reports, et cetera, be gradually standardized and translated into some new metadata.

**Joey:** Agreed, a lot of the more complex discussions we are having around NFT acquisitions have more to do with this question of stewardship and definition of ongoing use than it does the NFT systems technologies themselves. Of course we also feel a need to understand these systems as participants in this exchange. To that end, naturally I am a bit skeptical about the notion of technologies and systems that are driven by capital, particularly when they deal with archives and precious information, but it feels like there might be a shift towards a more open-source mindset with platforms such as Algorand, Arteia, and other systems that make use of the IPFS protocol. But aren’t there other risks to longevity besides that they are built off open standards and languages? Again, thinking about this question of Adoption, is it not essential for all stakeholders to remain invested (or “engaged” might be a better term) in these systems for them to retain their value? Can we be certain that these relationships and the assets themselves can be migrated over into other emerging platforms (open or not) given how quickly the market changes and evolves?

**Elian:** It’s a very good point. Capital-driven organizations may not be the right type of organizations to manage such precious archives. The initial setup is for UNCOPIED to have a mixed model, with the open-source development and the IFPS infrastructure being owned and funded by a non-profit organization (Uncopied Open Collective) and the software-as-a-service business model being operated by a limited company (Uncopied SAS). But there is room also for role sharing with the public sector (an organization such as a national library or national archive). My dream would be for one piece of the quintuplicate chirograph to be stored “forever” at the Library of Congress, the British National Library, or the French National Archives.

Engaging a wide community of stakeholders can be complex. We see some risks that will need to be carefully handled in the near future. There are legal risks around NFTs and crypto inherent to a field of innovation which challenges  traditional legal systems with its motto “the code is the law.” How do you balance long-term conservation of data on IPFS or the blockchain and European law (GDPR and the Right to be Forgotten, for example)? How do you factor the right governance to implement legitimate censorship?

**Joey:** Yes, questions to take with us into the future. One final question for you, Elian. As I understand it, most NFT platforms are fairly siloed even if they are built off of common cryptocurrencies, which perhaps brings up the distinction between “proof of work” and “proof of stake.” I see that UNCOPIED considers ways of protecting the asset and original metadata in an encrypted form but allows for linking and sharing of certain metadata which in effect removes it from this silo. Do you think most blockchain systems desire this kind of open usage or is there a perceived loss in rarified value when things become more open in this sense?

**Elian:** We made a choice to distinguish the UNCOPIED certificate of authenticity token (with digital objects and provenance metadata) and the token which represents the economic value (the NFT). To make a parallel, UNCOPIED is like an “organic” label on a package, which is distinct from the barcode which is used to sell the object.

The UNCOPIED tokens represent an immutable proof of provenance for a physical or digital object. As such they are non-tradable and inalienable. But the token can be moved to a different UNCOPIED wallet to represent the artwork’s change of status, for example, to document a case of legitimate censorship.

Another bold choice we made is to tie the UNCOPIED certificate not just with metadata, but also with a plain-English document. It allows for natural language to express what cannot yet be expressed as metadata or code: the spirit of the law that will govern the smart contract.

This innovative model can be used to break silos across multiple blockchains, as long as there is a bijective one-to-one relation between the certificate token and the value token. For example, a group of artists could get together to aggregate the NFTs they’ve published on different platforms into a new collective artwork. Unless they have given away their intellectual property with the original NFT, they have every right to do so. As long as the metadata for the new artwork links back to the original NFTs, this would no more induce a perceived loss of rarefied value—as when a museum aggregates different artists together for a themed exhibition.

**Joey:** So many possibilities that I hope continue to be a part of the discussion as NFTs continue to work their way within the market! Thank you so much for your time Elian, and looking forward to the next steps for UNCOPIED.

## LACMA UNFRAMED
This article is a Los Angeles County Museum of Art (LACMA) UNFRAMED reblog. You can read the [original article](https://unframed.lacma.org/2021/12/03/nfts-and-museum-part-5-art-collections-blockchain) or its [French translation](/fr/blog/lacma-unframed-nfts-and-museum-part-5-art-collections-blockchain/).

EN->FR translation by [emilymdavis](https://www.fiverr.com/emilymdavis), proofread by DanièleC.