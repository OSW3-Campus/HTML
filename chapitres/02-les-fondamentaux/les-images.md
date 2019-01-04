# Les images


## Pratique

### TP #1 : Insérer des images

<!-- tabs:start -->

###### ** Instruction **

Intégrer les images du répertoire `animaux` dans le fichier `index.html`.  
Ne pas oublier les éléments SEO et d'optimisation de l'accessibilité.

Mettre le fichier `index.html` et le répertoire `animaux` sur le même niveau.

```
/tp/index.html
/tp/animaux/
```

<a href="_ressources/les-images/animaux.zip" download>Télécharger la source</a>

###### ** Rendu **

<h1>Les animaux de la terre</h1>
<img src="../../_ressources/les-images/animaux/terre/lion.jpg" alt="Image représentant un lion." title="Photo d'un lion.">
<img src="../../_ressources/les-images/animaux/terre/elephants.jpg" alt="Image représentant des éléphants." title="Photo d'éléphants.">

<h1>Les animaux de la mer</h1>
<img src="../../_ressources/les-images/animaux/eau/baleines.jpeg" alt="Image représentant des baleines." title="Photo de baleines.">
<img src="../../_ressources/les-images/animaux/eau/orque.jpg" alt="Image représentant un orque." title="Photo d'un orque.">

<h1>Les animaux des airs</h1>
<img src="../../_ressources/les-images/animaux/air/aigle.jpg" alt="Image représentant un aigle." title="Photo d'un aigle.">
<img src="../../_ressources/les-images/animaux/air/chouette.png" alt="Image représentant une chouette." title="Photo d'une chouette.">



###### ** Corrigé **

```html
<h1>Les animaux de la terre</h1>
<img src="animaux/terre/lion.jpg" alt="Image représentant un lion." title="Photo d'un lion.">
<img src="animaux/terre/elephants.jpg" alt="Image représentant des éléphants." title="Photo d'éléphants.">

<h1>Les animaux de la mer</h1>
<img src="animaux/eau/baleines.jpeg" alt="Image représentant des baleines." title="Photo de baleines.">
<img src="animaux/eau/orque.jpg" alt="Image représentant un orque." title="Photo d'un orque.">

<h1>Les animaux des airs</h1>
<img src="animaux/air/aigle.jpg" alt="Image représentant un aigle." title="Photo d'un aigle.">
<img src="animaux/air/chouette.png" alt="Image représentant une chouette." title="Photo d'une chouette.">
```

<!-- tabs:end -->



### TP #2 : Ajouter des liens sur des images


<!-- tabs:start -->

###### ** Instructions **

Reprendre le TP#1 et rendre les images cliquables. Chaque image doit ouvrir la page wikipédia de l'animal qu'elle représente.

- Lion : https://fr.wikipedia.org/wiki/Lion
- Eléphants : https://fr.wikipedia.org/wiki/%C3%89l%C3%A9phant
- Baleine : https://fr.wikipedia.org/wiki/Baleine
- Orque : https://fr.wikipedia.org/wiki/Orque
- Aigle : https://fr.wikipedia.org/wiki/Aigle
- Chouette : https://fr.wikipedia.org/wiki/Chouette

###### ** Rendu **

<h1>Les animaux de la terre</h1>
<a href="https://fr.wikipedia.org/wiki/Lion"><img src="../../_ressources/les-images/animaux/terre/lion.jpg" alt="Image représentant un lion." title="Photo d'un lion."></a>
<a href="https://fr.wikipedia.org/wiki/%C3%89l%C3%A9phant"><img src="../../_ressources/les-images/animaux/terre/elephants.jpg" alt="Image représentant des éléphants." title="Photo d'éléphants."></a>

<h1>Les animaux de la mer</h1>
<a href="https://fr.wikipedia.org/wiki/Baleine"><img src="../../_ressources/les-images/animaux/eau/baleines.jpeg" alt="Image représentant des baleines." title="Photo de baleines."></a>
<a href="https://fr.wikipedia.org/wiki/Orque"><img src="../../_ressources/les-images/animaux/eau/orque.jpg" alt="Image représentant un orque." title="Photo d'un orque."></a>

<h1>Les animaux des airs</h1>
<a href="https://fr.wikipedia.org/wiki/Aigle"><img src="../../_ressources/les-images/animaux/air/aigle.jpg" alt="Image représentant un aigle." title="Photo d'un aigle."></a>
<a href="https://fr.wikipedia.org/wiki/Chouette"><img src="../../_ressources/les-images/animaux/air/chouette.png" alt="Image représentant une chouette." title="Photo d'une chouette."></a>



###### ** Corrigé **

```html
<h1>Les animaux de la terre</h1>
<a href="https://fr.wikipedia.org/wiki/Lion"><img src="animaux/terre/lion.jpg" alt="Image représentant un lion." title="Photo d'un lion."></a>
<a href="https://fr.wikipedia.org/wiki/%C3%89l%C3%A9phant"><img src="animaux/terre/elephants.jpg" alt="Image représentant des éléphants." title="Photo d'éléphants."></a>

<h1>Les animaux de la mer</h1>
<a href="https://fr.wikipedia.org/wiki/Baleine"><img src="animaux/eau/baleines.jpeg" alt="Image représentant des baleines." title="Photo de baleines."></a>
<a href="https://fr.wikipedia.org/wiki/Orque"><img src="animaux/eau/orque.jpg" alt="Image représentant un orque." title="Photo d'un orque."></a>

<h1>Les animaux des airs</h1>
<a href="https://fr.wikipedia.org/wiki/Aigle"><img src="animaux/air/aigle.jpg" alt="Image représentant un aigle." title="Photo d'un aigle."></a>
<a href="https://fr.wikipedia.org/wiki/Chouette"><img src="animaux/air/chouette.png" alt="Image représentant une chouette." title="Photo d'une chouette."></a>
```
<!-- tabs:end -->