1. Les balises principales de structure
	#### `<html>`
	- La balise racine de tout document HTML
	- Contient tout le contenu de la page
	- Exemple
		```html
		<DOCTYPE html>
		<html lang="fr">
			<head>
				<meta charset="UTF-8">
				<title>Titre</title>
			</head>
			<body>
				<!--- contenu --->
			</body>
		</html>
		```

	#### `<head>` et `<body>`
	- `<head>` contient les métadonnées, le titre, les liens CSS/JS, les meta tags, favicon...
	- `<body>` contient tout le contenu visible de la page (texte, images, boutons...)

2. Les balises de structure de contenu (sémantiques)
	Ces balises servent à décrire le rôle de chaque section, pas juste à styliser

	#### `<header>`
	- Représente l'en-tête d'une page ou d'une section
	- Contient souvent : logo, menu, titre principal
	- Exemple
		```html
		<header>
			<h1>Titre principal</h1>
			<nav>Menu</nav>
		</header>
		```

	#### `<nav>`
	- Représente une zone de navigation
	- Contient généralement des liens vers d'autres pages
	- Exemple
		```html
		<nav>
			<ul>
				<li><a href="#">Accueil</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
		```

	#### `<main>`
	- Contenu principal unique de la page
	- **Ne doit apparaître qu'une seule fois par page**
	- Exemple
		```html
		<main>
			<h2>Articles récents</h2>
			<p>Voici le contenu principal...</p>
		</main>
		```

	#### `<section>`
	**Doit avoir un titre pour être accessibles**
	- Représente une section thématique
	- Peut contenir un titre `<h2>` ou `<h3>`
	- Exemple
		```html
		<section>
			<h2>À propos</h2>
			<p>Texte sur la section à propos</p>
		</section>
		```

	#### `<article>`
	**Doit avoir un titre pour être accessibles**
	- Représente un contenu indépendant: article, blog, post, commentaire
	- Idéal pour les éléments réutilisables
	- Exemple
		```html
		<article>
			<h2>Titre de l'article</h2>
			<p>Contenu de l'article...</p>
		</article>
		```

	#### `<aside>`
	- Contenu annexe, complémentaire au contenu principal
	- Comme: sidebar, publicités, citations
	- Exemple
		```html
		<aside>
			<h3>Liens utiles</h3>
			<ul>
				<li><a href="#">Lien 1</a></li>
				<li><a href="#">Lien 2</a></li>
			</ul>
		</aside>
		```

	#### `<footer>`
	- Pied de page pour une page ou une section
	- Contient: copyright, liens secondaires, infos contact
	- Exemple
		```html
		<footer>
			<p>&copy; 2025 Mon site</p>
		</footer>
		```
3. Autres balises utiles pour structurer
	- **`<div>`:** conteneur générique non sémantique, pour grouper des éléments
	- **`<span>`:** conteneur en ligne, souvent pour appliquer du style à du text
	- **`<h1>` à `<h6>`:** titres, hierarchie des sections
	- **`<p>`:** paragraphe
	- **`<ul>`, `<ol>`:** listes
	- **`<li>`:** élément de liste
	- **`<figure>` et `<figcaption>`:** image avec légende
