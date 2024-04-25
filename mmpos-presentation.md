# Présentation mmpOS

## En résumé :

- Le même principe que Hiveos
**- LES RIGS CPU SONT GRATUITS ET ILLIMITES EN NOMBRE !!** 🥳 
- Le mineur Qubic est nativement disponible !
- C'est le nombre de GPU qui est compté pour l'offre gratuite, peu importe le nombre de rigs. (Gratuit pour 8 GPU/jour)
- c'est basé sur ubuntu 22.04.
- le mineur Qubic officiel y est intégré, pour GPU et CPU (aucune bidouille, ça marche direct)
- gestion des OC plus complète (l'interface de mmpos permet de faire tout ce que fait nvtool en gros)
- plus d'options possibles dans les flight sheets (exécuter une commande au démarrage, modifier la commande du mineur, utiliser n'importe quel exécutable comme mineur custom...)

J'ai passé mes 3 rigs chez eux après un test sur l'un des rigs pour ne pas basculer mon compte hiveos en payant ^^

Les inconvénients qu'il peut y avoir :
- Pas d'appli mobile
- Pas de schedule ? (J'ai pas trop cherché)
- Pas en Français 😛

## Combien ça coûte ?

C'est ce qui m'a fait passer chez eux, j'avais 3 rigs mais 4 GPU (config pour miner Qubic et Warthog)
En résumé, le tarif dépend du nombre de GPU que vous possédez :
- On a le droit à **8 GPU gratuits** quelque-soit le nombre de rigs. (Que vous ayez un seul rig de 8 GPU ou 8 rigs avec 1 GPU, c'est gratuit).
- Ce qui veut dire que tout ce qui n'est pas un GPU (**CPU**, FPGA, ASIC) est **gratuit et illimité en nombre !**
- Si vous faitez un premier paiement, la limite passe à **14 GPU gratuits par jour** 🙂

La tarification fonctionne avec un nombre de crédits.
Un GPU allumé consomme 1 crédit par jour. De base, vous avez 8 crédits offerts par jour (14 après un premier achat.)
En créant votre compte, vous avez 180 crédits, qui ne descendront donc pas tant que vous n'avez pas plus de 8 GPU en marche. Et ça reste gratuit tant que vous ne les avez pas épuisés 😉

![Tarifs](/IMG/mmpos-prix.png)

## A quoi ça ressemble ?

![Dashboard](/IMG/mmpos-dashboard.png)

![Rigs](/IMG/mmpos-rigs.png)

![Rigs](/IMG/mmpos-rigs02.png)

Le principe est le même que Hiveos. Les principales différences :

Les flight sheets sont appelées miner profiles

![Profils](/IMG/mmpos-profiles01.png)

![Profils](/IMG/mmpos-profiles02_1.png)

![Profils](/IMG/mmpos-profiles02_2.png)
 
La liste des pools se crée manuellement. Quand vous créez une pool, elle contient :
- Le coin miné
- L'adresse et le port de la pool
- L'adresse de votre wallet

![Pools](/IMG/mmpos-pools.png)
  
- L'overclocking est plus complet (Core clock, core offset, mem clock, mem offset)
- une flight sheet = un mineur, en gros on peut appliquer plusieurs flight sheets à son rig (une nvidia + une AMD + une CPU par exemple)
- Pour les bidouilleurs, les flight sheets sont plus complètes. On peut y modifier la commande d'exécution du mineur, et choisir une autre commande à exécuter au démarrage de la FS (overclocking, mise à jour, lancement d'un node... )

## Comment l'installer :

Ca s'installe comme hiveos

- Télécharger l'IMG : https://download.mmpos.eu/images/mmp-latest.img.xz
- La flasher (avec Balena Etcher par exemple) sur le disque dur, SSD ou clé USB qui sera sur votre rig et booter en étant connecté au réseau. L'IP locale du rig va apparaître à l'écran du rig.
- Sur un PC connecté au même réseau local que votre rig, créez votre compte sur https://app.mmpos.eu et connectez-vous.
- Allez dans Rigs pour en ajouter un nouveau, entrez l'IP qui s'affiche sur votre rig et il se liera à votre compte 😉

Et voilà, plus qu'à enregistrer vos wallets et créer vos flight sheets ! (Appelées mining profiles)

## Mot de passe du rig par défaut :
user : miner
mdp : mmpOS

# Envie de le tester ? :)

Mon referral code mmpOS : 9PT-FXW5-H50
