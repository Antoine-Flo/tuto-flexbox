# Tutoriel FlexBox

👋 Bienvenue dans ce tutoriel, n'hésitez pas à [allez voir la vidéo]()(à venir).

## Terminologie

<ins>Main axis</ins> : Axe principal, horizontale par défault, verticale si ``flex-direction`` modifié.<br>
<ins>Cross axis</ins> : Axe perpendiculare à l'axe principal<br>

---

## Propriétés du container

```css
.container {
  display: flex;
  /* Initialise le container flex */

  flex-direction: column | row | column-reverse | row-reverse;
  /* Determine la direction de l'axe principal (horizontal par défaut) */

  flex-wrap: nowrap | wrap | wrap-reverse;
  /* Force ou non les élément à rester sur une ligne (no-wrap par défaut, pas de retour à la ligne) */

  flex-flow: column wrap;
  /* Raccourcis direction + wrap */

  justify-content: flex-start | flex-end | center | space-between | space-around
    | space-evenly;
  /* Aligne les éléments sur l'axe principale */

  align-items: stretch | flex-start | flex-end | center | baseline | first
    baseline | last baseline | start | end | self-start | self-end;
  /* Aligne les éléments sur l'axe secondaire */

  align-content: flex-start | flex-end | center | space-between | space-around |
    space-evenly | stretch | start | end | baseline | first baseline | last
    baseline;
  /* Si plusieurs lignes, les aligne sur axe principale */
}
```

---

## Propritété sur les éléments

```css
.element {

    flex-grow: 0;
    /* Détermine quelle quantité de place disponible l'élément doit occuper */

    flex-shrink: 1;
    /* Détermine capacité d'un élément à réduire sa taille si nécessaire */

    flex-basis: auto;
    /* Taille par défault de l'élément */

    flex: 0 1 auto;
    /* Raccourcis : basis grow shrink */

    align-self: auto | flex-start | flex-end | center | baseline | stretch;
    /* Modifier propriété align-items pour cet élément */

    order: 0;
    /* Modifie ordre des éléments */

}

```
