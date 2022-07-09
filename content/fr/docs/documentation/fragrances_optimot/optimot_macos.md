---
weight: 1
title: "Optimot pour Mac"
---

# Optimot pour Mac

{{<hint danger>}}
TODO ⇒ compléter
{{</hint>}}

C'est la version la plus complète, qui exploite toutes les possibilités laissées par Karabiner dans la conception des interactions de l'interface clavier.
Le [changelog](../../../change_log.md) contient les détails exhaustifs des incrémentations de ces fonctionnalités au fil des versions du projet.
Ci-dessous, vous trouverez toutes les fonctionnalités propres à l'environnement Mac.

## Mode exposant avancé

{{<hint info>}}
Pour entrer en mode exposant, taper `altgr-e` ou `^` puis un chiffre.
{{</hint>}}

### Verrouillage du mode exposant après le premier chiffre

- `^ 1 2 3 4` ⇒ **¹²³⁴**
- `espace` et `backspace` désactivent le verrouillage
- `Ç` permet de basculer entre le mode indice et exposant
- `$` permet de basculer entre le mode indice et exposant en plaçant d'abord une barre de fraction :
  - `/` en passant d'exposant à indice
  - `\` en passant d'indice à exposant
- `@` émet **⁄₂₀**
- `#` émet **⁄₁₂**
- **⁻⁺⁼⁽⁾** sont en `altgr` directement après ^, et en `shift` et `alt` en mode exposant.
- **₋₊₌₍₎** sont en `shift-altgr` directement après ^, et en `shift` et `alt` en mode exposant.

### Exemples

**Écrire une fraction :**

- `^ 1 2 3 $ 9 7` ⇒ **¹²³⁄₉₇**
- `^ Ç 3 $ 5` ⇒ **₃\⁵**
- `^ 1 6 @` ⇒ **¹⁶⁄₂₀**
- `^ 7 #` ⇒ **⁷⁄₁₂**

**Écrire pour les mathématiques :**

- `shift‑2 altgr‑e n shift-+ 1` ⇒ 2ⁿ⁺¹