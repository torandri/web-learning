1. ***Qu'est-ce qu'une règle CSS ?***
    <p>Une règle CSS sert à dire au navigateur:
    `sur quel élément HTML appliquer quel style`
    <br>Une règle CSS est composée de 3 parties:
    ```html
    sélecteur {
        propriété: valeur;
    }
    ```
    <br>Exemple simple
    ```html
    p {
        color: red;
    }
    ```
    <br>Tradiction humaine:
    `Tous les <p> auront un texte rouge`</p>

2. ***Les 3 parties d'une règle CSS***
    #### Le sélecteur
    C'est tout ce qui est à cibles
    - Exemple:
    `p` -> toutes les balises `<p>`<br>
    `h1` -> tous les titres `<h1>`<br>
    `.box` -> tous les éléments avec `class=box`<br>
    `#menu` -> tous les éléments avec `id=menu`

    #### La propriété
    C'est tout ce qui est à modifier
    - Exemple
    `color` -> couleur du texte<br>
    `background-color` -> couleur de fond<br>
    `font-size` -> taille du texte<br>
    `margin` -> espace extérieur<br>
    `padding` -> espace intérieur

    #### La valeur
    C'est par quoi la propriété sera modifier
    - Exemple
    `red`, `blue`, `#222`<br>
    `16px`, `2em`, `100%`<br>
    `center`, `bold`