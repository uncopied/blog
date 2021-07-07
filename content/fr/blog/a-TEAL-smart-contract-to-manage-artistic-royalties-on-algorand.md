---
date: 2021-06-04
description: "Uncopied.art contribue deux exemples de contrats intelligents pour gérer le droit de suite et les royalties pour des jetons non fongibles artistiques(NFTs) émis sur Algorand."
featured_image: "/images/photo-1501366062246-723b4d3e4eb6.jpg"
tags: ["Algorand","TEAL"]
title: "Des contrats artistiques intelligents pour les NFTs sur Algorand"
---

## Qui est Uncopied.art

En février 2021, nous avions démontré la faisabilité d'un nouveau type de certificats d'authenticité à plusieurs artistes, galleries et musées. 

Notre prototype combinait un [chirographe](/fr/about/chirograph/) et un jeton non fongible Algorand (Algorand Standard Asset - ASA) pour sécuriser l'unicité et la preuve d'origine d'une oeuvre physique ou numérique. 

Techniquement, le résultat a été concluant, et les retours ont été positifs. Nous avons ressenti une forte attente de la communauté Algorand et artistique pour des NFTs plus écologiques, alors que nous avions prévu un lancement courant mai 2021.

A mesure que nous prenions meilleure connaissance du marché, nous avons réalisé que notre architecture fonctionnelle et technique était trop monolotique.  Cela risquait de limiter notre capacité à nous intégrer avec des partenaires dans l'esprit d'un écosystème fortement décentralisé. 

Aussi, ces derniers mois, l'[équipe](/fr/about/team/) a travaillé d'arrache-pied, pour réécrire Uncopied sous la forme d'une API modulaire et de micro-services Golange performants. l'interface utilisateur (UI) a également été refondue, passant de ReactJS à NextJS. Nous espérons désormais lancer le service d'ici fin juin 2021.  

### Preuve de Provenance et Conservation

Uncopied permet de créer des certificats d'authenticité inviolables pour les oeuvres d'art originales, garantissant l'unicité de l'objet. 

Notre objectif est de participer à l'émergence d'un écosystème artistique nouveau, basé sur la confiance, la preuve de provenance et une [conservation des objets numériques à long terme](/fr/blog/blockchain-museum-collection-inventory/).

Afin de nous refocaliser sur ce coeur de services, nous avons décidé que les actifs Uncopied sur Algorand seraient non négociables mais exclusivement utilisés pour la sécurisation et la conservation. 

Uncopied se place ainsi en dehors du cadre marchand le plus spéculatif des NFTs, pour se focaliser sur la labelisation. Comme tout label de confiance, le label Uncopied se doit d'être inaliénable.

    Uncopied ASA != NFT négociable

Nous restons intéressé par contre dans la collaboration avec les artistes, les galleries, les musuées qui vont eux émettre de plus en plus de NFTs à leur nom. Uncopied apportera le Certificat de Provenance comme label de qualité (en même temps que d'autres services essentiels comme la protecion contre le plagiat et la conservation à long terme.)

Algorand est une plateforme qui sort du lot pour la création des NFTs artistiques. Nous voyons plusieurs projets fantastiques en préparation (des galleries d'art, plateformes de fractionalisation, plateformes de dés-intermédiation des enchères publiques ... ) Nous sommes heureux de collaborer déjà avec certains de ces projets. 


## Cas complexes de royalties et Droit de Suite sur Algorand

Bien qu'Uncopied n'ai pas l'intention de devenir une place de marché pour les NFTs sur le modèle de Rarible ou Opensea, nous voulons cependant que nos solutions s'intègrent facilement avec les cas d'usages les plus complexes en matière de droit d'auteur.

En matière de Droit d'Auteur, le [Droit de Suite](https://fr.wikipedia.org/wiki/Droit_de_suite) est

>le droit, pour l'auteur d'une œuvre d'art graphique ou plastique originale, à percevoir un pourcentage sur le prix obtenu pour toute revente de cette œuvre. Les ayants droit de l'artiste profitent également de la vente des œuvres d'art jusqu'à 70 ans après le décès de l'artiste.

Nous voulions protyper un contrat intelligent (smart contract TEAL sur Algorand) qui permettrait de gérer un cas réel complexe pour une oeuvre collective. Nous étions également particulièrement intéressé d'examiner la faisabilité pour ce contrat de continuer de s'exécuter dans le cadre d'enchères publiques sur une plateforme d'échanges décentralisée (place de marché ou DEX).  

Nous avons contacté [Jesulonimi Akingbesote](https://github.com/Jesulonimi21) pour nous aider. Jesulonimi est un Google Associate Android Developer et primé de l’Algorand Development Award. 

Nous sommes parti des exemples et tutoriels Algorand,
- Assets and Custom Transfer Logic by Jason Weathersby, Algorand (https://developer.algorand.org/solutions/assets-and-custom-transfer-logic/)
- AlgoRealm, a NFT Royalty Game by Cosimo Bassi, Algorand (https://developer.algorand.org/solutions/algorealm-nft-royalty-game/)

Nous avons mis en ligne sur Github deux exemples à destination de la communauté Algorand,
- un cas simple, où l'artiste perçoit une commission sur toutes les ventes du marché secondaire (https://github.com/uncopied/smart_contract)
- un cas sophistiqué, en partenariat avec [EPOCH Gallery](https://epoch.gallery/), où le contrat prévoit une répartition des royalties entre au moment de la vente initiale puis lors des ventes successives entre la gallerie et les sept artists, selon une clé de répartition personnalisée (https://github.com/uncopied/epoch_smart_contract)

Ces deux contrats intelligents sont distribués sous une license open source Apache 2.0 au bénéfice de tous. 

Vous trouverez ci-dessous des explications complémentaires (en anglais)

{{< youtube id="674lob3OsmQ" autoplay="false" >}}

N'hésitez pas à contribuer vos commentaires, suggestions ou corrections sur Github. Merci par avance de nous informer si vous voyez des dysfonctionnements possibles du contrat intelligent. 

Photo par Jeremy Bishop sur Unsplash.
 
