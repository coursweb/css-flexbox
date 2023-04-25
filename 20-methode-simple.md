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

Il est inutile de préciser la flex-direction, car `flex-direction: row` est la valeur par défaut de flexbox.
