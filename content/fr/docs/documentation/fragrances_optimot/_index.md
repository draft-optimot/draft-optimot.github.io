---
weight: 2
bookCollapseSection: true
title: "Fragrances d'Optimot"
---

# Fragrances d'Optimot et fonctionnement des drivers

## Pourquoi Optimot est différent sur Mac, Linux et Windows ?

Chaque système d'exploitation a sa manière de gérer les drivers de claviers et vient avec son lot d'opportunités et de contraintes, ce qui laisse deux possibilités :

1. **Harmoniser tous les drivers** en s'arrêtant aux limitations les plus fortes (celles de Windows),
2. **Développer trois drivers** fondés sur la même base mais qui exploitent chacun **au maximum les possibilités que lui donne l'OS** pour lequel il est développé.

Dans le cas d'Optimot, le choix a été fait de **tirer le maximum de chaque OS (Mac, Linux, Windows)** et de produire trois drivers — trois fragrances d'Optimot — en commençant par le maximum puis en élaguant les fonctionnalités non-compatibles lors du portage vers les autres OS.


## Qu'est-ce qui change ?

{{<hint danger>}}
TODO ⇒ compléter les onglets
{{</hint>}}

{{<tabs "uniqueid">}}

{{<tab "MacOS">}}
#### Optimot pour MacOS

C'est la version la plus complète et qui met à disposition de l'utilisateur les fonctionnalités les plus avancées :

🔒 **Verrouillage + mode avancé de certaines couches :**

  - Évite de devoir réactiver la couche à chaque caractère →  plus de fluidité,
  - Fonctionnalités pratiques pour certains cas d'usage,
  - Disponible pour les modes **exposant** et **indice** ainsi que la couche **Grec**.

🎓 **Lettres mathématiques**


🔍 [En savoir plus…](optimot_macos)

{{</tab>}}

{{<tab "Linux">}}
#### Optimot pour Linux

C'est une version quasi-complète par rapport à celle de MacOS : seuls certains comportements avancés demandent encore un peu de travail d'ingénierie ou subissent une contrainte technique.

Dans l'ensemble, on est plus qu'à mi-chemin entre Windows et MacOs.

🔍 [En savoir plus…](optimot_linux)

{{</tab>}}

{{<tab "Windows">}}
#### Optimot pour Windows

C'est la version la moins featurée du fait des limitations du système d'exploitation — la façon dont Windows gère les drivers de claviers crée un certain nombre d'incompatibilités qui nécessitent un élagage dans les caractères / enchaînements de touches.

Pour autant, elle préserve tous les atouts de base de la disposition : ergonomie et mise à disposition d'une importante variété de caractères.

🔍 [En savoir plus…](optimot_windows)

{{</tab>}}

{{</tabs>}}


{{<hint info>}}
✅ L'index des caractères pris en charge par Optimot est sur [Bépoète.fr/optimot](https://www.xn--bpote-6rae.fr/optimot)

 ⇒ 🔎 Avec une fonction recherche !!

 ⇒ Les caractères disponibles uniquement sur Mac et Linux sont affichés *sur un fond jaune*.
{{</hint>}}