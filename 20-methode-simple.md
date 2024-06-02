---
layout: page
title: Méthode simple
permalink: methode-simple.html
---

Une méthode simple, qui permet d'aligner des éléments horizontalement en leur donnant **une largeur égale**:

```css
.row { display: flex; }
.row > * { flex: 1; }
```

Il est inutile de préciser la propriété `flex-direction`, car `flex-direction: row` est la valeur par défaut de flexbox.

Le réglage `flex:1` permet de donner une largeur égale à tous les éléments, et d'assurer qu'ils remplissent l'espace disponible.

C'est une écriture courte, qui correspond aux trois propriétés suivantes: 

```css
.item {
  flex-grow: 1;   /* au lieu de la valeur par défaut, qui est de 0 */
  flex-shrink: 1; /* correspond à la valeur par défaut */
  flex-basis: 0;  /* au lieu de la valeur par défaut, qui est "auto" */
}
```

## Un exemple

<p class="codepen" data-height="300" data-default-tab="html,result" data-slug-hash="oNRZJbX" data-editable="true" data-user="eracom" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/eracom/pen/oNRZJbX">
  flexbox defaults</a> 
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
