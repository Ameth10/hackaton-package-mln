# MLN Feedbacks

MLN Feedbacks ajoute facilement des effets de « feedback » à un jeu Unity : un objet qui rebondit quand on le touche, qui clignote quand il prend un coup, une explosion avec son bruitage…

> **État : en développement.** La structure du package est en place. Les feedbacks arrivent dans les prochaines versions : les sections « Démarrage rapide » et « Référence des feedbacks » seront complétées à ce moment-là.

## Sommaire

1. [Présentation](#présentation)
2. [Compatibilité](#compatibilité)
3. [Installation](#installation)
4. [Changer de version](#changer-de-version)
5. [Scène de démonstration](#scène-de-démonstration)
6. [Démarrage rapide](#démarrage-rapide)
7. [Référence des feedbacks](#référence-des-feedbacks)
8. [Licence](#licence)

## Présentation

Un **feedback**, c'est la réaction visuelle ou sonore d'un jeu quand il se passe quelque chose : un coup reçu, un objet ramassé, un bouton cliqué.

MLN Feedbacks propose trois familles d'effets :

| Famille | Exemples |
|---|---|
| **Transforms** | L'objet grossit puis revient (punch), tremble (shake), rebondit |
| **Matériaux** | Flash blanc, changement de couleur, lueur |
| **VFX + son** | Particules et son déclenchés en même temps |

Les effets se règlent dans l'Inspector et se déclenchent en une ligne de code.

## Compatibilité

- Unity 6 (6000.0) ou une version plus récente.
- Aucune dépendance à un autre package.

## Installation

1. Dans Unity, ouvre **Window > Package Manager**.
2. Clique sur le bouton **+** en haut à gauche, puis sur **Install package from git URL**.
3. Colle cette adresse, puis clique sur **Install** :

   ```
   https://github.com/Ameth10/hackaton-package-mln.git?path=/com.niangahmed821.hackatonpackagepluginmln
   ```

4. Le package **MLN Feedbacks** apparaît dans la liste : c'est installé.

## Changer de version

L'adresse ci-dessus installe toujours la dernière version. Pour installer une version précise, ou revenir à une version précédente, ajoute `#` suivi du nom de la version à la fin de l'adresse, puis refais l'étape 3 de l'installation :

```
https://github.com/Ameth10/hackaton-package-mln.git?path=/com.niangahmed821.hackatonpackagepluginmln#v0.3.1
```

Les versions disponibles et leurs nouveautés sont listées dans le [CHANGELOG](../CHANGELOG.md).

## Scène de démonstration

La scène de démonstration n'est pas installée avec le package, pour ne pas encombrer ton projet. Pour l'ajouter :

1. Dans le Package Manager, sélectionne **MLN Feedbacks**.
2. Ouvre l'onglet **Samples**.
3. Clique sur **Import**.

Elle est copiée dans `Assets/Samples/MLN Feedbacks/`. Tu peux la modifier ou la supprimer sans risque.

## Démarrage rapide

*À compléter avec les feedbacks.*

## Référence des feedbacks

*À compléter avec les feedbacks : la liste de chaque feedback et de ses réglages.*

## Licence

Licence MIT : libre d'utilisation, de modification et de partage, y compris dans un projet commercial, à condition de garder la mention de l'auteur. Voir [LICENSE.md](../LICENSE.md).
