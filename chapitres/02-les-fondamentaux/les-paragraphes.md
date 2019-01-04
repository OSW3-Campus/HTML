# Les paragraphes


## Balise

La balise HTML `<p>` définit un paragraphe :

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
##### ** Rendu **

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

> **Remarque**: Les navigateurs ajoutent automatiquement une marge avant et après un titre.

<!-- tabs:end -->

> Ne pas oublier la balise de fin

La plupart des navigateurs affichent les paragraphe correctement même si vous oubliez la balise de fin, mais ils peuvent également produire des résultats ou des erreurs inattendues.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>This is a paragraph.
<p>This is another paragraph.
```

##### ** Rendu **

<p>This is a paragraph.
<p>This is another paragraph.

<!-- tabs:end -->


## Gestion de l'affichage

### Gestion des espaces

Les multiples espaces ne sont pas pris en compte par les navigateurs.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser 
ignores it.
</p>
```
##### ** Rendu **

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser 
ignores it.
</p>

<!-- tabs:end -->

### gestion des sauts de ligne

Les retours à la ligne ne sont pas pris en compte par les navigateurs.

<!-- tabs:start -->

###### ** Code HTML **

```html
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser 
ignores it.
</p>
```
##### ** Rendu **

<p>
This paragraph
contains a lot of lines
in the source code,
but the browser 
ignores it.
</p>

<!-- tabs:end -->

### Ajouter un saut de ligne

La balise `<br>` ajoute un saut de ligne sans redéclarer un noveau paragraphe.


<!-- tabs:start -->

###### ** Code HTML **

```html
<p>This is<br>a paragraph<br>with line breaks.</p>
```
##### ** Rendu **

<p>This is<br>a paragraph<br>with line breaks.</p>

<!-- tabs:end -->


## Pratique

<!-- tabs:start -->

###### ** Instruction **

Corriger l'affichage de ce poème

```html
<p>

   My Bonnie lies over the ocean.

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.

   Oh, bring back my Bonnie to me.

</p>
```

###### ** Rendu **

<p>My Bonnie lies over the ocean.</p>
<p>My Bonnie lies over the sea.</p>
<p>My Bonnie lies over the ocean.</p>
<p>Oh, bring back my Bonnie to me.</p>


###### ** Corrigé **

```html
<p>My Bonnie lies over the ocean.</p>
<p>My Bonnie lies over the sea.</p>
<p>My Bonnie lies over the ocean.</p>
<p>Oh, bring back my Bonnie to me.</p>
```

<!-- tabs:end -->