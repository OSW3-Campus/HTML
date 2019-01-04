# Les liens

## Pratique

<!-- tabs:start -->

###### ** Instruction **

Créer une série de fichiers et les lier entre eux selon le schéma suivant :

![Le concept HyperText](../../_images/hypertext.jpg)

- Le document **A** est lié aux documents **B**, **E** et **D**
- Le document **B** est lié au document **C**
- Le document **C** est lié au document **F**
- Le document **D** n'à pas de liaison vers d'autres documents
- Le document **E** est lié au document **D**
- Le document **F** est lié aux documents **F** et **C**

```
/tp/A.html
/tp/B.html
/tp/C.html
/tp/D.html
/tp/E.html
/tp/F.html
```

###### ** Corrigé **

#### A.html

```html
<h1>Je suis le fichier A</h1>
<a href="B.html">Voir le fichier B</a>
<a href="E.html">Voir le fichier E</a>
<a href="D.html">Voir le fichier D</a>
```

#### B.html

```html
<h1>Je suis le fichier B</h1>
<a href="C.html">Voir le fichier C</a>
```

#### C.html

```html
<h1>Je suis le fichier C</h1>
<a href="F.html">Voir le fichier F</a>
```

#### D.html

```html
<h1>Je suis le fichier D</h1>
Je n'ai pas de lien
```

#### E.html

```html
<h1>Je suis le fichier E</h1>
<a href="D.html">Voir le fichier D</a>
```

#### F.html

```html
<h1>Je suis le fichier F</h1>
<a href="F.html">Voir le fichier F</a>
<a href="C.html">Voir le fichier C</a>
```

<!-- tabs:end -->