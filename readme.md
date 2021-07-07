# Tutoriel FlexBox
👋 Bienvenue dans ce tutoriel, n'hésitez pas à [allez voir la vidéo]()(à venir).


## Terminologie
<ins>Main axis</ins> : *Axe principal, horizontale par défault, verticale si flex-direction modifié.*<br>
<ins>Cross axis</ins> : *Axe perpendiculare à l'axe principal*<br>

***
## Propriétés du container
```css
.container {
    
    display: flex;
    /* Initialise le container flex */

    flex-direction: column;
    /* Determine direction de l'axe principale (horizontal par défaut) */

    flex-wrap: nowrap | wrap | wrap-reverse;
    /* Comportement des éléments sur plusieurs lignes ou non */

    justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
    /* Aligne les éléments sur l'axe principale */

    align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end;
    /* Aligne les éléments sur l'axe secondaire */

    align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline;
    /* Si plusieurs lignes, alignes les lignes sur axe principale */
}

```
***
## Propritété sur les éléments

```css
.element {

    
}

```
