# IBU Toolbox 🍺

Calculateur d'IBU (formule Tinseth) pour le design de recettes de bière.
Une page HTML unique dans une WebView Android, compilée en APK par GitHub Actions.

## Fonctions

- Brassin : volume après ébullition (défaut 23 L) + densité initiale (défaut 1,050)
- Houblons : liste des variétés avec acide alpha (valeur du stock sinon milieu du range), grammes et minutes ajustables au doigt
- Échelle des styles : une lane par famille BJCP, marqueur IBU, comparaison optionnelle à un style précis
- EBC (couleur) : à venir dans une carte séparée

## APK

Onglet **Actions** du dépôt → dernier run **Build APK** → artefact **MiniApp-APK** (`app-debug.apk`).
Installer en autorisant « sources inconnues » ; les mises à jour se font par remplacement de l'APK.

## Modifier

Éditer `app/src/main/assets/index.html` et pousser : l'APK se recompile automatiquement (~5 min).
