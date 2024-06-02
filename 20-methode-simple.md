---
layout: page
title: Méthode simple
permalink: methode-simple.html
---

Une méthode simple, qui permet d'aligner des éléments horizontalement en leur donnant une largeur égale:

```css
.row { display: flex; }
.row > * { flex: 1; }
```

Il est inutile de préciser la `flex-direction`, car `flex-direction: row` est la valeur par défaut de flexbox.

Le réglage `flex:1` est une écriture courte, qui correspond aux propriétés suivantes: 

```css
  flex-grow: 1; (au lieu de la valeur par défaut, qui est de 0)
  flex-shrink: 1; (correspond à la valeur par défaut)
  flex-basis: 0; (au lieu de la valeur par défaut qui est "auto")
```
