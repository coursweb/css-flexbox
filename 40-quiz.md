---
layout: page
title: Quiz
permalink: quiz.html
---

Questions d'auto-évaluation sur Flexbox.

**1. Comment initaliser Flexbox ?**

- [ ] display : flexbox
- [ ] display : flex
- [ ] flexbox : 1
- [ ] position : flex

<details>
  <summary>Voir la réponse</summary>
  <p><code>display : flex</code> permet d'initialiser Flexbox.</p>
</details>

---

**2. Cochez toutes les valeurs que "justify-content" peut prendre.**

- [ ] space-evenly
- [ ] space-inside
- [ ] space-between
- [ ] space-around

<details>
  <summary>Voir la réponse</summary>
  <p>Les trois valeurs d'espacement possibles sont:<br> 
  <code>space-between</code>, <code>space-around</code>, <code>space-evenly</code>. Voir <a href="proprietes.html">propriétés</a>.</p>
  <p>La valeur <code>space-inside</code> n'existe pas.</p>
</details>

---

**3. Que se passe-t-il si on applique "flex:1" sur les éléments enfants d’une Flexbox?**

- [ ] Ils sont de largeur égale.
- [ ] Leur taille devient minuscule.
- [ ] Ils occupent toute la largeur disponible.
- [ ] Ils recouvrent les autres éléments de la page.

<details>
  <summary>Voir la réponse</summary>
  <p>1 et 3 sont justes.</p>
  <p>Leur largeur sera égale, et remplira l'espace disponible. Voir <a href="methode-simple.html">méthode simple</a> / <a href=https://cours-web.ch/css/selectors.html">sélecteurs CSS</a>.</p>
</details>

---

**4. Comment appliquer flex:1 sur les enfants directs de .row ?**

- [ ] `.row { flex : 1 }`
- [ ] `.row * { flex : 1 }`
- [ ] `.row * > { flex : 1 }`
- [ ] `.row > * { flex : 1 }`

<details>
  <summary>Voir la réponse</summary>
  <p>La réponse 4 est juste. Voir <a href="methode-simple.html">méthode simple</a>.</p>
</details>

---

## Questions "vrai ou faux"

**La mise en page Flexbox s'applique sur les éléments enfants du conteneur.**

- [ ] Vrai.
- [ ] Faux.

<details>
  <summary>Voir la réponse</summary>
  <p>Vrai.</p>
</details>

---

**Il est déconseillé d'utiliser Flexbox plusieurs fois sur une même page web.**

- [ ] Vrai.
- [ ] Faux.

<details>
  <summary>Voir la réponse</summary>
  <p>Faux. Il n'y a aucun problème à l'utiliser plusieurs fois sur une page.</p>
</details>

---

**L'ordre d'affichage des éléments Flex peut être modifié en CSS avec `order`.**

- [ ] Vrai.
- [ ] Faux.

<details>
  <summary>Voir la réponse</summary>
  <p>Vrai.</p>
</details>