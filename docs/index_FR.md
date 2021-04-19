
> **⚠ ATTENTION: Le contenu qui suit est sujet a des modifications et n'est pas encore final.** 

# Galital: La galaxie digital

## clause de non-responsabilité:

**Les technologies de la blockchain et du jeu vidéo sont en constante évolution. Ce papier blanc décrit le dévelopement le mieux possible, toutefois du à la nature de la technologie et la complexitée de l’intégration du monde de la 
blockchain et du jeux vidéo le présent document peut être sujet à des changements. Nous essayons de nous rapprocher au maximum du plan initial, mais parfois des modifications sont nécessaires afin d’améliorer l’expérience utilisateur
 et surmonter les barrières technologiques rencontrées au cours du développement..**



## 1. Introduction

La fracture numérique a commencé depuis plusieurs années et le monde tend à se digitaliser progressivement. La majorité des paiements se font désormais en ligne et on achète de plus en plus de produits digitaux. 
Cependant, la propriété de ces biens n'appartient que rarement aux acheteurs. Les jeux numériques que vous avez sur votre compte Steam, PS store ou autres ne vous appartiennent pas réellement. 
L'arrivée des NFT (Non Fongible Token) a révolutionné le biens digital et permet une vraie propriété au sein de la blockchain. Les NFT vous appartiennent et vous êtes libre d’en disposer comme bon vous semble. 
Cependant, la vente, l’achat ou l'échange de NFT n’est hélas pas accessible à tout le monde encore. Entre la difficulté d’utilisation des différents marketplace et notamment le coût grandissant des frais annexes, 
les NFT sont devenues réservées au moyen et gros portefeuille. Avec l'arrivée des NFT utilitaires (dans le jeux vidéo par exemple) il est devenu crucial de transformer notre façon d'échanger les NFT afin de les rendre 
facile d'accès pour tout un chacun, que ce soit sur le plan de l’utilisation que sur les frais associés. 


> C’est sur ce constat qu'est né Galital. Un écosystème permettant de démocratiser l’utilisation des NFT en créant une plateforme NFT basée sur Polkadot et le framework substrate. 
> L'élaboration de Galital repose sur plusieurs composants essentiels : 


###   **La Factory**

Rendre la création et le déploiement de NFT simple, rapide et accessible aux artistes, créateurs de contenu, studio de jeux vidéo ou tout un chacun.
###   **Le Hub **

Permettre l’interconnexion des NFT entre les différentes chaînes, que ce soit vers La Binance Chain, Ethereum, Avax, Polkadot ou encore Flare, le but du Hub est de rendre la transition cross-chain simple et accessible.
###  **Le Market **

Véritable composant principal de l'écosystème, le market permet la vente, l’achat ou l'échange de NFT, que ce soit via enchère ou simple listing. Les utilisateurs ont également la possibilité de pouvoir s'échanger directement des NFT. 
Enfin, grâce au DeFi, le market permet le borrow et lending de NFT.
###   **la Forge  **

Le domaine du Sharding. C'est l'endroit où la magie opère et permet de casser ses NFT en plusieurs éclat ou "Shard". C'est également ici que vous pouvez reformer un NFT si vous possédez tout ses "Shards".
###   **Le Vault **

Permet de placer ses NFT en collatéral afin de récupérer des Tokens
###   **Le Home ** 

dashboard permettant de gérer ses NFT.

###   **L'arcade**

C'est ici que vous trouverez tous les jeux vidéo développés par Galital ainsi que les jeux des autres studios qui utilisent l'écosystème Galital.


## 2. Gouvernance et trésorerie

Galital est basé sur le framework substrate, de ce fait, il bénéficie d’un vrai système de gouvernance décentralisé construit directement au sein de la blockchain elle-même. 
Il permet entre autres à n’importe quel détenteur de $TAL de pouvoir faire entendre sa voix dans l'évolution de l'écosystème. Via la gouvernance, il est possible de soumettre des propositions afin de faire évoluer Galital, 
des missions pour permettre de diriger le développement des différents produits ou encore de proposer des pourboires afin de récompenser le travail effectué par la communauté.

![drawing](assets/governance-treasury.png)

La gouvernance se découpe en 3 groupes distinct : 

![drawing](assets/parlemient.png)

*   Le comité technique assure la stabilité et la sécurité de la blockchain. Ils sont donc en mesure de soumettre des motions d’urgence auprès du conseil, une fois validés par le conseil, ces motions s'appliquent dans un délai plus court que les motions classiques.Cette chambre est réservée aux membres ayant une excellente connaissance de la blockchain et du code source de Galital.
*   Les membres du conseil votent les motions et les dépenses de la trésorerie (mission / pourboire). Leur rôle est central et leur mission est de faire évoluer l'écosystème en validant les propositions faites par la communauté. Ils sont élus par la communauté et leur mandat dure 7 jours actuellement. Les sièges du conseil sont ouverts et n’importe quel détenteur de $TAL peut soumettre sa candidature.
*   Les détenteurs de $TAL peuvent quant à eux voter pour élire les membres du conseil, faire des propositions afin d’améliorer la blockchain, proposer des missions ou encore en effectuer. Ils sont le cœur de Galital et c’est grâce à eux que l'écosystème évolue et avance plus loin.

C’est grâce à ce système de gouvernance que les utilisateurs de Galital peuvent avoir un impact fort dans l'évolution de l'écosystème. Ce n’est plus une seule entité qui a le pouvoir, mais la communauté toute entière. 
Afin de supporter les différentes évolutions de la blockchain, la trésorerie est un mécanisme crucial permettant à Galital de subvenir à ses besoins sans l’aide d’un tiers. 
Elle permet essentiellement à la communauté de pouvoir mettre en place des missions rémunérées afin de développer de nouveaux produits, de faire du marketing, d’ajouter de nouveau bridge ou tout autre proposition jugée pertinente 
par les membres du conseil et validée par la communauté.


## 3. Placement et sécuritée de la chaîne (Staking)

N’importe quel détenteur de $TAL peux participer au staking afin de sécuriser la blockchain. En contrepartie de cette contribution, les stakeur reçoivent des récompenses en $TAL. Il existe 2 rôles distincts : Validateur et Nominateur .
 
###   3.1	Validateur


Les validateurs sécurisent la chaîne relais en bloquant des $TAL permettant de valider les preuves des collators et en participant au consensus avec les autres validateurs.


Ceux-ci joueront un rôle crucial dans l’ajout de nouveaux blocs a la chaine relais et par extension, à toutes les chaînes secondaires. Cela permettant ainsi aux parties d’effectuer des transactions interchaine via la chaîne relais. 

Les validateur remplissent 2 fonctions: 


*   Ils vérifient les informations contenues dans un ensemble assigné de blocs provenant de chaînes secondaires afin de déterminer leur validité (telles que l’identité des parties de la transaction et l'objet du contrat).
*   Ils participent aux mécanismes de consensus afin de produire les blocs de la chaîne relais en se basant sur les déclarations de validité des autres validateurs. 

Dans le cas de non-conformité aux algorithmes de consensus, le validateur est sanctionné via la suppression d’une partie ou de la totalité des $TAL bloqué sur celui-ci. Ce mécanisme permet ainsi de décourager les acteurs belliqueux. 
A contrario, le respect et les bonnes performances sont récompensés par la blockchain.


Il y a actuellement 100 places de disponible pour les validateurs. Afin d'être élus par le réseau et ainsi créer de nouveau blocs, les validateurs doivent être dans les 100 premiers en termes de $TAL bloqué (validateur + nominations). 
Si un validateur n’est pas élu par le réseau, il ne procédera à aucun travail et ne recevra aucune récompense. 



En contrepartie de leur contribution, les validateurs reçoivent les récompenses du bloc (nouveau $TAL créé, basé sur le système d’inflation fourni par le réseau) ainsi que 20% des frais de transaction (le reste allant à la trésorerie). 
Ces récompenses sont  réparties entre le validateur et ses nominateurs en fonction de leurs parts respectives (moins la commission fixé par le validateur afin de couvrir les frais de maintenance) 



### 3.2 Nominateur


Les nominateurs sont responsables de la désignation de leur participation auprès des validateurs. En bloquant leurs $TAL sur des validateurs, ils permettent à ceux-ci d'être choisi par le réseau afin de créer des nouveaux blocs et 
partagent ainsi les récompenses et les pénalités associées. 



Alors que les validateurs sont des participants actifs du réseau qui prennent part aux mécanismes de production et de finalité des blocs, les nominateurs jouent un rôle plus passif avec une approche de délégation. 
Il n’est donc pas nécessaire d’avoir des connaissances techniques ou de posséder du matériel spécifique. Cependant, un bon nominateur fait preuve de sagesse à l'égard des validateurs qu’il choisit en faisant attention à son propre 
pourcentage de récompense ainsi qu’au risque d'être sanctionné si le validateur agit de manière belliqueuse. Les nominateurs sont récompensé en fonction du nombre de part qu’ils détiennent sur le validateur (moins les frais de commission) 


## 4. La Factory

La factory est un composant essentiel de l'écosystème Galital, il permet entre autres de créer et déployer de manière simple et rapide ses propres NFTs. Grâce à un design d'interface ergonomique, créer des NFTs devient un jeu d’enfant 
et à la portée de tous. Que vous soyez artiste, créateur de contenu, développeur de JV ou passionnée, la factory est faite pour vous simplifier la vie et vous faire gagner un temps précieux, vous permettant de créer à l'infinie, 
en un claquement de doigts.



Il sera également possible, lors de la création d’un NFT, de choisir un % de royalties qui seront payé au créateur pour chaque transaction du dit NFT dans le market de Galital. Ce système permettra aux créateurs de bénéficier 
d’un revenu supplémentaire leur incitant à partager leurs créations.




## 5. Le Hub (Les bridges entre chaînes + UI)

Le Hub est l’espace dédié pour les bridges cross-chaîne. C’est ici que les utilisateurs vont pouvoir transférer leur NFTs entre les différentes chaînes supportées par Galital (la liste évoluera en fonction des choix de la communauté).
Dans un premier temps, les transferts depuis et vers Ethereum, BSC, Avalanche, Polkadot, Matic et Flare seront disponibles. Permettant ainsi au utilisateur de pouvoir transférer librement leur NFT pour pouvoir les utiliser directement 
dans l'écosystème Galital et notamment le market. Le transfert et le flow s'effectue simplement, l’utilisateur aura une interface graphique ou il pourra sélectionner la chaine d’origine et la chaîne de destination pour le transfert 
des NFTs ou de token, l’utilisateur signe ensuite la transaction est procédée par le réseau d’oracles ( Galital utilisera la technologie de ChainSafe ), et transfert les assets sur la chaîne désirée.


## 6. Le Market

Le market est le point central de Galital, c’est ici que les utilisateurs pourront vendre ou acheter des NFTs. La force du market repose sur sa simplicité d’utilisation et sa diversité, il sera possible au vendeur de choisir la 
crypto qu’il souhaite recevoir en paiement et l’acheteur pourra payer dans la crypto de son choix, grâce à un système de DEX intégrer, les achats seront fluides, fini le temps ou il vous fallait convertir vos ETH en DAI car le NFT 
de votre choix n'était listé que en DAI. Fini les gas fee exorbitant, votre achat se fait désormais en un clic et vous pouvez alors acheter vos NFTs quand vous le souhaitez, rapidement et en toute simplicité. 



Lors d’une vente, 2 frais sont déduit de la vente : 

*   Les fees pour le market : 2.5%
*   Les fees pour le créateur : défini par celui-ci lors de la création du NFT.


Les frais du market peuvent être réduit lors d’un paiement en $TAL ainsi qu’en possession de NFT spéciaux. Cumulé il peuvent même atteindre une réduction de 100%. Cependant, les fee pour le créateur ne peuvent eux pas être réduit. 



Les utilisateurs ont également la possibilité d’effectuer une vente privée (le NFT ne peut être acheté que par l'adresse spécifiée par le vendeur). Dans  ce cas, uniquement les frais pour le créateur sont déduits. 




## 7. Le Vault

Le vault est l’endroit idéal pour stacker ses NFTs afin de farmer des nouveaux tokens. Que ce soit pour gagner des monnaies en jeu ou d’autres crypto, le vault vous permet de bloquer vos NFTs pendant une certaine période 
afin de les faire travailler eux aussi. 



## 8. Fractional NFT System

> Galital intends to implement fractional NFT in order to push the NFT beyond the limit and unlock a bunch of new possibilities.


### Propriété fractionnée (Sharding)

Le NFT fractionné (ou le "Sharding") permet de partager la propriété des NFT. Vous voulez une épée epique dans un jeu mais vous ne pouvez pas vous la payer ? Ou peut-être qu'un Cyberpunk attire votre attention depuis longtemps mais il est bien trop cher 
pour l'acheter seul ?

Le NFT fractionné vous permettra de prendre une part sur ces NFT. C'est encore plus utile lorsque vous voulez profiter des avantages de la DeFi grace au NFT. En effet, ce system vous permet de prendre des parts fractionnées afin de 
percevoir un revenu via le système de prêt, vous permettant ainsi de beneficier de tous les avantages de la DeFi assoicés aux NFTs.

Ce système offre de nombreuses possiblités qui vont bien au-delà de ce document. Si vous êtes un joueur de MMO, vous voudrez certainement l'utiliser pour acheter des NFTs en tant que guilde et les partager avec vos membres. Plus loin encore,
les développeurs de jeux pourraient développer des contrats intelligents qui permettront aux guildes de posséder un NFT et de le partager automatiquement avec les membres de celle-ci en fonction de leur rang. Grâce à ça, vous pourrez désormais
posséder un NFT en tant que guilde, le louer ou le vendre et tout cela sera partagé entre tous les membres.
Vous pouvez aussi simplement partager un NFT avec vos amis ou votre communauté et l'utiliser en jeu chacun votre tour.

C'est un grand pas en avant pour l'industrie du jeu et offre de nombreuses possiblités de **jouer**, **posséder** et **gagner** ensemble.


### Découverte des prix du marché

Le "Sharding" permettra également d'améliorer et de rendre plus saine la découverte du prix des NFTs. Les "shards" seront directement drivé par le marché et échangées comme n'importe quel token. Si un utilisateur veut prendre la pleine 
propriété d'un NFT fractionné, il lui suffira d'obtenir toutes les "shards" de celui-ci afin d'être en mesure de le reformer grace à la forge. Il sera également possible à tout moment de casser un NFT en n'importe quel nombre de "Shards" 
permettant ainsi de donner plus rareté à un seul NFT.
	


## 9. La forge

La forge est l'endroit idéal pour casser ses NFTs en éclats (ou "Shards"). Il est possible de choisir la rareté (le nombre de shards produit : 10, 100, 1000, etc..). Ensuite, les "Shards" peuvent être distribué ou vendu via le Market comme 
un token. Cela donnera par exemple la possibilité aux créateurs de jeux vidéo d'améliorer la rareté de leur NFT tout en permettant à un plus grand nombre de personnes d'y acceder.

Lorsque vous avez collecté tous les "Shards" d'un NFT, vous pouvez aller sur la forge et les fusionner afin de reformer le NFT original.

## 10. Prêter / Emprunter

En plus de simplifier considérablement l'achat et la vente de NFTS, le marché permettra également aux utilisateurs de louer ou prêter leurs NFT. Vous souhaitez obtenir un objet de valeur dans un jeu pour un certain temps ? 
Vous possédez des terres que vous aimeriez mettre à disposition ? Un ami a besoin d'un NFT en votre possession temporairement ? Le marché vous permettra d'effectuer toutes ces actions et bien plus encore, de manière simple et sécurisée.
Plus besoin d'envoyer vorte NFT pour le prêter. Un nouveau champ de possiblités s'offre a vous avec Galital.

## 11. Le Home

Le home fait office de dashboard pour gérer vos NFTs. C’est ici que vous aurez la possibilité de voir vos NFTs, gérer vos assets c’est votre panneau de contrôle principal. 
De cet emplacement vous pourrez gérer toutes les applications, créer des tokens, acheter / vendre sur le marketplace.


## 12. Contracts intéligents

Étant donné que Substrate prend en charge les contrats intelligents Wasm, cela signifie que tout langage pouvant compiler vers Wasm peut être utilisé pour écrire ces contrats. ink! est la réponse de Parity pour rédiger des contrats 
intelligents en utilisant le langage de programmation Rust.



ink! est un langage spécifique au domaine intégré (eDSL) basé sur Rust pour la rédaction de contrats intelligents Wasm spécifiquement pour la “Contrats pallet”. 
Les principaux objectifs de INK! sont la convivialité, la concision et l'efficacité.



### 12.1 Composants du contrat


ink! devrait se sentir familier aux développeurs qui ont programmé en utilisant d'autres langages de contrat intelligents modernes. Le squelette d'un contrat à tous les mêmes composants auquel vous pourriez vous attendre:

*   Événements
*   Espace de stockage
*   Fonction de déploiement (constructeur)
*   Fonctions publiques
*   Fonctions internes


Dans ink !, la mutabilité et la visibilité sont explicitement définies par fonction de contrat. Dans ces fonctions, vous avez accès à un certain nombre de types de Substrate courants tels que AccountId, Balances, Hash, etc. 


De plus, vous avez accès à des variables d'environnement couramment utilisées comme l'appelant, et plus encore!


### 12.2 Design


Les principaux objectifs de ink! sont l'exactitude, la concision et l'efficacité.

inking! est conçu pour être aussi proche que possible du langage de programmation Rust. Le langage utilise des macros d'attributs pour baliser les structures Rust standard en composants de contrat compréhensibles.

Parce que ink! suit les normes Rust, des outils comme rustfmt et rust-analyzer fonctionnent déjà nativement.


### 12.3 Sécurité d’overflow


Être écrit en Rust, INK! peut fournir une sécurité de dépassement / sous-dépassement lors de la compilation. À l'aide d'une configuration de compilateur Rust, vous pouvez spécifier si vous souhaitez prendre en charge 
les débordements mathématiques ou si vous voulez que l'exécution du contrat panique en cas de dépassement. Pas besoin d'importer continuellement des bibliothèques "Safe Math", bien que Rust propose également des fonctions 
mathématiques vérifiées, encapsulées et saturées intégrées.


Remarque: il existe des problèmes connus concernant la fonctionnalité des vérifications de dépassement de capacité au niveau du compilateur et la taille résultante de l'objet blob Wasm. 
Cette fonctionnalité peut changer ou être réitérée à l'avenir.



### 12.4 Environnement de test


INK! fournit un environnement de test intégré qui peut être utilisé pour effectuer des tests unitaires hors chaîne avec le framework Rust. Cela permet de garantir simplement et facilement que votre code de contrat fonctionne comme prévu, 
sans avoir besoin de plates-formes de test tierces.


### 12.4 ink! vs Solidity 


Rust est un langage de contrat intelligent idéal. Il est de type sécurisé, sans danger pour la mémoire et exempt de comportements indéfinis. Il génère de petits fichiers binaires car il n'inclut pas de ballonnement supplémentaire, 
comme un garbage collector, et les optimisations avancées et supprime le code mort. Grâce aux indicateurs du compilateur, Rust peut se protéger automatiquement contre le dépassement d'entier.


INK! choisit de ne pas inventer un nouveau langage de programmation, mais plutôt d'adapter un sous-ensemble de Rust pour servir cet objectif. 


En conséquence, vous bénéficiez de tous les outils et de l'assistance disponibles gratuitement pour l'écosystème Rust. De plus, à mesure que la langue se développe, INK! aura automatiquement accès à de nouvelles 
features et fonctionnalités, améliorant ainsi la façon dont vous pourrez rédiger des contrats intelligents à l'avenir.



Voici une brève comparaison des fonctionnalités entre INK! et Solidity:


<table>
  <tr>
   <td>
   </td>
   <td>
<strong>ink! </strong>
   </td>
   <td><strong>Solidity </strong>
   </td>
  </tr>
  <tr>
   <td>Virtual Machine
   </td>
   <td>Any Wasm VM
   </td>
   <td>EVM
   </td>
  </tr>
  <tr>
   <td>Encoding
   </td>
   <td>Wasm
   </td>
   <td>EVM Byte Code
   </td>
  </tr>
  <tr>
   <td>Language
   </td>
   <td>Rust
   </td>
   <td>Standalone
   </td>
  </tr>
  <tr>
   <td>Overflow Protection
   </td>
   <td>Enabled by default
   </td>
   <td>None
   </td>
  </tr>
  <tr>
   <td>Constructor Functions
   </td>
   <td>Multiple
   </td>
   <td>Single
   </td>
  </tr>
  <tr>
   <td>Tooling
   </td>
   <td>Anything that supports Rust
   </td>
   <td>Custom
   </td>
  </tr>
  <tr>
   <td>Versioning
   </td>
   <td>Semantic
   </td>
   <td>Semantic
   </td>
  </tr>
  <tr>
   <td>Has Metadata?
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td>Multi-File Project
   </td>
   <td>Planned
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td>Storage Entries
   </td>
   <td>Variable
   </td>
   <td>256 bits
   </td>
  </tr>
  <tr>
   <td>Supported Types
   </td>
   <td><a href="https://substrate.dev/docs/en/knowledgebase/advanced/codec">Docs</a>
   </td>
   <td><a href="https://solidity.readthedocs.io/en/latest/types.html">Docs</a>
   </td>
  </tr>
  <tr>
   <td>Has Interfaces?
   </td>
   <td>Planned (Rust Traits)
   </td>
   <td>Yes
   </td>
  </tr>
</table>



## References


* [https://substrate.dev/docs/en/knowledgebase/smart-contracts/](https://substrate.dev/docs/en/knowledgebase/smart-contracts/)
* [https://substrate.dev/docs/](https://substrate.dev/docs)

   