# La forme : et pourquoi pas la 3D?

Notre environnement, nos territoires, même si nous les ramenons systématiquement à un plan, restent d'abord et avant tout des espaces tri-dimensionnels.
Alors pourquoi ne pas essayer de visualiser les données proposées en 3D? Et qui plus est de manière interactive bien sur.
L'idée serait de permettre à l'utilisateur de pouvoir navihuer à la fois dans l'espace géographique de la région et des données proposées.
### Faire des choix
Parmi les variables proposées, on retiendra la production d'énergie d'un côté, et la consommation de l'autre. attention de ne pas mélanger des choux et des carottes, MWh pour la consommation , GWh pour la production. L'année la plus récente, 2022, est retenue.

### Faire évoluer la proposition en avançant

Les premières visualisations obligent à tordre un peu la représentation des données. Il s'avère nécessaires d'appliquer un facteur / 2 aux paramètres graphiques des consommations, car l'écart avec les chiffres de production est trop important et la visibilité de l'ensemble serait perturbée.

# Le fond: des territoire en "déficit" énergétique
Clairement, et ce n'est pas une surprise nos territoires consomment beaucoup plus d'énergie qu'ils n'en produisent. La question restante serait: d'ou provient l'énergie consommée?
### Un concept: l'iceberg énergétique?
Sous contraintes des outils utilisés et des choix réalisés, la visualisation nous dessine un paysage d'iceberg, la partie émergée (la production) étant significativement inférieure à la partie immergée (la consommation). Pour mémoire , la partie émmergée d'un iceberg représente en moyenne 1/10 de sa partie immergée.

# Des outils simples mais suffisants
* QGIS comme plateforme d'intégration.
* Geopackage pour le stockage des données.
* SQL pour la préparation des données.
* Plugin Qgis Qgis2threejs pour la mise en forme Web
* Dépôt et page Github pour la publication