# Qubic (CPU GPU) sous mmpOS :

## 1- Créer le wallet/access token

Dans mmpOS, créer wallet Qubic et y entrer votre **access token complet.**

## - RACCOURCI : Importer une feuille de route prête à l'emploi

Il existe des fichiers .json pour importer directement votre FS Qubic.
(à importer à la page "miner profiles")

Dispo ici :

- Discord mmpOS : https://discord.gg/EWghRBSe
- fichiers json de profils Qubic CPU et GPU : https://discord.com/channels/335932437941059593/810505148618506291/1218654078381461644 

Pour créer le profil manuellement :

## 2- Créer la pool

Note : pool qubic.li. Mais on peut sûrement paramétrer la pool communautaire aussi 😉

- Name : qubic.li
- Coin : Qubic
- Wallet : **access token**
- Hostname : mine.qubic.li
- Port : 443
- Username : %wallet_address%.%rig_name%%miner_id%

## 3- Créer les miner profiles

### Pour CPU :

**Basic :**
- Name of profile : Qubic-CPU
- Coin : Qubic
- Platform : Linux / mmpOS
- Miner : qubic-cpu
- Miner version : Latest (changer si besoin)
- Pool : qubic.li (celle crée précédemment)

**Advanced :**
- Restrict workers : vide
- Api port : 333 (par défaut)
- Initiate command prior to miner launch : commande pour huge pages si besoin !
- Arguments : `--server %pool_server% --accesstoken %wallet_address% --cpu-threads 12 --rigid %rig_name%%miner_id%-CPU --no-avx512`
(changer le nombre de threads selon vos besoins)

### Pour GPU :

**Basic :**
- Name of profile : Qubic-GPU
- Coin : Qubic
- Platform : Linux / mmpOS
- Miner : qubic-gpu
- Miner version : Latest (changer si besoin)
- Pool : qubic.li

**Advanced :**
- Restrict workers : vide
- Api port : 333 (par défaut)
- Initiate command prior to miner launch : vide
- Arguments : `--server %pool_server% --accesstoken %wallet_address% --rigid %rig_name%%miner_id%-GPU`

## Autres mineurs custom (rqiner, apoolminer...)
Dispo ici : https://github.com/ddobreff/mmp-profiles/releases/
Importez directement le fichier .json voulu comme miner profile.

#Ce tuto vous a donné envie de tester mmpOS ? :)
Mon referral code mmpOS : 9PT-FXW5-H50
