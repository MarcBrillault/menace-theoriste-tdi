# menace-theoriste-tdi
Ce dépôt a pour but de mettre en évidence, via des captures provenant de la wayback machine, les évolutions de l'article sur le TDI publié sur le blog "la menace théoriste"

## Qu'est-ce que la Wayback Machine ?

> La _Wayback Machine_ (littéralement « _machine à revenir en arrière_ ») est un site web mis à disposition par Internet Archive afin d'offrir un accès à des clichés instantanés de pages web stockés par l'organisme.
> (source [Wikipedia](https://fr.wikipedia.org/wiki/Wayback_Machine))

Le projet permet d'enregistrer certaines pages du web, automatiquement ou sur simple demande, pour archivage. La date et l'heure de consultation sont renseignées.

Ainsi, lorsqu'une page possède plusieurs enregistrements dans la wayback machine, cela permet de constater l'évolution de son contenu au fil du temps.

Le fait qu'il s'agisse d'un site indépendant garantit également sa neutralité.

## Protocole

Pour chacune des entrées présentes dans [la page d'archive de l'article disponible sur la wayback machine](https://web.archive.org/web/20210401000000*/https://menace-theoriste.fr/le-trouble-dissociatif-de-lidentite-nest-pas-ce-que-vous-pensez/) :

- Je récupèrerai la partie du code source qui correspond à l'article (Tout le contenu disponible sous le sélecteur CSS `.standard-content`)
- J'utiliserai le site [Code Beautify](https://codebeautify.org/htmlviewer) pour harmoniser le code source, avec les réglages par défaut
- À l'enregistrement, le code source sera corrigé une seconde fois par mon logiciel (Visual Studio Code)

## Historique
