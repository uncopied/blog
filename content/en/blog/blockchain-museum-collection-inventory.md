---
date: 2021-02-13
description: "Aftermath of COVID-19 : cultural heritage at risk"
featured_image: "/images/joconde-oh-no-min.jpg"
tags: ["security","conservation"]
title: "Can the blockchain help secure museum collections?"
---

## Preparing for the aftermath of COVID-19: our cultural heritage is at risk

A 2011 survey by [ICCROM/UNESCO](http://www.unesco.org/new/en/culture/themes/dynamic-content-single-view/news/stored_but_not_safe_museum_collections_are_at_risk_worldwid) has revealed that up to 60% of museum collections are endangered globally. Storage overloads, poor conditions for conservation and budget constraints contribute to risk factors. 95% of a museum’s collections are kept in storage. Billions of objects are kept away from public sight. 
One in four museums have [incomplete documentation systems](https://www.iccrom.org/section/preventive-conservation/re-org). One in 10 museums, or less, have made their entire collections digitally accessible with pictures and metadata. Barely 0.1% of museums disseminate metadata in a usable format (such as CSV, XML or JSON). 


As of February 2021, COVID-19 has already had an unprecedented impact on tourism worldwide, placing further pressure on heritage conservation. 90% of countries have closed World Heritage Sites with immense socio-economic consequences for communities reliant on tourism. Furthermore, 90% of museums closed and [13% may never reopen](https://news.un.org/en/story/2020/05/1064362).


An economic crisis may still be ahead of us, one which undermines the public government’s ability to finance conservation, placing many museums in a situation where the risks are multiplied (civil unrest, fraud, corruption, etc.) and already strained resources are diminished (time, budget, money). In such a challenging environment, the risks for the objects in storage to be destroyed or illegally sold is increased tenfold. 


To prevent such threats, the periodic inventory of collections is an essential process: maintain accurate descriptions, pictures and scientific documentation, verify identifications and markings, check if the collection database is up to date and ensure the physical security of objects. In a budget-constrained situation, databases and backups can be lost too. Even harder to spot, data tampering is the act of deliberately modifying (destroying, manipulating or editing) data through unauthorised channels. 


Every one of the 25 collection management systems listed in the [Collections Trust](https://collectionstrust.org.uk/software/) and Wikipedia use a relational database, vulnerable to data loss or tampering. Only one new entrant, [Arteïa](https://www.journaldeleconomie.fr/Olivier-Marian-Arteia-%E2%80%89Une-solution-de-catalogage-et-de-gestion-des-collections-d-oeuvres-d-art-pour-les_a7249.html), offers native protection against data tampering using public blockchain technology. Some institutions have used GitHub as a tamper-proof and long-term archive for their collection's metadata: [Williams College Museum of Art](https://github.com/wcmaart/collection) (WCMA), [The Tate](https://github.com/tategallery/collection),  [The Museum of Modern Art](https://github.com/MuseumofModernArt/collection) (MoMA), the [Minneapolis Institute of Art](https://github.com/artsmia/collection), the [Carnegie Museum of Art](https://github.com/cmoa/collection), [Cooper Hewitt](https://github.com/cooperhewitt/collection) Smithsonian Design Museum and The [Metropolitan Museum of Art](https://github.com/metmuseum/openaccess). These GitHub repositories have all been preserved in the Arctic Code Vault, a very long-term archival facility 250 meters deep in the permafrost of an Arctic mountain – so their conservation is as safe as it can be. Unfortunately, there is no simple way for the ordinary citizen, other than a computer-savvy ‘geek’, to query such data or metadata.


Sadly, they are often incomplete. Even when the collections database is made public, the object’s metadata is not systematically linked to the object’s picture. A vivid example is the French museums' [JOCONDE database](https://data.culture.gouv.fr/explore/dataset/base-joconde-extrait/export/), which is accessible as open-data in a reusable format (CSV, JSON, XML), but the other digital assets (low-definition or high-definition pictures) are distributed separately on each museum’s web site – if at all.  

Some museums are more affected than others. Museums in Africa are in an extremely difficult situation. The [National Museum of Mali](https://musee-national-mali.org/), for example, had to cope with a long sequence of negative events since 2012 (Mali security crisis, political instability, COVID-19, etc.)

## Can virtual visits help restore a museum’s financial stability?

As museums were closed to visitors worldwide, many new technologies have emerged to allow virtual visits. High-tech gadgets (virtual reality in 3D, 5G, etc.) promise to immerse visitors in the museum’s permanent collections, or even to discover collections in the storage rooms. 


A recent 5G promotional campaign by a French telecom company, Orange, shows pupils visiting Le Louvre and (virtually) [ransacking the museum](https://www.universfreebox.com/article/60345/orange-devoile-sa-nouvelle-publicite-pour-la-5g-et-ses-promesses-d-innovation). Let’s hope those virtual visits do not replace the ‘real’ thing: pupils discovering in person Le Louvre for the first time with their teachers and friends and learning to respect their cultural heritage. 


In this virtual world, the objects can exist, be magnified and be digitally restored using Instagram-like filters – while the physical objects are forgotten. 


It is still unclear what the economic model will be for such innovation, and how museums will financially benefit from those virtual visits. Can virtual visits or digital licensing rights compensate for the loss of physical visitors and help finance physical object conservation? Or will those new technologies divert funding from conservation towards activities with a more direct return on investment? This would be dangerous.


## So, is it all doom and gloom? 

Technology can help! Here are some ideas:

### Museums could embrace open-source software

Open source software is not free. You still have to install and maintain it, but used wisely it can help keep IT costs at bay. It offers the flexibility to create highly customised solutions. Open-source collections management software include CollectionSpace and GlamKit. [CollectionSpace](https://collectionspace.org/) is maintained by [Lyrasis](https://www.lyrasis.org/), a non-profit organisation focused on enabling equitable access to the world’s knowledge and cultural heritage.​ For content management systems (CMS), [The Interaction Consortium](https://interaction.net.au/) has incorporated considerable expertise when building GlamKit and has now turned [Wagtail](https://wagtail.io/) into a CMS for museums by extending it. A very comprehensive comparison of [collections management systems](https://www.canada.ca/en/heritage-information-network/services/collections-management-systems.html) was done by the Governement of Canada between 2016 and 2019.

### Museums could store digital assets on GitHub or IPFS

Storing large digital assets reliably is costly. As an example, the French National Library has built the highly redundant infrastructure [SPAR](https://www.bnf.fr/fr/infrastructure-materielle-de-spar-systeme-de-preservation-et-darchivage-reparti) , and replicated it across several locations to preserve digital assets in the long term. There were probably no better alternatives at the time, and with a €220 million yearly budget, the BNF can afford to maintain such costly infrastructure. But, if an organisation were to design a digital archive today, it would be possible to use alternative solutions such as GitHub or the [InterPlanetary File System](https://en.wikipedia.org/wiki/InterPlanetary_File_System) (IPFS). Those solutions offer the same level of redundancy, at a fraction of the cost. It is possible to rely on the community to participate in the distributed cluster and provide additional redundancy against extreme disasters (such as earthquakes or floods).

### Museums could adopt standards for metadata

Structuring data is complex, every museum has different types of objects. Describing those objects in a consistent way is not a piece of cake. Currently, every museum reinvents the wheel when it comes to describing its collections, or just translate what was on a paper trail to a digital format (such as XML or JSON or CSV). But museums could get together and build a standard that works for the next 100 years. For that, they could re-use and expand on Schema.org or Europeana. Using Schema.org definitions to describe objects helps reach internet visitors, as Schema.org powers the semantic web and speaks to the ears of the Google Search Engine. For example, the [VisualArtwork](https://schema.org/VisualArtwork) schema describes any work of art that is primarily visual in character (painting, photography, etc.). The Europeana [Data Model](https://pro.europeana.eu/page/edm-documentation) is a huge collaborative effort that has involved over 60 participating museums, and it works! Museums can use Europeana as a new distribution channel, working with an [aggregator](https://pro.europeana.eu/page/aggregators) to publish their collections. 


## UNCOPIED ART value proposition for collections inventory

UNCOPIED expands on the availability of existing collections management software, but it adds an extra layer of security against tampering. It facilitates the dissemination of open data. It uses blockchain technology to add transparency to the object’s lifecycle and status (ex. lending/borrowing, acquisition or sale, theft, loss or destruction, etc.). 
UNCOPIED Certificates of Inventory links a physical object with a tamper-proof artwork identifier, immutable and permanent storage for photographs and metadata. 


The UNCOPIED label is printed on a quintuplicate chirograph with a RFID/NFC chip. In some cases, the label can be directly stuck onto the object in compliance with the labelling and marking best practices of the [Collections Trust](https://collectionstrust.org.uk/resource/labelling-and-marking-museum-objects-booklet/), the [French Ministère de la Culture](https://www.culture.gouv.fr/Media/Thematiques/Circulation-des-biens-culturels/Files/Ressources-doc-Guides-et-procedures/Guide-Marquage-des-collections-publiques-MCC-2008) or [ICOM International Observatory on Illicit Traffic in Cultural Goods](https://www.obs-traffic.museum/). But in most cases, UNCOPIED does not change anything to the existing object identification, labelling and marking. One photographic print of the object with the UNCOPIED label glued to its back acts as a proxy for the original object: it can be placed on display when the object is on loan or being restored. The object’s lifecycle and status can be accessed at any time by scanning the QR Code or NFC chip from a standard smartphone. 

Physical inventory certificates are quadruplicate documents secured by the chirograph and archived in multiple copies by the Museum, by UNCOPIED and by a trusted third-party. In France, for example, only 20 companies or so have [accreditations to archive papers](https://francearchives.fr/fr/article/26287437) on behalf of the government.
The UNCOPIED digital certificate is a legible document secured using the Algorand blockchain, creating an [Algorand Standard Asset](https://medium.com/algorand/algorand-standard-assets-efda8afcfc0a) (ASA – the equivalent of NFT for Ethereum Blockchain). Algorand is a new generation of blockchain technology that is secure, distributed and scalable. 
Metadata, or any digital asset referenced by the object’s metadata, is saved in a long-term storage distributed database [IPFS](https://ipfs.io/) (the Interplanetary File System). High-definition and low-definition images can be distributed with different licences to comply with copyright laws (ex. ‘All Rights Reserved’ for high-definition images and ‘Creative-Commons’ for low-definition images). 


As part of UNCOPIED’s open-source development, the roadmap includes developping a connector to synchronize with both IPFS and GitHub and benefit from its GitHub's very long-term archival facility. Opening the collections’ metadata to public scrutiny using open data, as many museums have done on GitHub, offers a strong level of protection. It also reinforces the collective sense of ownership and responsibility towards preserving cultural heritage. 


## Benefits of UNCOPIED Certificates of Inventory
-	UNCOPIED adds an extra layer of security to existing collection management systems, thus re-using existing museum investments and not requiring any complex new software installation.
-	Museums can more easily disseminate public data about their collections in future-proof formats and standards such as JSON.
-	Checking the inventory becomes a more transparent process which is open to public scrutiny and creates additional levels of security for the long term preservation of the 95% of the museum’s collections that are kept in storage.
-	Visitors can scan a QR Code and access additional information about an object in the public collections: when was it acquired? How is the object documented or cross-referenced? Any restoration work, borrowing or lending is recorded in the traceable log of the blockchain. 
-	No single person can tamper with the critical data elements, such as the artwork ID, the photographs or the metadata. In case of fraud or looting, the object‘s stolen status is quickly communicated globally. 


We plan to soft launch [UNCOPIED](https://uncopied.org/) in April 2021.

 
