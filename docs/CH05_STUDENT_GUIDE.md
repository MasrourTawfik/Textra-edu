# TRADING INTELLIGENT — CH05 v2.0 — GUIDE ÉTUDIANT

**Auteurs / cours :** Pr. Tawfik Masrour — Trading Intelligent.

## Dans quel ordre ?

**1. NB01 — Régression et ML supervisé** : apprendre le sens de X, y, des paramètres et de la perte ; calculer une droite à la main ; comparer OLS, Ridge, Lasso, régression logistique et arbre ; interpréter les scores et le surapprentissage.

**2. NB02 — Séries, fenêtres, ML financier** : transformer une série de dix rendements en matrice supervisée, vérifier retards et horizons, puis travailler sur le dataset synthétique canonique de 564 décisions du manuel. Conclure sur les contrôles temporels et le risque de fuite d'information.

## Exécution dans Google Colab

Dans Colab, importer le fichier `.ipynb` correspondant, sélectionner `Exécution > Tout exécuter`. Les bibliothèques courantes (NumPy, pandas, Matplotlib, scikit-learn) sont nécessaires. Aucune connexion à une API financière n'est requise. Si aucun CSV n'est présent, NB02 régénère le dataset synthétique depuis le code intégré.

## Méthode d'apprentissage

À chaque expérience : lire la question avant le code, formuler une prédiction, exécuter, lire les axes et unités, expliquer les écarts. Remplir les cellules « À vous » facultatives ; la suite du notebook ne dépend pas de votre réponse, ce qui permet de tester librement.

## Questions à savoir expliquer à la fin

- Pourquoi `fit` n'est pas `predict` ?
- Comment AR(1) devient-il une régression ?
- Pourquoi la matrice des retards perd-elle des lignes ?
- Que signifient L et h et la formule `N=T-L-h+1` ?
- Pourquoi la cible r[t+h] diffère-t-elle du rendement cumulé t→t+h ?
- Pourquoi la standardisation globale, les labels non matures et les données publiées plus tard peuvent-ils invalider une expérience ?
- Pourquoi accuracy / RMSE ne prouvent-ils pas une rentabilité nette ?

Les données sont inventées et ne constituent aucun conseil de trading.


## Livrables pédagogiques

NB01 : retrouver les coefficients OLS à la main, décrire les résidus, interpréter la différence entre prédiction et observation, comparer les modèles sur validation. NB02 : soumettre les quatre mini-livrables A à D en fin de notebook avec figures, assertions, note sur la maturité des labels et comparaison des métriques. Les espaces d'essai peuvent rester facultatifs pour l'exécution automatique ; ils sont obligatoires dans le rendu de l'étudiant.

**Horloge de décision :** les décisions du laboratoire sont prises après clôture ; la première cible VALIDATION ne doit jamais intervenir dans les features de cette première décision. La dernière cible TRAIN ne devient disponible qu'à cette clôture, avant prédiction pour la séance suivante.
