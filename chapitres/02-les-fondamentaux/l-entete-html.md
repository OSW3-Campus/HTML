# L'entête HTML

## Qu'est ce que c'est ?

L'entête HTML est un conteneur pour des métadonnées.

Les métadonnées HTML sont des information qui décrivent le comportement du document HTML et ne sont pas affichées. Elles définissent généralement le titre du document, le jeu de caractères, les styles et les scripts.

La balise d'entête `<head>` est placée entre la balise `<html>` et la balise `<body>`.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Document title</title>
    </head>
    <body>
    </body>
</html>
```


## Les éléments de l'entête HTML

| Balise | Description |
|:-|:-|
| [&lt;head&gt;][ltheadgt] | Defines information about the document |
| [&lt;title&gt;][lttitlegt] | Defines the title of a document |
| [&lt;base&gt;][ltbasegt] | Defines a default address or a default target for all links on a page |
| [&lt;link&gt;][ltlinkgt] | Defines the relationship between a document and an external resource |
| [&lt;meta&gt;][ltmetagt] | Defines metadata about an HTML document |
| [&lt;script&gt;][ltscriptgt] | Defines a client-side script |
| [&lt;style&gt;][ltstylegt] | Defines style information for a document |

[ltheadgt]: memo/les-balises?id=ltheadgt
[lttitlegt]: memo/les-balises?id=lttitlegt
[ltbasegt]: memo/les-balises?id=ltbasegt
[ltlinkgt]: memo/les-balises?id=ltlinkgt
[ltmetagt]: memo/les-balises?id=ltmetagt
[ltscriptgt]: memo/les-balises?id=ltscriptgt
[ltstylegt]: memo/les-balises?id=ltstylegt


## Pratique

<!-- tabs:start -->

###### ** Instruction **

Ajouter le titre du document, une description, une feuille de style et un fichier de script

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <button>Dire bonjour !</button>
    </body>
</html>
```

###### ** Rendu **



###### ** Corrigé **

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Hello World</title>
        <base href="assets/" target="_blank">
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <button>Dire bonjour !</button>
    </body>
</html>
```

<!-- tabs:end -->