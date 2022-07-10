---
title: "Couches de base"
weight: 1
---

# Couches de base (accès direct)

{{<figure width=600 src="/img/optimot_ISO_full.jpg" link="/img/optimot_ISO_full.jpg" alt="Map de la couche de base de la version ISO d'Optimot" caption="Couche de base d'Optimot (version ISO)">}}

## Quelques généralités

{{<expand "💡 Principe des quatre niveaux">}}

De base, tous les claviers ont la capacité de placer quatre caractères par touche grâce aux modificateurs `Shift` et `AltGr` ainsi qu'avec leur combinaison `AltGr-Shift`, ce qui produit le résultat suivant :

```
                            +-------+
       caractère en Shift → | A   Æ | ← caractère en AltGr-Shift
caractère en accès direct → | a   æ | ← caractère en AltGr
                            +-------+
```
En général, leur utilisation se cantonne aux touches supérieures (le *num-row*) et n'utilisent pas la possibilité `AltGr-Shift` → sur la touche `8` AZERTY, par exemple, on trouve `_ 8 \`.

✅ Pour plus de lisibilité, on nomme souvent la touche par son caractère capitalisé :

- touche `A` pour `a A æ Æ`,
- touche `1` pour `« 1 “ ¼`,
- touche `?` pour `' ? ¿ ♦`.

✅ Dans la même idée, l'appui de `Shift` et `AltGr` est toujours mentionné de façon explicite → si vous lisez dans ce site `^ 1`, il s'agit d'appuyer sur `^` puis sur la touche `1` du num-row (donc sans `Shift` qui permettrait effectivement de faire « 1 »)

{{</expand>}}

{{<expand "💡 Principe des touches mortes et des accents morts">}}
Les **touches mortes** sont des touches spéciales qui activent une autre couche.
Tant que la frappe suivante n'a pas été effectuée, rien ne sort à l'emplacement du curseur.

Elles servent généralement à préparer un **accent mort** (typiquement `^` ou `~`) pour le poser sur le caractère tapé ensuite.

🌟 Dans le cas d'Optimot, elles servent aussi à **activer des couches spécialisées** du clavier dans lesquelles est rangé un vaste ensemble de caractères qui intéresseront certains utilisateurs pour des [usages spécifiques](./../../cas_usage/dialogues_citations).

🍏 ⇒ **sur MacOS**, le curseur se met en surbrillance lorsqu'un accent mort a été activé.
{{</expand>}}

## Logique Optimot

### Sur l'agencement des caractères

Optimot a été conçu de façon à :

{{<expand "🙈 Faciliter la frappe à l'aveugle">}}

 Bien qu'on puisse l'utiliser en regardant le clavier, la disposition prend tout son sens dans l'exercice d'une frappe à l'aveugle (ou « frappe à 10 doigts »), à travers laquelle elle permet :

  1. De redresser le corps pour soulager le dos et la nuque,
  1. De donner répartir le travail sur les 10 doigts,
  1. De limiter les contorsions des poignets.

 ↪ 🔗 [Bépoète.fr](https://www.xn--bpote-6rae.fr/) pour vous entraîner à Optimot autant qu'à la frappe à l'aveugle.
{{</expand>}}

{{<expand "📈 Optimiser le placement des caractères…">}}
…en plaçant les caractères les plus fréquents (y compris la ponctuation) :
  - Sur la *home-row* (rangée du milieu où se trouvent les repères tactiles — touches `F` et `J` d'AZERTY),
  - Sur des doigts forts (pas le petit doigt),
  - À portée des doigts selon leur longueur et leur motricité.
{{</expand>}}

{{<expand "🤸‍♂️ Favoriser les roulements…">}}
…en juxtaposant les caractères fréquemment enchaînés

  - *Directs* (parfaitement juxtaposés) → `a i e` dans « haie » ( h *aie* ),
  - **Indirects** (nécessitent de sauter un doigt ou de changer de rangée) → `j o u` et `n t` dans « jouaient » ( **jou** *aie* **nt**).
{{</expand>}}

{{<expand "😏 Faciliter autant que possible l'usage de Shift et AltGr">}}
Exemples :

  - L'espace insécable fine `Shift-espace` s'enchaîne avec les ponctuations pertinentes situées aussi en `Shift`, permettant le maintient du modificateur :
    - `↓Shift↓ espace ,` → `␣;`
    - `↓Shift↓ espace '` → `␣?`
    - `↓Shift↓ espace ^` → `␣!`
    - etc…
  - L'espace insécable normale `AltGr-espace` s'enchaîne avec les ponctuations pertinentes situées aussi en `AltGr` :
    - `↓AltGr↓ B espace` → `—␣` pour éviter que le tiret cadratin — ne soit séparé du texte qui le suit,
    - `↓AltGr↓ espace , espace` → `␣–␣` pour éviter que les dates et le tiret demi-cadratin dans « 1450 – 1455 » ne soient séparés.
{{</expand>}}

{{<expand "⚖ Compromis dactylo / programmation">}}
#### Sur l'apostrophe

Après de nombreuses concertations, la touche `'` (apostrophe) a finalement reçu le caractère « apostrophe droite » (la même que celle produite par le `4` d'AZERTY) au lieu de `’` (« apostrophe typographique », qui présente la même courbure qu'une virgule) afin de faciliter son utilisation pour les développeurs.

Cette décision s'appuie sur le constat que la plupart des logiciels opèrent de toute façon une substitution automatique de `'` par `’` et que, dans l'usage actuel, `'` ne choque pas véritablement le lecteur moyen si jamais elle apparaît quelque-part au milieu d'un texte.

#### Sur les symboles de programmation

Les symboles les plus courants bénéficient de doublons afin de permettre de les atteindre de différentes manières :

- `_` (underscore) :
  - Se situe sur `^ espace` (roulement petit doigt – pouce),
  - Et sur `Shift-@` (dans la num-row),
  - Et est activé sur `@` lorsque l'utilisateur enclenche `CAPSLOCK` de façon à permettre un usage simplifié avec les chiffres.
- `|` (barre verticale) :
  - Se situe sur `AltGr-X`,
  - Et sur `^ Q` (roulement auriculaire – annulaire)
- `\` (backslash) :
  - Se situe sur `AltGr-7`,
  - Et sur `AltGr-KK`,
  - Et sur `^ R`.
- etc…

Pour vérifier l'accessibilité des symboles, vous référer à l'indexe des caractères sur [Bépoète.fr](https://www.xn--bpote-6rae.fr/optimot)

{{</expand>}}

### Sur l'organisation des couches
Les quatre couches de base s'organisent selon une certaine logique :

- Les ligatures du français sont sur leur lettre de base → æ sur `A`, œ sur `O`, … (ellipse) sur `.`,
- `{` `}`  sont aussi près que possible de `(` `)` ,
- `<` `>`  sur `AltGr` sont au même endroit que `⩽` `⩾`  sur `AltGr-Shift`,
- `«` `»` `"`  sur l'accès direct deviennent `“` `”` `„`  en `AltGr`,
- `⬅` `⬇` `⬆` `➡`  en `AltGr` reprennent la convention de l'éditeur vi, simplement décalé d'une touche,
- etc…

{{<expand "💡 Logique inter-couches">}}
#### Sur l'organisation des couches spécialisées par rapport à la couche de base

Lorsque c'est pertinent, les caractères présents dans les couches spécialisées peuvent s'appuyer sur les caractères de la couche de base :

- La [Couche Flèches](../couche_fleches) est organisée selon la logique de direction des flèches, mais on y trouve aussi :
  - `↪` et `↳` qui sont sur `(` et `[`
  - `↩` et `↵` qui sont sur `)` et `]`
- La [Couche Grec](../couche_grec) associe les lettres grecques avec leurs équivalents français lorsqu'elles en possèdent :
  - `ε` sur `E`,
  - `α` sur `A`,
  - `π` sur `P`…
- etc…
{{</expand>}}


## Liste des touches mortes et des accès aux couches spéciales

Signalées en vert sur la map (essentiellement en couche `AltGr`), les touches mortes reprennent autant que possible une signalétique cohérente avec la lettre sur laquelle elles reposent (simple moyen mnémotechnique) et sont aussi organisées selon la logique inter-couches.

Selon les cas, elles activent soit (🚀) une couche spéciale, soit (📝) un caractère combinant (accent mort) :

- 🚀 `^` porte la [couche Circonflexe](./../couche_circonflexe) qui permet un accès rapide à diverses fonctionnalités avancées (chiffres en exposant, )
- 🚀 `$` porte la [couche Monnaie](./../couche_monnaie) `¤` où on retrouve par exemple :
- 📝 `É` l'accent aigu mort simple (á, ú) et double (ő, ű) tandis que `È` porte l'accent grave mort simple (ò, ì) et double (ȍ, ȉ).
- `Q` par sa rotondité :
  - 📝 porte le `̊ ` « Rond en chef », utilisé notamment dans les langues scandinaves (Åå),
  - 🚀 permet d'entourer chiffres et lettres (❶②➂⓸ⓐⒷ).
- 📝 `I` porte le tréma `̈ ` qu'il porte plus fréquemment que le `u` en français :
  - `ï` → tréma suscrit en tapant `AltGr-I`,
  - `ṳ` → tréma souscrit en tapant `AltGr-II`,
- 🚀 `E` active :
  - Le mode exposant avec `AltGr-E` → 1ᵉʳ et 2ⁿᵈ
  - Le mode indice avec `AltGr-EE` → fₙ , f₀ , f₁ , f₂ , f₃
- 🚀 `∞` représente la [couche Science](./../couche_science), posée sur le `S`,
- 🚀 `𝐋` représente la [couche Latin](./../couche_latin), posée sur le `R` comme « *Romain* »,
- 📝 `N` porte le tilde `~`,
- 📝 `K` porte la barre oblique `⁄` utilisée notamment dans les langues scandinaves (Øøł),
- 📝 `Y` porte le point combinant `̇ ` :
  - `ȧ` → point suscrit en tapant `AltGr-Y`
  - `ạ` → point souscrit en tapant `AltGr-YY`
- 🚀 `µ` représente la [couche Grec](./../couche_grec), posée sur le `G`,
- 📝 `C` porte la cédille,
- 📝 `M` porte le macron `̄ `,
  - `ā` → suscrit en tapant `AltGr-M`
  - `̱a` → souscrit en tapant `AltGr-MM`
- 📝 `H` porte la brève `̆ `,
  - `ă` normale en tapant `AltGr-H`
  - `ȃ` inversés en tapant `AltGr-HH`
- 📝 `V` porte le caron `̌ `,
  - `š` → suscrit en tapant `AltGr-V`
  - `ṷ` → souscrit en tapant `AltGr-VV`

