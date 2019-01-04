# Les titres

## Les balises

Les titres sont définis avec les balises `<h1>` à `<h6>`.

La balise `<h1>` définis le titre la plus forte importance, alors que la balise `<h6>` définis un titre avec la plus faible importance.

<!-- tabs:start -->

###### ** Code HTML **

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
##### ** Rendu **

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

> **Remarque**: Les navigateurs ajoutent automatiquement une marge avant et après un titre.

<!-- tabs:end -->


## Le rôle des balises de titre

Les moteurs de recherche utilisent les balises de titre pour indexer la structure et le contenu des pages Web.

Les titres `<h1>` doivent être utilisés pour les titres principaux, suivi par les titres `<h2>` moins important, puis `<h3>` et ainsi de suite...

> **Remarque**: Utilisez des titres HTML pour les titres de rubriques seulement. Ne pas utiliser des titres pour rendre le texte gras.


## Modifier le style

Chaque titre HTML possède une taille par défaut. Cependant, vous pouvez spécifier la taille pour toute position avec l'attribut `style`, en utilisant la propriété CSS `font-size`


## La balise de régle horizontal

La balise `<hr>` définit une rupture thématique dans une page HTML, et est le plus souvent affiché avec une ligne horizontale.


<!-- tabs:start -->

###### ** Code HTML **

```html
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```
##### ** Rendu **

<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

<!-- tabs:end -->


## Pratique

<!-- tabs:start -->

###### ** Instruction **

Hiérarchisé les éléments suivant garce aux balises de titre

```
Stagiaire
Actionnaires
Manager / Chefs d'equipe
P.D.G.
Salarié
Directeur
```

###### ** Rendu **

<h1>Actionnaires</h1>
<h2>P.D.G.</h2>
<h3>Directeur</h3>
<h4>Manager / Chefs d'equipe</h4>
<h5>Salarié</h5>
<h6>Stagiaire</h6>


###### ** Corrigé **

```html
<h1>Actionnaires</h1>
<h2>P.D.G.</h2>
<h3>Directeur</h3>
<h4>Manager / Chefs d'equipe</h4>
<h5>Salarié</h5>
<h6>Stagiaire</h6>
```

<!-- tabs:end -->