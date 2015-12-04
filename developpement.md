# dépot de développement
- https://github.com/MapContrib/MapContrib/issues
- Licence / MIT pour le moment, intégration de code propriétaire selon les interactions avec certains SIG ?

# les instances en cours
Rudomap se base sur MapContrib.
- rudomap.xyz
Il existe d'autres instances de MapContrib :
- cartes.xyz
- velo.cartes.xyz
- divers.cartes.xyz
- handi.cartes.xyz
- tiers-lieux.cartes.xyz
- don-bosco.cartes.xyz

# les livrables
## Phase 1
- Affichage :
 - filtrer les informations provenant d'OpenStreetMap à l'aide de requêtes overpass, **OK mais bug**
 - avoir plusieurs couches d'informations personnalisables,
 - définir les icônes des différentes couches en utilisant la librairie Font Awesome (http://fortawesome.github.io/Font-Awesome/icons/) ou **par un lien personnalisé**,
 - afficher du texte et des informations dynamiques dans les pop-ups de données,
 - pouvoir définir le lieu d'affichage de la carte lors de l'ouverture de l'application,
 - pouvoir choisir le fond de carte basé sur une liste de rendus définis,
 - permettre d'afficher des pages d'information et d'aides,

- Contribution :
 - permettre la connexion avec son compte OSM,
 - afficher tous les mots clés pour chaque donnée extraite d'OSM,
 - permettre de mettre en avant quelques mots clés pour faciliter la contribution,
 - pouvoir ajouter de nouveaux mots clés à des données existantes,
 - permettre l'ajout de nouveaux points en s'assurant d'éviter la création de doublons, **en cours**
 - permettre l'ajout de "note", **à faire**

-Ergonomie :
 - séparer visuellement les différentes fonctions (affichage, contribution, configuration),
