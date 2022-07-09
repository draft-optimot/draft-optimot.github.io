---
weight: 2
bookCollapseSection: true
title: "Fragrances d'Optimot"
---

# Fragrances d'Optimot et fonctionnement des drivers

## Pourquoi Optimot est différent sur Mac, Linux et Windows ?

Chaque système d'exploitation a sa manière de gérer les drivers de claviers et vient avec son lot d'opportunités et de contraintes, ce qui laisse deux possibilités :

1. Harmoniser tous les drivers en s'arrêtant aux limitations les plus fortes (celles de Windows),
2. Développer trois drivers fondés sur la même base mais qui exploitent chacun au maximum les possibilités que lui donne l'OS pour lequel il est développé.

Dans le cas d'Optimot, le choix a été fait de **tirer le maximum de chaque OS (Mac, Linux, Windows)** et de produire trois drivers — trois fragrances d'Optimot — en commençant par le maximum puis en élagant les fonctionnalités non-compatibles lors du portage vers les autres OS.

{{<button relref="/optimot_macos">}}Voir les particularités macOS{{</button>}}

{{<button relref="/optimot_linux">}}Voir les particularités Linux{{</button>}}

{{<button relref="/optimot_windows">}}Voir les particularités Windows{{</button>}}

## Chaînage Mac — Linux — Windows

Pour faire simple :

1. Optimot est développé sur Mac, via Karabiner,
2. Le fichier de description Mac est passé à travers un script afin de produire les fichiers de description des drivers Linux et Windows,
3. Le driver Linux reprend toutes les fonctionnalités originales,
4. Le driver Windows en perd un certain nombre.

Quand on parle de fonctionalités, on parle ici :

- De certains caractères que Windows ne permet pas d'intégrer dans un driver de clavier,
- De certaines combinaisons de touches que Windows interdit.

La description de ces alternatives est donnée dans les pages dédiées : [Mac](optimot_mac.md), [Linux](optimot_linux.md) et [Windows](optimot_windows.md).

{{<hint info>}}
✅ L'index des caractères pris en charge par Optimot est sur [Bépoète.fr/optimot](https://www.xn--bpote-6rae.fr/optimot)

 ⇒ 🔎 Avec une fonciton recherche !!

 ⇒ Les caractères disponibles uniquement sur Mac et Linux sont affichés *sur un fond jaune*.
{{</hint>}}