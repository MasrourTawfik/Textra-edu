# Trading Intelligent — Guide étudiant CH04 (v2.0)

## Objectif

Passer du mouvement commun de deux actifs à l'analyse d'un éventuel équilibre
relatif, puis à l'évaluation critique d'une stratégie de convergence.

## Ordre conseillé

1. Lire le [cours PDF CH04](../chapters/CH04/Trading_Intelligent_CH04_Relations_Actifs_Cointegration_Pairs_Trading_Tawfik_Masrour_v2.0.pdf) jusqu’à 4.7 : covariance, corrélation, OLS, spread, stationnarité et I(1).
2. Lire 4.8–4.10 puis exécuter [NB01](../notebooks/CH04/CH04_NB01_Relations_Cointegration_STUDENT.ipynb) : Engle–Granger, stationnarité du résidu, demi-vie, rupture.
3. Lire 4.11–4.17 puis exécuter [NB02](../notebooks/CH04/CH04_NB02_Pairs_Trading_Chronologique_STUDENT.ipynb) : signal, exécution, coûts, causalité et performance nette.
4. Terminer 4.18–4.23 : ECM, Johansen, VECM, pipeline, exercices et synthèse.

## Ressources

- [Jeu de données synthétique](../data/CH04/CH04_LAB_SYNTHETIQUE_V2.csv) : 700 jours ouvrés fictifs, graine 20261109.
- [Dépendances](CH04_LAB_REQUIREMENTS.txt) : `numpy`, `pandas`, `matplotlib`, `statsmodels`, `nbformat`, `nbclient` et `jupyterlab`.
- Les notebooks **recréent automatiquement** leurs séries en mémoire et n’exigent aucun CSV sur Colab.

## Livrables

**NB01 :** une note de 200–300 mots qui distingue une corrélation élevée,
un résidu stationnaire et une relation de long terme crédible, en discutant
les limites d'un test et le risque de rupture.

**NB02 :** une fiche de décision donnant la date du signal, la date
d'exécution, les poids notionnels, les coûts, la richesse nette et au moins
un scénario dans lequel il faut renoncer à la stratégie.

## Prudence scientifique

Les expériences sont synthétiques et reproductibles. Le backtest illustre
les mécanismes, sans prétendre mesurer une performance réelle, un coût de
prêt de titres réaliste ou le risque de liquidation sur marge.
Ne jamais évaluer une règle sur la même période que celle utilisée pour
la choisir.
