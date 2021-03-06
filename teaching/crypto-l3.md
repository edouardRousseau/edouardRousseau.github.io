---
title: Cryptographie
layout: default
permalink: /teaching/crypto-l3/
visible: false
---

J'ai donné des Travaux Dirigés (TD) de cryptographie à l'université de Versailles en licence 3
d'informatique en 2017-2018 puis 2018-2019 et 2019-2020. Le cours était assuré soit par [Christina Boura](http://christina-boura.info/en), soit par [Léo Perrin](https://who.paris.inria.fr/Leo.Perrin/). Les feuilles d'exercices sont sur cette page. Si vous avez une question, vous pouvez me contacter par
[e-mail](mailto:{{site.email}}).

1. [Chiffrements historiques](td1.pdf)
2. [ENIGMA et chiffrement à flot](td2.pdf)
3. [One-Time-Pad et LFSR](td3.pdf)
4. [Chiffrement par bloc et schémas de Feistel](td4.pdf)
5. [DES et modes opératoires](td5.pdf)
6. [Arithmétique modulaire](td6.pdf)
7. [RSA](td7.pdf)
8. [Tests de primalité et cryptographie à clé publique](td8.pdf)
9. [Protocole Diffie-Hellman](td9.pdf)
10. [Chiffrement Elgamal](td10.pdf)
11. [Signatures numériques](td11.pdf)
12. [OpenSSL](TD12.zip)

# Une conjecture issue du TD sur les LFSR

Un étudiant a formulé la conjecture suivante

**Conjecture**

*Un LFSR ayant des coefficents de rétroaction tous nuls sauf les deux premiers
est de période maximale.*

et m'a demandé si ce résultat était vrai. En effet, on rencontre des LFSR de
longueur 3 et 4 dans le TD qui possèdent ces propriétés. Comme j'avais assez peu
confiance en ce résultat j'ai utilisé [Sage](http://www.sagemath.org/) pour
enquêter. Il s'avère que c'est faux dès la longueur 5. Je n'ai pas eu à coder
grand chose car il y avait déjà une fonction pour générer des LFSR dans Sage.
