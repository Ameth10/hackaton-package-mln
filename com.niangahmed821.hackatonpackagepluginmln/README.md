# MLN Feedbacks

Package Unity de feedbacks : highlight de transforms, animation de matériaux, combinaison VFX et son.

**Documentation complète (installation, scène de démo, utilisation) : [Documentation~/hackatonpackagepluginmln.md](Documentation~/hackatonpackagepluginmln.md)**

## Installation rapide

Dans Unity : **Window > Package Manager > + > Install package from git URL**, puis colle :

```
https://github.com/Ameth10/hackaton-package-mln.git?path=/com.niangahmed821.hackatonpackagepluginmln
```

Compatible Unity 6 (6000.0) et versions suivantes.

## Contenu du package

| Élément | Rôle |
|---|---|
| `package.json` | Nom, version, description et sample du package |
| `Runtime/` | Code des feedbacks, utilisable en jeu |
| `Editor/` | Code de l'éditeur Unity (Inspector) |
| `Samples~/` | Scène de démonstration, importable depuis le Package Manager |
| `Documentation~/` | Documentation utilisateur |
| `CHANGELOG.md` | Historique des versions |
| `LICENSE.md` | Licence MIT |
| `Third Party Notices.md` | Composants tiers utilisés (aucun) |

Les dossiers terminés par `~` sont ignorés par Unity à l'import : ils ne sont pas compilés et n'encombrent pas le projet.

## Modifier le package

Le package se développe dans le projet Unity `HackatonPackage/` du [dépôt GitHub](https://github.com/Ameth10/hackaton-package-mln), qui l'utilise en local : toute modification est visible directement dans Unity. Le guide pour publier une nouvelle version est dans le README à la racine du dépôt.

## Licence

Licence MIT : libre d'utilisation, de modification et de partage, à condition de garder la mention de l'auteur. Voir [LICENSE.md](LICENSE.md).
