# FCSC 2021 The Offenders

Notre équipe de Threat Intel est tombé sur ce binaire lors d’un RétroHunt VirusTotal à la recherche des termes FCSC. 
Ils y ont jeté un œil et ont compris que le binaire s’attend à être exécuté par Windows Defender. Un rapide 
reverse-à-coup-de-notepad nous a permis de trouver un endroit commençant par INPUTINPUT..., qui semble être le moyen 
de donner un argument au programme (en le patchant).


Fichier :
- [the_offenders.exe](the_offenders.exe)



Auteur : commial

Origine : [The Offenders](https://hackropole.fr/fr/challenges/reverse/fcsc2021-reverse-the-offenders/)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2021-reverse-the-offenders.git

> cd fcsc2021-reverse-the-offenders


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/reverse/fcsc2021-reverse-the-offenders/