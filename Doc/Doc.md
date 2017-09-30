# Documentation MarkDown
## Block Elements



### Paragraphes:

Une ou plusieurs lignes de textes séparées par un ou plusieurs retour à la ligne, ces lignes ou ensembles de lignes seront divisées avec "< br/>" ou avec des simples retour à la ligne.

### Titres:

Pour écrire des titres, nous insérerons notre titre entre le nombre de dièse requis. H1 # dièse # H6 ###### dièses #######
H1
H2
H3
H4
H5
H6

### Blockquotes (ou citations):

    Ma ligne commence avec un blockquote

    Celle-ci aussi

    C'est la syntaxe typique Mail
    Que Markdown a repris
    pour une lecture plus fluide.

        Un autre niveau de blockquote

    Retour au niveau initial

        Ils peuvent contenir d'autres éléments


### Listes:

Les listes se font à l'aide de (*,-,+), avant chaque élément de la liste vous mettez un de ces symboles ci pour créer la liste à puces non ordonnée.

    Markdown supporte les listes
    ordonnées et
    non ordonnées.
        Je fais une
        sous
        puce

Pour les listes ordonnées vous les faites précéder de numéros.

    Ici une
    Liste
    Ordonnée


Si vous devez écrire un texte et que vous devez y introduire un numéro. votre texte, vous devrez casser votre point comme ceci 1 \ . afin de ne pas créer de liste à puces par accidents.

Bloc de code:

Votre code sera encadré des balises < pre> < code> et refermé par ces mêmes balises < /pre> < /code>.

 Votre bloc de code

Ce qui rend la lecture plus aisée, on sait directement ce qu'il en est. Les chevrons < > dans votre code deviennent alors & lt; code & gt; (sans espace)

Vous pouvez insérer une ligne de code dans votre texte en l'insérant entre deux accents graves ` votre code et la suite de votre texte.

Les lignes horizontales :

Pour faire une < hr /> Vous pouvez insérez 3 (et plus) astérix ou tirets

***

* * * *

- - -

--------------

Tout simplement.

Emphase:

*J'écris en italique*

J'écris en italique

_Ici aussi_

Ici aussi

**J'écris en gras**

J'écris en gras

__Ici aussi__

Ici aussi

## Span Elements
### Les Liens

Comment créer des liens:

1. URL seul
  + input: https://github.com/jimmyGoossens/MKD-Project/edit/Valerian/Doc/README.md

  + Resultat: https://github.com/jimmyGoossens/MKD-Project/edit/Valerian/Doc/README.md

3. Titre URL

  + input:
  \[Google Home Page](https://www.google.com)

    sans espace entre "]" et "("

  + Resultat:
   [Google Home Page](https://www.google.com)

3. Lien Local

  + input:
  \[README](/README)

      sans espace entre "]" et "("

  + Resultat:
  [README](/README)

### insister sur un mot

1. Italique

    + input:
    \*vraiment*

    + Resultat:
     *vraiment*

2. En gras

  + input:
  \*\*vraiment**

  + Resultat:
  **vraiment**

##Github Markdown

### insérer du code

1. Code pure

  + input: insérer code entre \`\`  exemple :  \``<script type="text/javascript">
  alert("Hello!");
</script>`\`

  + Resultat: `<script type="text/javascript">
  alert("Hello!");
</script>`

2. Code Colorisé (Github Flavored Markdown)

  + input:
  \```javascript
alert("Hello!");
```

  + Resultat:
  ```javascript
  alert("Hello!");
  ```
### Créer une liste de tâche

une liste de tâche peut être crée telle une liste en prenant comme "balise" les éléments - [ ] et - [X] à l'instar du + ou - d'une liste basic

    - [X] Elément terminé
    - [ ] Elément non terminé





### Créer une table

une table est initialisée en créant la  première ligne de la table comme ceci

    First Header | Second Header
    ------------ | -------------

Puis pour chaque ligne suivante, les cellules devront être séparée d'un | comme ceci

    Content from cell 1 | Content from cell 2

résultat:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2

### mentionner un autre utilisateur

pour mentionner un autre utilisateur sur un github Markdown, il suffit d'insérer un \@Nom_du_user

    exemple: @ValerianThomas





### insérer image

  + Input: \![image test]\(samuel-zeller-360588.jpg) ==> titre de l'image plus la location de l'image sur le serveur/oridnateur

  + Resultat
![image test](samuel-zeller-360588.jpg)


## That's it my friends

![gif](https://media.giphy.com/media/Um3ljJl8jrnHy/giphy.gif)
