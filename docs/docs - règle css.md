1. ***Qu'est-ce qu'une règle CSS ?***
	<br>Une règle CSS sert à dire au navigateur:
	`sur quel élément HTML appliquer quel style`
	<br>Une règle CSS est composée de 3 parties:
	```css
	sélecteur {
		propriété: valeur;
	}
	```

	> ⚠️ **WARNING**<br>
	> ***Règles importantes:***<br>
	> Toujours `:` entre propriété et valeur<br>
	> Toujours `;` à la fin<br>
	> Les accolades `{}` sont obligatoires

	Exemple simple
	```css
	p {
		color: red;
	}
	```
	<br>Tradiction humaine:
	`Tous les <p> auront un texte rouge`

2. ***Les 3 parties d'une règle CSS***
	#### Le sélecteur
	C'est tout ce qui est à cibles
	> ℹ️ **NOTE**<br>
	> Il y a tois (03) types de sélecteur:<br>
	> **Sélecteur de balise**<br>
	> **Sélecteur de classe**<br>
	> **Sélecteur d'ID**<br>
	> 💡 **TIP**<br>
	> Ces sélecteurs peuvent être combinés mais certains sont prioritaire que d'autres,<br>
	> **ID**<br>
	> **Classe**<br>
	> **Balise**

	- Exemple:<br>
	`p` -> toutes les balises `<p>`<br>
	`h1` -> tous les titres `<h1>`<br>
	`.box` -> tous les éléments avec `class=box`<br>
	`#menu` -> tous les éléments avec `id=menu`

	#### La propriété
	C'est tout ce qui est à modifier
	- Exemple:<br>
	`color` -> couleur du texte<br>
	`background-color` -> couleur de fond<br>
	`font-size` -> taille du texte<br>
	`margin` -> espace extérieur<br>
	`padding` -> espace intérieur

	#### La valeur
	C'est par quoi la propriété sera modifier
	- Exemple:<br>
	`red`, `blue`, `#222`<br>
	`16px`, `2em`, `100%`<br>
	`center`, `bold`
