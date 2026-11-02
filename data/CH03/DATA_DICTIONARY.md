# Dictionnaire des données — CH03 LAB V1

Toutes les données sont **synthétiques** et **non marchandes**. Générateur : numpy.random.default_rng(20261102), 2400 séances ouvrées fictives. Reproductibilité dépendante des versions de NumPy.

- `date` : calendrier de jours ouvrés inventé, pas véritable calendrier de marché.
- `prix_fictif` : indice artificiel, base autour de 100 DH, construit par multiplication des facteurs de rendements.
- `rendement_pct` : rendement quotidien en points de pourcentage (`2` = 2 %).
- `innovation_pct` : choc `rendement_pct - 0.025`, en pourcentage.
- `variance_latente_pct2` : variance vraie du mécanisme simulé, en (%²), **inobservable pour les données réelles**.
- `volatilite_latente_pct` : racine carrée de la variance latente, en %.
- `z_vrai` : innovation Student-t à variance unitaire utilisée par la simulation, sans unité.

Mécanisme synthétique : `h[t] = 0.015 + (0.065 + 0.085*(eps[t-1]<0))*eps[t-1]**2 + 0.870*h[t-1]`, Student-t ν=7 standardisée, moyenne 0.025 %, `h[0]=0.015/(1-0.065-0.870-0.085/2)`.

Les fichiers sont **des références pédagogiques**, le notebook peut tout reconstruire sans eux. Les résultats de simulation ne démontrent aucune performance financière sur le marché.
