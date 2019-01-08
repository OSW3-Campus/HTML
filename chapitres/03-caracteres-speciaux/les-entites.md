# Les entités HTML

## Qu'est ce que c'est ?

Les entités de caractères HTML permettent de remplacer l'écriture de certains caractères réservés à l'écriture du format HTML.  
Les entités de caractères HTML permettent également l'écriture de caractères qui ne sont pas présent sur le clavier.


## Comment écrire une entité HTML ?

Une entité HTML peux s'écrire avec son **nom d'entité** 

```html
&nom;
```

ou son **numéro d'entité**

```html
&#numero;
```

Pour afficher un signe inférieur (&lt;) il faut écrire: `&lt;` ou `&#60;`

> **Avantage d'utiliser un nom d'entité**: Un nom d'entité est facile à retenir. 

!> **Inconvénient d'utiliser un nom d'entité**: Certains navigateurs ne supportent pas tous les noms d'entités.

> **Remarque** Les noms d'entités sont sensible à la casse.


## Les entités non-sécable

Deux mots séparés par une entité non-sécable colleront ensemble, c'est à dire qu'aucun saut de ligne ne s'appliquera entre ces deux mots. Ceci est pratique si la rupture des mots perturbe la lecture.

### L'espace non-sécable

L'espace non-sécable ajoute un espace entre deux mots.

```html
&nbsp;
```

> Si vous écrivez 10 espaces dans votre texte, le navigateur en supprimera 9 d'entre eux. 
Pour ajouter des espaces réels à votre texte, vous pouvez utiliser l'espace non-sécable.

Exemples :
- §&nbsp;dix
- 10&nbsp;kmh
- 22&nbsp;heures

### Le trait d'union non-sécable 

Le trait d'union non-sécable ajoute un trait d'union entre deux mots.

```html
&#8209;
```


## Quelques entités HTML utiles

| Result | Description | Entity Name | Entity Number |
|:-------|:------------|:------------|:--------------|
| &nbsp; |non-breaking space | &amp;nbsp; | &amp;#160; |
| &lt; | less than | &amp;lt; | &amp;#60; |
| &gt; | greater than | &amp;gt; | &amp;#62; |
| &amp; | ampersand | &amp;amp; | &amp;#38; |
| &quot; | double quotation mark | &amp;quot; | &amp;#34; |
| &apos; | single quotation mark (apostrophe) | &amp;apos; | &amp;#39; |
| &cent; | cent | &amp;cent; | &amp;#162; |
| &pound; | pound | &amp;pound; | &amp;#163; |
| &yen; | yen | &amp;yen; | &amp;#165; |
| &euro; | euro | &amp;euro; | &amp;#8364; |
| &copy; | copyright | &amp;copy; | &amp;#169; |
| &reg; | registered trademark | &amp;reg; | &amp;#174; |


## Les entités diacritiques

Les signes diacritiques sont des « **glyphes** » utilisés en combinaison avec des caractères alphanumériques pour produire des caractères qui ne sont pas présents dans le jeu de caractères (encodage) utilisé dans la page.

| Marque | Caractère | Constructeur | Resultat |
|:-------|:----------|:-------------|:---------|
|  ̀ | a | a&amp;#768; | a&#768; |
|  ́ | a | a&amp;#769; | a&#769; |
|  ̂ | a | a&amp;#770; | a&#770; |
|  ̃ | a | a&amp;#771; | a&#771; |
|  ̀ | O | O&amp;#768; | O&#768; |
|  ́ | O | O&amp;#769; | O&#769; |
|  ̂ | O | O&amp;#770; | O&#770; |
|  ̃ | O | O&amp;#771; | O&#771; |