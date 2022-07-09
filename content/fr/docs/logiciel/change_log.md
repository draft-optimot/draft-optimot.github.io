---
title: "Change log"
weight: 1
---

# Historique des versions d'Optimot

{{<hint danger>}}
TODO ⇒ mise en page
{{</hint>}}

## Versions actuelles

| Option | Mac | Linux | Windows | Pour clavier |
|:---:|:---:|:---:|:---:|:---|
| Ergo | V1.4.4 | V1.3.1 | V1.3 | ⇐ Ergo / QWERTY |
| ISO  | V1.4.4 | V1.3.1 | V1.3 | ⇐ AZERTY |

___

## V1.4.4

### Nouveaux raccourcis clavier pour macOS 12.

Depuis macOS 12, Apple a changé le mode de fonctionnement des raccourcis clavier pour les dispositions autres que Azerty. Désormais ce sont les raccourcis clavier Qwerty qui sont attendus, même pour les dispositions déclarées comme françaises telles que Optimot.

Ces modifications impactent essentiellement les raccourcis avec la rangée supérieure. Par exemple, le Finder attend ⌘1, ⌘2, ⌘3… au lieu de ⌘&, ⌘é, ⌘"…

Si vous utilisez macOS 11 ou antérieur, vous devez installer le pilote Optimot version 1.4.3.

## V1.4.3

### Correction des raccourcis clavier.

## V1.4.2a

### ISO :

Ajout de ⌘+Z à la place du BackSpace. De toutes façons ce BackSpace ne marche pas avec ⌘ et Ctrl (il marche avec ⌥ en revanche). 

### ISO et Ergo :

* Suppression de `'`
* Décalage de `[`, `]`, `<`, `>` vers la gauche (en mirroir en Ergo)
* Ajout de `*` en `8`
* `*` sert pour la même série de fonctions dans Aperçu (et peut-être ailleurs).

## V1.4.2

### ❶ Refonte des raccourcis clavier.

Désormais seuls les raccourcis clavier Optimot sont fournis.

Ils ont été repensés pour être compatibles avec davantage d’applications en ce qui concerne la rangée supérieure.

Pour la partie principale avec les lettres, ils sont disposés de telle sorte que les raccourcis les plus utilisés sont accessibles aussi bien sur le côté gauche pour les droitiers, que sur le côté droit pour les gauchers (qui utilisent la souris de la main gauche).

Pour ce faire, X, C, V, et Q sont dupliqués du côté gauche sur des emplacements inutilisés, tandis que A et W sont dupliqués du côté droit. Du côté gauche, X, C, V se trouvent sur les mêmes touches qu’en Azerty, et Q sur la même touche qu’en Qwerty.

Consultez le dossier « Raccourcis clavier » pour en savoir plus.

Les versions Q et Qu sont présentes dans un unique paquet.

### ❷ Amélioration de la saisie des exposants, indices, et fractions

__*⇒ EXCLUSIVITÉ MAC-OS*__

- Après ^, les chiffres en exposants sont en accès direct, et les indices avec Shift.
  - Exemple : ^3 → ³
  - Exemple : ^‹Shift-3› → ₃

- Après le premier chiffre, la saisie est verrouillée en mode exposant ou indice.
  - Inutile de presser ^ avant chaque chiffre. On sort de ce mode avec Espace.
  - Exemple : ^4572  → ⁴⁵⁷²
- La touche Ç permet de passer d’exposant à indice et vice-versa.
- En $ se trouve une barre de fraction, et le mode passe d’exposant à indice et vice-versa.
  - Exemple : ^123$97  → ¹²³⁄₉₇ 
  - Exemple : ^‹Shift-3›$5  → ₃\⁵ 
- En @ se trouve  ⁄₂₀ et en #  ⁄₁₂
  - Exemple : ^16@ → ¹⁶⁄₂₀
  - Exemple : ^7# → ⁷⁄₁₂

- Autres changements sur la couche Circonflexe :
  - ⁻⁺⁼⁽⁾ sont en Alt directement après ^, et en Shift et Alt en mode exposant.
  - ₋₊₌₍₎ sont en Shift‑Alt directement après ^, et en Shift et Alt en mode indice.
  - L’accent grave nu → ^à
- Sur les couches Exposant et Indice, la saisie de "i" et "n" provoquent le verrouillage en mode exposant ou indice.
- Sur la couche Exposant, la saisie de "x", "y" et "z" provoquent le verrouillage en mode exposant.
- Après ^ç, les touches I, N, X, Y, Z affichent ces lettres en exposant.
  - Exemple : ‹Shift‑2›‹Alt‑e›n‹Shift‑+›1  → 2ⁿ⁺¹
  - Autre façon de faire : ‹Shift‑2›^çn‹Alt‑+›1  → 2ⁿ⁺¹
- "i" et "n" sont également disponibles une fois verrouillé en mode exposant et indice, mais pas directement après ^.
  - Exemple : ‹Shift‑2›^3i  → 2³ⁱ

### ❸ Refonte de la couche Grec + verrouillage en mode saisie en grec.

__*⇒ EXCLUSIVITÉ MAC-OS*__

La couche Grec a été optimisée pour la saisie de texte en grec, avec notamment toutes les voyelles à gauche et l’accent en accès direct.

★ Il est possible de rester verrouillé en mode de saisie du grec en faisant `2×Alt-g`.

Il faut utiliser une touche Entrée spécifique pour rester en grec.

La touche À quitte le mode Grec. La touche BackSpace aussi. 

### ❹ Déplacement des touches mortes Corne et Crochet en chef → Alt-ç

- § et ¶ → aux deux places libérées en Shift‑Alt.
- ❏ et ❖ → aux deux places libérées par § et ¶.
- Permutation Tiret demi-cadratin ↔ Apostrophe typographique

### ❺ Regroupement des touches mortes Barré et Rayé → Alt-k

- 1× Alt‑k = barré
- 2× Alt‑k = rayé 

### ❻ Ajout de 3 flèches :

- ➼ → Alt-st Alt-Espace
- ➜ → Alt-st Shift-Espace
- ↕ → Alt-st Alt-e

### ❼ Ajout du diacritique barré court (en plus du barré long) :

- Barre de fraction : Alt-k Espace (également en ^$)
- Barré court (pour les minuscules) : Alt-k Alt‑Espace
- Barré long (pour les majuscules) : Alt-k Shift‑Espace

### ❽ Changements mineurs sur la couche Latin.

- `ɪ` et `ʏ` passent en direct sur `i` et `y`.  ̽` `et `ʎ` passent en Shift.
- `ø` en Alt‑o.