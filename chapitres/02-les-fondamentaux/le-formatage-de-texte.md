# Le formatage de texte

## Texte en gras

La balise `<b>` définit du texte en gras.  
La balise `<strong>` définit du texte en important affiché en gras.

<!-- tabs:start -->

###### ** Code HTML **

```html
<b>This text is bold</b>
<strong>This text is strong</strong>
```

##### ** Rendu **

<b>This text is bold</b>
<strong>This text is strong</strong>

<!-- tabs:end -->

!> **Remarque**: Les navigateurs affichent `<strong>` et `<b>` de la même façon, cependant, il y a une différence dans le sens de ces balises: 
- `<strong>` signifie que le texte est **important**
- `<b>` définit le texte en gras


## Texte en italique

La balise `<i>` définit du texte en italique.  
La balise `<em>` définit du texte en important affiché en italique.

<!-- tabs:start -->

###### ** Code HTML **

```html
<i>This text is italic</i>
<em>This text is emphasized</em>
```

##### ** Rendu **

<i>This text is italic</i>
<em>This text is emphasized</em>

<!-- tabs:end -->

> **Remarque**: Les navigateurs affichent `<em>` et `<i>` de la même façon, cependant, il y a une différence dans le sens de ces balises: 
- `<em>` signifie que le texte est **important**
- `<i>` définit le texte en italic

## Texte plus petit

La balise `<small>` définit du texte plus petit.

<!-- tabs:start -->

###### ** Code HTML **

```html
<h2>HTML <small>Small</small> Formatting</h2>
```

##### ** Rendu **

<h2>HTML <small>Small</small> Formatting</h2>

<!-- tabs:end -->

## Texte surligné

La balise `<mark>` définit du texte en surbrillance.

<!-- tabs:start -->

###### ** Code HTML **

```html
<h2>HTML <mark>Marked</mark> Formatting</h2>
```

##### ** Rendu **

<h2>HTML <mark>Marked</mark> Formatting</h2>

<!-- tabs:end -->

## Texte supprimé

La balise `<del>` définit du texte supprimé.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>My favorite color is <del>blue</del> red.</p>
```

##### ** Rendu **

<p>My favorite color is <del>blue</del> red.</p>

<!-- tabs:end -->

## Texte ajouté

La balise `<ins>` définit du texte ajouté.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>My favorite <ins>color</ins> is red.</p>
```

##### ** Rendu **

<p>My favorite <ins>color</ins> is red.</p>

<!-- tabs:end -->

## Texte indicé

La balise `<sub>` définit du texte en indice.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>This is <sub>subscripted</sub> text.</p>
```

##### ** Rendu **

<p>This is <sub>subscripted</sub> text.</p>

<!-- tabs:end -->

## Texte exposant

La balise `<sup>` définit du texte en exposant.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>This is <sup>superscripted</sup> text.</p>
```

##### ** Rendu **

<p>This is <sup>superscripted</sup> text.</p>

<!-- tabs:end -->


## Pratique

### TP #1

<!-- tabs:start -->

###### ** Instruction **

Surligner les mots "Tokyo", "région métropolitaine", "la plus peuplée du monde"

```html
<p>Tokyo est la capitale du Japon, le centre de la région métropolitaine est la zone la plus peuplée du monde.</p>
```

###### ** Rendu **

<p><mark>Tokyo</mark> est la capitale du Japon, le centre de la <mark>région métropolitaine</mark> est la zone <mark>la plus peuplée du monde</mark>.</p>

###### ** Corrigé **

```html
<p><mark>Tokyo</mark> est la capitale du Japon, le centre de la <mark>région métropolitaine</mark> est la zone <mark>la plus peuplée du monde</mark>.</p>
```

<!-- tabs:end -->

### TP #2

<!-- tabs:start -->

###### ** Instruction **

Mettre le chiffre "2" en indice.

```html
<p>H2O is the scientific term for water.</p>
```

###### ** Rendu **

<p>H<sub>2</sub>O is the scientific term for water.</p>

###### ** Corrigé **

```html
<p>H<sub>2</sub>O is the scientific term for water.</p>
```

<!-- tabs:end -->

### TP #3

<!-- tabs:start -->

###### ** Instruction **

Barré le mot "blue" et indiqué que le mot "red" à été ajouté.

```html
<p>My favorite color is blue red.</p>
```

###### ** Rendu **

<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

###### ** Corrigé **

```html
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
```

<!-- tabs:end -->